# Bosch-Production-Line-Performance
Preprocessing

1. The raw data contains plenty of missing data. Sparsity is around 80% on average, so this allows much faster feature generation with a smaller memory footprint.
2. Creating a look-up-table that helps merging data between the numeric, categorical and timestamp datasets.
3. Clustering all samples based on the path they traversed through the manufacturing lines.

Feature Engineering
1. Numerical
2. Time
3. Category

a. Correlation with next/previous samples after sorting by t_max, t_min
b. Correlation with next/previous samples after sorting by numerical values
