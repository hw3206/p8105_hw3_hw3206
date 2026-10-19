# Source files

Files downloaded from the [Homework 3 assignment](https://p8105.com/homework_3.html) on October 19, 2026:

- `nhanes_covar.csv`: <https://p8105.com/data/nhanes_covar.csv>. Four metadata rows precede the column names. Sex: 1 = male, 2 = female. Education: 1 = less than high school, 2 = high school equivalent, 3 = more than high school.
- `nhanes_accel.csv`: <https://p8105.com/data/nhanes_accel.csv>. Columns `min1` through `min1440` are minute-level MIMS values beginning at midnight; `SEQN` is the participant identifier in both NHANES files.
- `Jan 2020 Citi.csv`, `July 2020 Citi.csv`, `Jan 2024 Citi.csv`, `July 2024 Citi.csv`: extracted from the four inner archives in <https://p8105.com/data/citibike.zip>. These are the supplied 1% samples of trips under four hours. Year and month come from the filenames.

The CSV files are kept as supplied. Cleaning is done in the R Markdown document. The NOAA data are loaded from `p8105.datasets` and are deliberately not saved here.
