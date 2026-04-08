# Introduction

This folder contains a copy of the data we (Group E) used for our project for EEB313 (Winter 2026)

**Name:** EEB313 Project Data

**Source:** [North American Breeding Bird Survey](https://www.pwrc.usgs.gov/BBS/PublicDataInterface/index.cfm?fuseaction=PublicDataInterface.viewStateSummaryReport)

**Method:** We copied our data from the site into a single spreadsheet and tagged which US state or Canadian province the data is from.



## Columns of the spreadsheet and what they refer to

| Column Name | What it refers to | Character Type| 
| :--- | :----: | :---: |
| State | The state / province where the data is gathered | String |
| Species List | The name of the species surveyed, Total Species, Route Count , or Total individuals | String |
| 1966 - 2022 | Data for each year | Numeric |

###### Note on 1966, 1967, and 2020: A lot of the data that year was logged as "-" on the site due to the data not being collected that year. These characters were removed during preprocessing so the values would show up correctly as NA (numeric) in R. No information was lost from doing this
