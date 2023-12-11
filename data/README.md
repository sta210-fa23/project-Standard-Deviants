# Data

If using an external dataset (that doesn't come in an R package), place data file(s) in this folder.

Then, include metadata about your dataset including information on provenance, codebook, etc.

The codebook for your data file(s) using the following format.

## sports.csv

| Variable             | Description                                                  |
|:----------------------|:-----------------------------------------------|
| year                 | year, like 2019                                              |
| unitid               | School ID                                                    |
| instituion_name      | School name                                                  |
| city_txt             | City name                                                    |
| state_cd             | State abbreviation                                           |
| zip_text             | Zip code of school                                           |
| classification_code  | Code for school classification                               |
| classification_name  | School classification, ie. NCAA Division I-FCS               |
| classification_other | School classification if other                               |
| ef_male_count        | Total male student population amount                         |
| ef_female_count      | Total female student population amount                       |
| ef_total_count       | Total student population amount                              |
| sector_cd            | Sector code                                                  |
| sector_name          | Sector name; ie. Public, 4-year or above                     |
| sportscode           | Sport code                                                   |
| partic_men           | Participation rate for men                                   |
| partic_women         | Participation rate for women                                 |
| partic_coed_men      | Participation in coed sports for men                         |
| partic_coed_women    | Participation in coed sports for women                       |
| sum_partic_men       | Sum of participation for men                                 |
| sum_partic_women     | Sum of participation for women                               |
| rev_men              | Revenue in USD for men                                       |
| rev_women            | Revenue is USD for women                                     |
| total_rev_menwomen   | Total revenue for both men and women                         |
| exp_men              | Expenditures in USD for men                                  |
| exp_women            | Expenditures in USD for women                                |
| total_exp_menwomen   | Total expenditures for both men and women                    |
| sports               | Sport name                                                   |
| gender_r             | Amount of male population divided by female population       |
| perc_wom_exp         | Percent of expenditured that goes towards women's basketball |
| profit               | A school's revenue minus expenditures                        |
