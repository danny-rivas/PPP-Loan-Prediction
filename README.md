# PPP-Loan-Prediction
University of Maryland, Info Challenge 2022

Team 32: Danny Rivas, Javan Reuto
## HTML Files
[Analysis.htm]](https://github.com/danny-rivas/PPP-Loan-Prediction/blob/0e5753974908d202d2dfcc2d9e0c16c6ae0b12cd/IC22032_PPPGA_02_Analysis-2.html)

## Abstract

In response to 2020 COVID pandemic, Congress took the initiative to enact the Paycheck Protection Program that provided loans to small businesses in the US. The program aimed at retaining payrolls. The distribution of these loans was overseen by the Small Business Administration and administered by private lenders who would submit applications to the government. The SBA offers data on applicants; however, some applications that were previously in the data of 11.5 million applications were removed.

Our goal for this project is primarily to investigate why some applications were removed from the data. We will first focus on characteristics such as business NAICS code, Low-Moderate Income (LMI) indicator, and HubZone indicator. In addition, we plan to explore how applicants varied in characteristics, such as race, income levels, and poverty levels. Given we don’t have these metrics in our original dataset, we will be adding it to compare to metrics that were given. Ultimately, we would like to know of the characteristics of businesses that were not able to benefit from the program.

For this project, we will be using loans given in Georgia as well as data provided by US Census. We will use Python to clean and explore our data, Tableau to create visualizations, and R to predict why some data was removed.

## Data Sources
* [US Census Bureau](https://data.census.gov/cedsci/all?q=georgia)
* [American Community Survey](https://data.census.gov/cedsci/all?q=georgia)
* [Data World](https://data.world/sasha/2017-2022-sic-to-naics-crosswalk/workspace/file?filename=2017-2022+SIC+to+NAICS+crosswalk.csv)
* [NAICS Association](https://www.naics.com)
