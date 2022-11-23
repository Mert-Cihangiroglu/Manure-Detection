# Manure-Detection
Detection of Manure Applications using Sentinel-2 Satellite Data.

## Process

- Download Dusaf Data Set. Contains polygons from Lombardia/Italy. 
- Dusaf dataset cleaning had to be done. There're many areas that we don't need. 
- I filtered the dataset in QGIS by selecting only rice fields. '213 ¿ risaie' in Dusaf DataSet. Export new features as shape file.
- Upload the shape file to Google Earth Engine.
- Run time series analysis on the given polygons. 
- The index we're testing is EOM, which is the Normalized Difference between Band 12 and Band 4 in Sentinel Data.

### References

- EOM Index is first stated in the following paper. https://www.mdpi.com/2072-4292/13/9/1616/htm
