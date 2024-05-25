Algorithm:
1.Load and Prepare the Data:
-Read the CSV file containing the vessel positions( "lat", "lon"), timestamps, and MMSI numbers.
-Ensure the data is sorted by timestamp to facilitate time-based proximity checks.
2.Vectorized Distance Calculation:
-Convert latitude and longitude to radians.
-Create a KDTree for spatial indexing.
-Get all pairs of points within the threshold distance.
3.Vectorized Proximity Checks:
-Iterate through pairs and calculate distances.
  *Calculate distance using vectorized Haversine formula.
4.Output
