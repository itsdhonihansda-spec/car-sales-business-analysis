| Column             | Missing | Strategy | Reason                                                  |
| ------------------ | ------: | -------- | ------------------------------------------------------- |
| Year_resale_value  |      36 | Median   | Large number of missing values; robust against outliers |
| Price_in_thousands |       2 | Median   | Price may contain outliers                              |
| Engine_size        |       1 | Median   | Protect against extreme values                          |
| Horsepower         |       1 | Median   | Performance cars may skew average                       |
| Wheelbase          |       1 | Mean     | Stable physical measurement                             |
| Width              |       1 | Mean     | Stable physical measurement                             |
| Length             |       1 | Mean     | Stable physical measurement                             |
| Curb_weight        |       2 | Mean     | Stable physical measurement                             |
| Fuel_capacity      |       1 | Mean     | Stable physical measurement                             |
| Fuel_efficiency    |       3 | Median   | Can vary significantly                                  |
| Power_perf_factor  |       2 | Median   | Derived metric may be skewed                            |
