# Data Quality Report

## Overview
This report summarizes the findings from the data quality audit performed on the D2C customer churn datasets.

## Missing Values
- `customers`: `loyalty_tier` (57.75%) and `skin_type` (16.71%) have significant missing values.
- `orders`: `rating` has 0.8% missing values.

## Duplicates
No duplicate records were found across any of the datasets.

## Outliers
Outliers were observed in numerical columns such as `quantity`, `gross_amount`, `discount_pct`, and `delivery_days` in the `orders` dataset, as visualized by box plots.

## Date Consistency
All date columns were converted to datetime objects and checked for future dates. No inconsistencies were found.
