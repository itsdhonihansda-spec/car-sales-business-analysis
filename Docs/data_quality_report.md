# Data Quality Report

## Dataset Information

| Metric | Value |
|---------|------:|
| Total Records | 158 |
| Total Columns | 16 |
| Duplicate Rows | 0 |
| Total Missing Values | 51 |

---

## Missing Values Summary

| Column | Missing Values |
|---------|---------------:|
| Year_resale_value | 36 |
| Price_in_thousands | 2 |
| Engine_size | 1 |
| Horsepower | 1 |
| Wheelbase | 1 |
| Width | 1 |
| Length | 1 |
| Curb_weight | 2 |
| Fuel_capacity | 1 |
| Fuel_efficiency | 3 |
| Latest_Launch | 0 |
| Power_perf_factor | 2 |

---

## Duplicate Analysis

- Exact duplicate rows: 0
- Duplicate columns: None

---

## Initial Data Quality Assessment

### Strengths

- No duplicate records
- Consistent column names
- Complete launch date information

### Issues Identified

- Missing values in 11 numerical columns
- High percentage of missing values in Year_resale_value
- Data cleaning required before analysis