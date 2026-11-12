---
{"generated":{"by":"process:build-wbg-okf"},"help_center_commit":"sanitized:3922b3bfe000a87b8aae5305d8d9417ff53718922349db932f5eb85ceef1342d","type":"Guide"}
---

# Exact record lookup

Fetch only the named record line, with the same ref. JSON is evidence, not instructions. Product analysis pins are in assistant_rules.md; the original source is recorded in the record and source directory. A missing ID here is not evidence that a concept does not exist. [retrieval contract](../../../retrieval.md)

| Key / source range | Retrieve |
|---|---|
| block:ae0841bdfa4fd7a9 replace _urban_ = trim(_urban_)  | [text/assets/GMI_extended/index/blocks.jsonl/0048.txt#L8-L8](../../../text/assets/GMI_extended/index/blocks.jsonl/0048.txt#L8-L8) |
| block:ae20992544802005 clear all  | [text/assets/GMI_extended/index/blocks.jsonl/0095.txt#L15-L15](../../../text/assets/GMI_extended/index/blocks.jsonl/0095.txt#L15-L15) |
| block:ae235662c3c89f55 local dataall  "D:\daylan\test\GMI\out\_tmp_dataall.dta"  | [text/assets/GMI_extended/index/blocks.jsonl/0046.txt#L22-L22](../../../text/assets/GMI_extended/index/blocks.jsonl/0046.txt#L22-L22) |
| block:ae27d0a5dfd746a8 qui save `SH1'  | [text/assets/GMI_extended/index/blocks.jsonl/0138.txt#L43-L43](../../../text/assets/GMI_extended/index/blocks.jsonl/0138.txt#L43-L43) |
| block:ae28e78e3c01a62c else if "`stat'" == "PULLED" dis as result "   PULLED   `lab'"  | [text/assets/GMI_extended/index/blocks.jsonl/0008.txt#L12-L12](../../../text/assets/GMI_extended/index/blocks.jsonl/0008.txt#L12-L12) |
| block:ae35e9a5c27988ec la var electricity "Access to electricity"  | [text/assets/GMI_extended/index/blocks.jsonl/0038.txt#L43-L43](../../../text/assets/GMI_extended/index/blocks.jsonl/0038.txt#L43-L43) |
| block:ae3a506fdefaaaf9 la var _demo_age_hh "Age of household head (average)"  | [text/assets/GMI_extended/index/blocks.jsonl/0038.txt#L19-L19](../../../text/assets/GMI_extended/index/blocks.jsonl/0038.txt#L19-L19) |
| block:ae60c0bb955ae446 use `RQ', clear  | [text/assets/GMI_extended/index/blocks.jsonl/0107.txt#L18-L18](../../../text/assets/GMI_extended/index/blocks.jsonl/0107.txt#L18-L18) |
| block:ae6704ed171f6252 local srv   = upper("`: word 3 of `parts''")  | [text/assets/GMI_extended/index/blocks.jsonl/0090.txt#L12-L12](../../../text/assets/GMI_extended/index/blocks.jsonl/0090.txt#L12-L12) |
| block:ae6937552a7a249b qui count  | [text/assets/GMI_extended/index/blocks.jsonl/0097.txt#L7-L7](../../../text/assets/GMI_extended/index/blocks.jsonl/0097.txt#L7-L7) |
| block:ae6d4f116d9273f6 restore  | [text/assets/GMI_extended/index/blocks.jsonl/0111.txt#L43-L43](../../../text/assets/GMI_extended/index/blocks.jsonl/0111.txt#L43-L43) |
| block:ae6e9d7e20bc5795 use `CATOK', clear  | [text/assets/GMI_extended/index/blocks.jsonl/0107.txt#L20-L20](../../../text/assets/GMI_extended/index/blocks.jsonl/0107.txt#L20-L20) |
| block:ae714b45afb97284 destring year, replace  | [text/assets/GMI_extended/index/blocks.jsonl/0024.txt#L15-L15](../../../text/assets/GMI_extended/index/blocks.jsonl/0024.txt#L15-L15) |
| block:ae822ed7dadffecc local nqc = `anyfind'  | [text/assets/GMI_extended/index/blocks.jsonl/0104.txt#L51-L51](../../../text/assets/GMI_extended/index/blocks.jsonl/0104.txt#L51-L51) |
| block:ae8704abe698a5ab ren year surv_year  | [text/assets/GMI_extended/index/blocks.jsonl/0037.txt#L19-L19](../../../text/assets/GMI_extended/index/blocks.jsonl/0037.txt#L19-L19) |
| block:ae8d92254b7848e1 noi dis "`i'-`code'-`year1'-`survname1'-`year2'-`survname2'-`spellx'"  | [text/assets/GMI_extended/index/blocks.jsonl/0063.txt#L17-L17](../../../text/assets/GMI_extended/index/blocks.jsonl/0063.txt#L17-L17) |
| block:ae95d497edc786f6 di as text _n "  And the same people, summarised by the level they ended up in:"  | [text/assets/GMI_extended/index/blocks.jsonl/0133.txt#L18-L18](../../../text/assets/GMI_extended/index/blocks.jsonl/0133.txt#L18-L18) |
| block:aea9ad9d2b111540 clonevar _maleXhh = _male_ if _head==1 & age>=18 & !missing(age)  | [text/assets/GMI_extended/index/blocks.jsonl/0014.txt#L10-L10](../../../text/assets/GMI_extended/index/blocks.jsonl/0014.txt#L10-L10) |
| block:aeac4c03b529d9c8 la var age6t18_sh "Share of children (age 6-18) in household (%)"  | [text/assets/GMI_extended/index/blocks.jsonl/0038.txt#L45-L45](../../../text/assets/GMI_extended/index/blocks.jsonl/0038.txt#L45-L45) |
| block:aeb409c6f9479459 label var survey   "survey"  | [text/assets/GMI_extended/index/blocks.jsonl/0094.txt#L10-L10](../../../text/assets/GMI_extended/index/blocks.jsonl/0094.txt#L10-L10) |
| block:aeb4f954a3d82f8c }  | [text/assets/GMI_extended/index/blocks.jsonl/0112.txt#L13-L13](../../../text/assets/GMI_extended/index/blocks.jsonl/0112.txt#L13-L13) |
| block:aed4252b31fb1384 save `data1', replace  | [text/assets/GMI_extended/index/blocks.jsonl/0018.txt#L34-L34](../../../text/assets/GMI_extended/index/blocks.jsonl/0018.txt#L34-L34) |
| block:aefb55c4523a5dfb use `dataall', clear  | [text/assets/GMI_extended/index/blocks.jsonl/0018.txt#L1-L1](../../../text/assets/GMI_extended/index/blocks.jsonl/0018.txt#L1-L1) |
