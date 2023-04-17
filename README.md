# Google-Fiber-BI

The Google Fiber case study  is a capstone project for Google Business Intelligence Professional Course that will go through each step of the BI Process. Which are: 

* [Project Planning](https://github.com/SCantergiani/Google-Data-Analytics-Certificate/blob/main/SQL%20&%20Power%20BI%20Version/SQL%20&%20Power%20BI%20Version.md#ask)
* [Data Preparation](https://github.com/SCantergiani/Google-Data-Analytics-Certificate/blob/main/SQL%20&%20Power%20BI%20Version/SQL%20&%20Power%20BI%20Version.md#prepare)
* [Deshboard Design](https://github.com/SCantergiani/Google-Data-Analytics-Certificate/blob/main/SQL%20&%20Power%20BI%20Version/SQL%20&%20Power%20BI%20Version.md#process)

### Tools Used

* SQL - BigQuery for data preparation and processing.
* Tableau - for further analysis and data visualizations.
* Github- for store codes and changelogs into notebooks.

### Resources

* Details of the case study can be found [here](https://drive.google.com/file/d/1OviIa6kTO48-rZu8fvniFVScWMq2KSES/view?usp=sharing).
* The dataset used can be download [here](https://github.com/SCantergiani/Google-Data-Analytics-Certificate/blob/main/R%20&%20Tableau%20Version/R%20&%20Tableau%20Version.md#google-data-analytics-certificate-capstone-project).
* * Link to the Dashboard hosted in Tableau Public can be found [here](https://public.tableau.com/views/GoogleFiber/Dashboard?:language=en-US&:display_count=n&:origin=viz_share_link).

## Data Planning

Loading the CSV files into GCP

Merging tables

```sql
SELECT
  *
FROM
  `markets.market1`
UNION ALL
SELECT
  *
FROM
  `markets.market2`
UNION ALL
SELECT
  *
FROM
  `markets.market3`
```

Total rows: 1350

Download the new consolidated CSV and upload to Tableau.

## Tableau

1) Load the data
2) Make problem type chart and change name to reflect the problems (Count distinct contacts N)

[![](Images/Dashboard.png)](https://github.com/SCantergiani/Google-Fiber-BI#google-fiber-bi)
