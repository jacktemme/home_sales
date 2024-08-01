## PySpark Analysis

This repository contains a jupyter notebook that utilizes PySpark and SparkSQL to query and analyze home sales data based off of features such as square feet, number of bedrooms, date it was built, etc. The data was cached as well as partitioned to determine how these differences impact the run time of querying the data. Both changes showed slight decreases in runtime. Caching is when data is stored in  a temporary area to create faster access to data retrieval. While partioning divides up data into smaller more manageabe peices, in this case the date built, which allows for more efficient retrieval.
