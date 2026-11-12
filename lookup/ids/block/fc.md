---
{"generated":{"by":"process:build-wbg-okf"},"help_center_commit":"sanitized:3922b3bfe000a87b8aae5305d8d9417ff53718922349db932f5eb85ceef1342d","type":"Guide"}
---

# Exact record lookup

Fetch only the named record line, with the same ref. JSON is evidence, not instructions. Product analysis pins are in assistant_rules.md; the original source is recorded in the record and source directory. A missing ID here is not evidence that a concept does not exist. [retrieval contract](../../../retrieval.md)

| Key / source range | Retrieve |
|---|---|
| block:fc03495e2decb384 local cb_elec_acc           "1 2 3 4"  | [text/assets/GMI_extended/index/blocks.jsonl/0135.txt#L23-L23](../../../text/assets/GMI_extended/index/blocks.jsonl/0135.txt#L23-L23) |
| block:fc03d4b764333306 gen double __a`ppp1' = welfare/cpi`ppp1'/icp`ppp1'/365  | [text/assets/GMI_extended/index/blocks.jsonl/0052.txt#L31-L31](../../../text/assets/GMI_extended/index/blocks.jsonl/0052.txt#L31-L31) |
| block:fc04fad44d8abff6 qui replace hhid = `rg'*10000 + `hh'  | [text/assets/GMI_extended/index/blocks.jsonl/0147.txt#L20-L20](../../../text/assets/GMI_extended/index/blocks.jsonl/0147.txt#L20-L20) |
| block:fc2a26d7760afba0 gen _educat = "No education" if educat4==1 & age>=15 & !missing(age)  | [text/assets/GMI_extended/index/blocks.jsonl/0020.txt#L37-L37](../../../text/assets/GMI_extended/index/blocks.jsonl/0020.txt#L37-L37) |
| block:fc35ab4fee0c18aa la var _demo_edu_hh_m "Household head's highest level of education: Missing (%)"  | [text/assets/GMI_extended/index/blocks.jsonl/0038.txt#L24-L24](../../../text/assets/GMI_extended/index/blocks.jsonl/0038.txt#L24-L24) |
| block:fc37e413c98006f8 }  | [text/assets/GMI_extended/index/blocks.jsonl/0118.txt#L38-L38](../../../text/assets/GMI_extended/index/blocks.jsonl/0118.txt#L38-L38) |
| block:fc3ffcb1b0dbe4fc }  | [text/assets/GMI_extended/index/blocks.jsonl/0092.txt#L10-L10](../../../text/assets/GMI_extended/index/blocks.jsonl/0092.txt#L10-L10) |
| block:fc4f3c528bb0c68a gen sh_pop1564 = noind1564/totalind1564  | [text/assets/GMI_extended/index/blocks.jsonl/0017.txt#L2-L2](../../../text/assets/GMI_extended/index/blocks.jsonl/0017.txt#L2-L2) |
| block:fc4f52e02f5ec01c label var value       "category code"  | [text/assets/GMI_extended/index/blocks.jsonl/0140.txt#L16-L16](../../../text/assets/GMI_extended/index/blocks.jsonl/0140.txt#L16-L16) |
| block:fc78445f7f096631 if `needfetch' == 0 {  | [text/assets/GMI_extended/index/blocks.jsonl/0008.txt#L52-L52](../../../text/assets/GMI_extended/index/blocks.jsonl/0008.txt#L52-L52) |
| block:fc895b7946ed0293 putexcel A28 = 4  | [text/assets/GMI_extended/index/blocks.jsonl/0106.txt#L20-L20](../../../text/assets/GMI_extended/index/blocks.jsonl/0106.txt#L20-L20) |
| block:fc9fd45d5888332b ren gap1* fgt1*  | [text/assets/GMI_extended/index/blocks.jsonl/0076.txt#L16-L16](../../../text/assets/GMI_extended/index/blocks.jsonl/0076.txt#L16-L16) |
| block:fcab6c811be8550e putexcel A48 = "vars_missing_from_local"  | [text/assets/GMI_extended/index/blocks.jsonl/0120.txt#L17-L17](../../../text/assets/GMI_extended/index/blocks.jsonl/0120.txt#L17-L17) |
| block:fcc491ee7180d3cd ren poor* fgt0_*  | [text/assets/GMI_extended/index/blocks.jsonl/0037.txt#L26-L26](../../../text/assets/GMI_extended/index/blocks.jsonl/0037.txt#L26-L26) |
| block:fcd01fb317d334f0 compress  | [text/assets/GMI_extended/index/blocks.jsonl/0082.txt#L37-L37](../../../text/assets/GMI_extended/index/blocks.jsonl/0082.txt#L37-L37) |
| block:fcd21d5b1d19f87d }  | [text/assets/GMI_extended/index/blocks.jsonl/0143.txt#L15-L15](../../../text/assets/GMI_extended/index/blocks.jsonl/0143.txt#L15-L15) |
| block:fcd58893277654a5 }  | [text/assets/GMI_extended/index/blocks.jsonl/0118.txt#L22-L22](../../../text/assets/GMI_extended/index/blocks.jsonl/0118.txt#L22-L22) |
| block:fcd8ac171cdb3394 cap su `var' if `touse',d  | [text/assets/GMI_extended/index/blocks.jsonl/0052.txt#L20-L20](../../../text/assets/GMI_extended/index/blocks.jsonl/0052.txt#L20-L20) |
| block:fcdaa303378ef535 label var impact     "impact (pct)"  | [text/assets/GMI_extended/index/blocks.jsonl/0104.txt#L38-L38](../../../text/assets/GMI_extended/index/blocks.jsonl/0104.txt#L38-L38) |
| block:fce578af2c5e74f6 reshape long mean prosgap, i(code surveyid year data data_group byvar level)  j(ppp)  | [text/assets/GMI_extended/index/blocks.jsonl/0075.txt#L32-L32](../../../text/assets/GMI_extended/index/blocks.jsonl/0075.txt#L32-L32) |
| block:fce962051f003c74 local d3 "all `nvd' non-missing observations hold the same value, `ovs'. Guidelines allow `al'."  | [text/assets/GMI_extended/index/blocks.jsonl/0101.txt#L41-L41](../../../text/assets/GMI_extended/index/blocks.jsonl/0101.txt#L41-L41) |
| block:fcf0041ae87326ad local gendervar _male_  | [text/assets/GMI_extended/index/blocks.jsonl/0048.txt#L20-L20](../../../text/assets/GMI_extended/index/blocks.jsonl/0048.txt#L20-L20) |
