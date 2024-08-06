
# The Data

## `cancer_reg.csv`

| Column Name             | Data Type   | Description                                                                |
|-------------------------|-------------|----------------------------------------------------------------------------|
| geography               | String      | Location name.                                                             |
| avganncount             | Numeric     | Average annual count of cancer cases in the county.                        |
| avgdeathsperyear        | Numeric     | Average number of deaths per year in the county.                           |
| target_deathrate        | Numeric     | Number of deaths per 100k individuals in each county.                      |
| medincome               | Numeric     | Median household income for the county.                                    |
| popest2015              | Numeric     | Population estimates for 2015.                                             |
| povertypercent          | Numeric     | Percentage of people living in poverty.                                    |
| studypercap             | Numeric     | Number of clinical trials per capita in the given county.                  |
| binnedinc               | Categorical | Binned income for each county.                                             |
| medianage               | Numeric     | Median age of the population in the county.                                |
| medianagemale           | Numeric     | Median age of the male population in the county.                           |
| medianagefemale         | Numeric     | Median age of the female population in the county.                         |
| percentmarried          | Numeric     | Percentage of people who are married in the county.                        |
| pctnohs18_24            | Numeric     | Percentage of people aged 18-24 who did not graduate high school.          |
| pcths18_24              | Numeric     | Percentage of people aged 18-24 who graduated high school.                 |
| pctsomecol18_24         | Numeric     | Percentage of people aged 18-24 who attended some college.                 |
| pctbachdeg18_24         | Numeric     | Percentage of people aged 18-24 who have a bachelor's degree.              |
| pcths25_over            | Numeric     | Percentage of people aged 25 and over who graduated high school.           |
| pctbachdeg25_over       | Numeric     | Percentage of people aged 25 and over who have a bachelor's degree.        |
| pctemployed16_over      | Numeric     | Percentage of people aged 16 and over who are employed.                    |
| pctunemployed16_over    | Numeric     | Percentage of people aged 16 and over who are unemployed.                  |
| pctprivatecoverage      | Numeric     | Percentage of people with private health insurance.                        |

## `avg-household-size.csv`

| Column Name       | Data Type | Description                                    |
|-------------------|-----------|------------------------------------------------|
| statefips         | Integer   | State identification number.                   |
| countyfips        | Integer   | County identification number.                  |
| avghouseholdsize  | Float     | Average size of households in the county.      |
| geography         | String    | Location name.                                 |
