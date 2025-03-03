# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Kentucky Json and Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Arbie Hsu using the corresponding jupyter notebook.  As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30 m) were changed to queen adjacencies.

# **Sources**

The following obtained from [Redistricting Data Hub](https://redistrictingdatahub.org/) on March 2, 2025:

[Population data](https://redistrictingdatahub.org/dataset/kentucky-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2022-kentucky-congressional-districts-approved-plan/): 2022 Kentucky Congressional Districts Approved Plan

[State House District data](https://redistrictingdatahub.org/dataset/2022-kentucky-house-of-representatives-districts-approved-plan/): 2022 Kentucky House of Representatives Districts Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2022-kentucky-senate-districts-approved-plan/): 2022 Kentucky Senate Districts Approved Plan

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-kentucky-precinct-and-election-results/): VEST 2016 precinct and election results 

[2019 election data](https://redistrictingdatahub.org/dataset/vest-2019-kentucky-precinct-boundaries-and-election-results-shapefile/): VEST 2019 precinct and election results

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-kentucky-precinct-and-election-results/): VEST 2020 precinct and election results

[2020 County data](https://redistrictingdatahub.org/dataset/kentucky-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

## Preprocessing
Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup). 

## Metadata
- `STATEFP20`: State FIPS code
- `COUNTYFP20`: County FIPS code
- `VTDST20`: Voting tabulation district FIPS code
- `GEOID20`: Geographical ID in 2022 enacted congressional map
- `NAME20`: Voting tabulation district name
- `CD`: Congressional district ID
- `SEND`: State Senate district for 2021 State Senate Adopted Plan
- `HDIST`: State House district for 2024 State House of Representatives Districts Plan
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `AGR19D`: Number of votes for 2019 Democratic Commissioner of Agriculture candidate
- `AGR19R`: Number of votes for 2019 Republican Commissioner of Agriculture candidate
- `AGR19O`: Number of votes for 2019 other party's Commissioner of Agriculture candidate
- `ATG19D`: Number of votes for 2019 Democratic attorney general candidate
- `ATG19R`: Number of votes for 2019 Republican attorney general candidate
- `AUD19D`: Number of votes for 2019 Democratic Auditor candidate
- `AUD19R`: Number of votes for 2019 Republican Auditor candidate
- `AUD19O`: Number of votes for 2019 other party's Auditor candidate
- `GOV19D`: Number of votes for 2019 Democratic gubernatorial candidate
- `GOV19R`: Number of votes for 2019 Republican gubernatorial candidate
- `GOV19O`: Number of votes for 2019 other party's gubernatorial candidate
- `PRE16D`: Number of votes for 2016 Democratic presidential candidate
- `PRE16R`: Number of votes for 2016 Republican presidential candidate
- `PRE16O`: Number of votes for 2016 other party's presidential candidate
- `PRE20D`: Number of votes for 2020 Democratic presidential candidate
- `PRE20R`: Number of votes for 2020 Republican presidential candidate
- `PRE20O`: Number of votes for 2020 other party's presidential candidate
- `SOS19D`: Number of votes for 2019 Democratic Secretary of State candidate
- `SOS19R`: Number of votes for 2019 Republican Secretary of State candidate
- `TRE19D`: Number of votes for 2019 Democratic Treasurer candidate
- `TRE19R`: Number of votes for 2019 Republican Treasurer candidate
- `USS16D`: Number of votes for 2016 Democratic senate candidate
- `USS16R`: Number of votes for 2016 Republican senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate

