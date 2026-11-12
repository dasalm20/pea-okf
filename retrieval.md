---
{"generated":{"by":"process:build-wbg-okf"},"help_center_commit":"sanitized:3922b3bfe000a87b8aae5305d8d9417ff53718922349db932f5eb85ceef1342d","type":"Guide"}
---

# Retrieval contract

1. Fetch index.md and assistant_rules.md once from this deployment, using one resolved snapshot. Search covers the default branch only; keep the same ref for exact reads. Restrict search and exact reads to the deployed folder. An ingestion service must enforce this scope; repository-wide access to the maintenance repository is unsuitable.
2. Follow a topic and lookup/sources/<logical-source-label>.md. Select its section and exact file/start_line/end_line. Case and inclusive line bounds matter. Source coordinates refer to the sanitized projection, whose line count is preserved.
3. For indicator:0c37415f17c1823c read lookup/ids/indicator/0c.md. Dependencies use lookup/edges/indicator/0c.md. Known names use lookup/names/<name>.md with colons replaced by __; preserve case and verify the logical name in the row. For other escapes, collisions or a missing direct path, follow [indicator names](lookup/indicator_names.md) by labelled ranges to the exact file link; never guess hash suffixes. Select the right current/archive producer; namesakes are not identical.
4. Fetch every listed incoming/outgoing edge and reference-table child. These are recorded direct edges, not an inferred transitive graph. Preserve evidence status; explicit zero means zero recorded edges. Empty content or missing routes are failures.
5. Markdown sections retain prerequisites and qualifications. Asset source lookups translate original line ranges to bounded UTF-8 shards. Source-map fragments are annotated source excerpts, not independently runnable scripts. Country applicability placeholders must not be executed as real filters or merged into universal conditions.
6. All 84 archival assets also have sanitized UTF-8 representations. Archives and catalogs are optional build/verification artifacts, never required for answers. Use ordinary text and narrow ranges. Targets are under 1,500 startup, 5,000 routine and 12,000 complex estimated tokens; evidence takes priority.
7. Source references without hyperlinks are attribution labels. Opaque source-reference labels deliberately do not expose upstream country-specific filenames. URNs cannot retrieve originals. Cite the local evidence range and source pin; do not reconstruct a hidden URL or case identity.

[Record kinds](lookup/ids_kinds.md) · [Dependency kinds](lookup/edges_kinds.md) · [Deployment boundary](deployment.md).
