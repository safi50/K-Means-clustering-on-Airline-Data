# Airline K-Means Clustering

This project performs K-Means clustering on airline data using PySpark. The goal is to group flights into clusters based on their `AirTime` and `Distance` to identify patterns or similarities.

## Running the Project

1. Ensure you have PySpark installed.
2. Download the `airlines1.csv` dataset and place it in the project directory.
3. Run the provided Python script to perform the clustering and evaluate the results.

## Example Output

```
+-------+--------+-------+--------+-------------+
| Origin|    Dest|AirTime|Distance|     features|
+-------+--------+-------+--------+-------------+
|    MSP|     SLC|    153|    1595|[153.0,1595.0]|
|    MSP|     SLC|    149|    1595|[149.0,1595.0]|
|    MSP|     SLC|    148|    1595|[148.0,1595.0]|
...
+-------+--------+-------+--------+-------------+

Silhouette with squared euclidean distance = 0.74
```
