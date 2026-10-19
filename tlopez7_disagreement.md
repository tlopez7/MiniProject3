# Disagreement Examples — tlopez7 & jmurph91

## Example 1 — samreay_chainconsumer (WhyRecovered)
**Owner / Validator:** jmurph91 / tlopez7
**Author:** Development resumed with bug fixes and package maintenance.
**Validator:** The maintainer started a major rewrite (pydantic conversion, Python 3.10 prep, new docs).
**Evidence:** The first commits after the 2022-10 to 2023-09 gap are "Initial cleanup to prep for 3.10 work", "Starting pydantic conversion", "Fixing up ruff errors" and "Starting on doco". Those describe an architecture rewrite, not routine fixes.
**Resolution:** ValidatorKept. jmurph91 agreed the commits point to a deliberate rewrite as the recovery trigger.

## Example 2 — juliarobotics_rigidbodydynamics.jl (ActivityPattern)
**Owner / Validator:** jmurph91 / tlopez7
**Author:** cyclical
**Validator:** declining
**Evidence:** Yearly commits were 528, 1010, 821 and 465 for 2016–2019, then 29, 71, 3, 30, 23 and 4. That is one large drop, not activity repeating at fixed intervals, which is what the coding guide requires for "cyclical".
**Resolution:** ValidatorKept.

## Example 3 — gavinsimpson_permute, juliaopt_convex.jl, simonvh_genomepy, gsdlab_clafer (HasRecovered)
**Owner / Validator:** tlopez7 / jmurph91
**Author:** Partially / Yes, briefly / Partially / Barely
**Validator:** Yes
**Evidence:** Each project has commits after its longest gap (for example, permute fixes bug #28 after a 31-month gap, and clafer upgrades its GHC toolchain after a 50-month gap). The coding guide defines HasRecovered as strictly yes/no.
**Resolution:** ValidatorKept. tlopez7 agreed the qualified labels did not fit the binary codebook; how strong the recovery was belongs in WhyRecovered or Notes instead.

## Example 4 — comit-network_xmr-btc-swap (RecentThemes)
**Owner / Validator:** jmurph91 / tlopez7
**Author:** Other:Other
**Validator:** Automated bot contributions:Other
**Evidence:** All 10 most recent commits are auto-generated "Merge X into Y" commits from 2025-08-19. The author value also repeated the same theme twice instead of naming two themes.
**Resolution:** ValidatorKept.

## Example 5 — openclimatefix_satip, eljost_pysisyphus, dicarlolab-delft_pycqed_py3 (HasRecovered)
**Owner / Validator:** tlopez7 / jmurph91
**Author:** N/A (recorded by the validator as "Not reported in source project statistics")
**Validator:** No
**Evidence:** None of these projects has a gap of 3 or more months. The author's file literally contains "N/A", but the validator's pandas script read that string as a missing value.
**Resolution:** ValidatorKept ("No", since the codebook is binary). Both parties noted the data-loading issue so the author value is recorded correctly as N/A in the resolution file.
