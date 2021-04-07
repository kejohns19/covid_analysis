# covid_analysis

Information related to analyzing the CDC case surveillance data set (23 million rows).

Initally processd the data by uploading into Google Big Query and applying the query identified in the big_query.txt file.  The resulting data was downloaded as the file titled "covid_cdc_survilance_summary_4-1-21.csv"

Population data was downloaded from the US Census bureau site: https://www.census.gov/newsroom/press-kits/2020/population-estimates-detailed.html.  I summarized the data by age group by the following race/ethnicity groups: Asian, Black, Hispanic, White, Other.  This file is titled "nc-est2019-asr6h.xlsx"

Finally I processed the data in the Jupyter notebook titled "Covid_analysis-altair-v2.ipynb".  I redaced my datapane license key.  The final report is automoatically uploaded to my Datapane account at the following site https://datapane.com/u/keith8/reports/covid-19-trends-by-quarter/.
