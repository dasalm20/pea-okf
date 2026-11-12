# PEA AI Help Center — OKF knowledge bundle

A country-neutral knowledge bundle covering the World Bank PEA ecosystem,
packaged in Google's Open Knowledge Format (OKF v0.2) so an AI assistant can
answer technical questions about it with traceable citations.

It documents three products:

- the **PEA Stata package** (the `pea` commands)
- the **PEA Dashboard** (peaApp)
- **GMI Extended**

plus the documented relationships between them.

---

## Entry point

Start at **[`index.md`](index.md)**. Everything else is reachable from there.

An assistant should read, in order:

1. [`index.md`](index.md) — topic map
2. [`assistant_rules.md`](assistant_rules.md) — how to answer and cite
3. [`retrieval.md`](retrieval.md) — the retrieval contract

No clone, runtime scripts, decompression or full catalogs are needed. The
bundle is plain Markdown with relative links.

---

## Layout

| Path | What it holds |
|---|---|
| `index.md` | Topic map and entry point |
| `assistant_rules.md` | Answering and citation rules |
| `retrieval.md` | Step-by-step retrieval contract |
| `deployment.md` | Deployment boundary and provenance. **Read before deploying.** |
| `*.md` (topics) | Stata commands, errors, templates; GMI indicators and lineage; Dashboard; cross-product |
| `text/` | The evidence: plain-text source extracts |
| `details/` | Detail pages |
| `lookup/` | Routing index — `ids/`, `edges/`, `sources/`, `names/`, `_pages/` |
| `data/` | Compressed archives. Every one has a plain-text equivalent under `text/`. |
| `templates/` | Stata code templates |
| `catalog.json`, `manifest.json`, `retrieval_catalog.json` | Build metadata. Not needed at query time. |

File count is high by design. `lookup/` is a sharded routing index of small
stubs, so a lookup reads about 1 KB instead of loading a large catalog.

---

## How to deploy it

Supply **only this repository**, on its own, to the assistant or index.

Do not attach the parent maintenance repository, the source product
repositories, internal reports or dictionaries alongside it. A folder-level
instruction cannot restrict a repository-wide connector, which is why this
bundle lives in a repository of its own.

Full rules are in **[`deployment.md`](deployment.md)**.

### Uploading as files

The routing index reuses the same folder and file names across `lookup/ids/`
and `lookup/edges/`, and across shards. Of 7,635 files, only 3,088 filenames
are unique. **Any upload that flattens the folder structure will collide and
silently drop files.**

Connect the repository, or upload a zip. Do not drag the folder into a web
uploader, and never resolve name conflicts with "Keep both" — renaming breaks
the relative links the bundle navigates by.

---

## What it is not

- **Not country data.** Country names and codes, survey years, individual
  occupation codes and observed estimates are excluded. It cannot tell you any
  country's poverty rate.
- **Not an execution guarantee.** The bundle is statically validated against
  the source code. It does not certify that any Stata or R run succeeds, nor
  what is currently deployed.
- **Not live.** Content reflects a fixed snapshot of the source repositories.

### Evidence labels

Every claim carries one. Do not read them as stronger than they are.

| Label | Meaning |
|---|---|
| `VERIFIED_STATIC` | The source code states this |
| `PARTIAL_STATIC` | Partially evidenced in source |
| `INFERRED` | Reasoned from documented behaviour, not stated directly |
| `UNVERIFIED` | Recorded but not evidenced |
| `EXTERNAL_DEPENDENCY` | Behaviour comes from outside the package |
| `RUNTIME_CONFIRMED` | An anonymized historical observation, not proof of general prevalence |

Static evidence means the code says so. It does not mean a run was confirmed.

---

## Provenance and updates

Generated from the private maintenance repository `PEA_ai_help_center`, which
is the source of truth. This repository is a published copy: regenerate and
replace it rather than editing files here.

Source revisions and evidence classifications are preserved inside the bundle.

---

## Contact

Maintained by Daylan Salmeron, Distributional Impact of Policies, World Bank Group.
Open an issue for problems with the content.
