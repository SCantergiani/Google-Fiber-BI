# Google-Fiber-BI

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
