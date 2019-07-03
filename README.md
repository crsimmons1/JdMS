# JdMS

Edit Friday, June 14th 2019

Our files:
1. **DataCleaning.ipynb**: creating the cleaned dataset, quality assurance, and modifying the data frame. Export the clean data as:
- export the data (long format - transaction table) as cleaned_data.parquet
- export the data (wide format - customer table) as customer_data.csv

2. **TDataVisualization.ipynb**: creating graphs to show relationships/trends not related to the model. Uses the transaction table.

3. **CDataVisualization.ipynb**: creating graphs to show relationships/trends not related to the model. Uses the customer table.

4. **Kmeans.ipynb**: this is the segmentation model that utilizes k-means to find our clusters.

5. **MeanShift.ipynb**: this is the segmentation model that utilizes mean shift to find our clusters.

6. **DBSCAN.ipynb**: this is the segmentation model that utilizes DBSCAN to find our clusters.

7. **GowerDistance.ipynb**: this is the file that calculates gower's distance for the customer table.

8. **MeanShift.ipynb**: this is the model running with the mean shift algorithm.

9. **PCA.ipynb**: runs the cleaned customer table through Principal component analysis, reduces the dimensions of the data so it can run smoother.

10. **UMAPS.ipynb**: runs the data through UMAPS. 


Over the course of the project we will add notes about the files of the project and what we are doing.
