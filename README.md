# USDA SNAP Spending Study

In November 2016, the United States Department of Agriculture [published a study](https://www.fns.usda.gov/snap/foods-typically-purchased-supplemental-nutrition-assistance-program-snap-households) that used “calendar year 2011 point-of-sale transaction data from a leading grocery retailer to examine the food choices of [Supplemental Nutrition Assistance Program (SNAP)] and non-SNAP households.”

In an [appendix](https://www.fns.usda.gov/sites/default/files/ops/SNAPFoodsTypicallyPurchased-Appendices.pdf), the report ranks the total spending on major commodities by SNAP households and non-SNAP households — but as a PDF table. This repository contains the commodity spending table (`Appendix A-4`), converted to a *tab-separated values* file. That file contains seven columns:

| Column                 | Description                                                                                     |
|------------------------|-------------------------------------------------------------------------------------------------|
| `commodity`            | The name of the commodity                                                                       |
| `snap_rank`            | The rank of this commodity, by spending, among SNAP households                                  |
| `snap_spending`        | The total expenditures ($ millions) on this commodity, in this study, among SNAP households     |
| `snap_pct_of_total`    | The percentage of all expenditures that this commodity accounted for, among SNAP households     |
| `nonsnap_rank`         | The rank of this commodity, by spending, among non-SNAP households                              |
| `nonsnap_spending`     | The total expenditures ($ millions), in this study, among non-SNAP households                   |
| `nonsnap_pct_of_total` | The percentage of all expenditures that this commodity accounted for, among non-SNAP households |

 ---

 This repository is brought to you by [Data Is Plural](https://tinyletter.com/data-is-plural), a weekly newsletter of useful/curious datasets.
