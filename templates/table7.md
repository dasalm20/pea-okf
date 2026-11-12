---
{
  "generated": {
    "by": "process:build-wbg-okf"
  },
  "help_center_commit": "sanitized:3922b3bfe000a87b8aae5305d8d9417ff53718922349db932f5eb85ceef1342d",
  "type": "Guide"
}
---

# Generic Table 7 do-file template

This is the documented Table 7 example adapted only to generic placeholders. Load the intended survey first, confirm variable definitions, weights, welfare/poverty-line units and dependencies. Replace ISO3 wherever used and each survey-year placeholder 0000 before running; do not replace a PPP base with a survey year. Existing correct derived variables should be retained rather than regenerated. Static syntax/template validation is not a successful Stata run.


Welfare option: `welfare(welfppp)` with `povlines(pline300)`.

`VERIFIED_STATIC` `povlines()` takes one variable here. `Stata/plus/p/pea_table7.ado:L22-L22`.

`VERIFIED_STATIC` Call options: `Stata/plus/p/pea_table7.ado:L22-L22`.

```stata
confirm new file "pea_table7.xlsx"
putexcel set "pea_table7.xlsx", sheet("Contents") replace
putexcel A1 = "PEA output"
putexcel clear

* GMD example conversion; use only with matching annual welfare and factors.
gen double welfppp = welfare/cpi2021/icp2021/365
label variable welfppp "Daily welfare (2021 PPP)"
gen double pline300 = 3.00
label variable pline300 "3.00 per day (2021 PPP)"

pea_table7 [aw=weight_p], ///
    welfare(welfppp) povlines(pline300) year(year) age(age) male(male) edu(educat4) ///
    vulnerability(1.5) pppyear(2021) excel("pea_table7.xlsx")
```

[Full record: pea_table7](../lookup/sources/Stata_package/commands/pea_table7.md.md).

[Complete prerequisites](../lookup/sources/Stata_package/TEMPLATES.md.md) · [Command contract](../lookup/sources/Stata_package/commands/pea_table7.md.md).
