## Purpose of the Lab

The purpose of this lab was to explore clustering techniques using 
Hierarchical Clustering and DBSCAN on the Wine dataset from scikit-learn. 
The lab focused on understanding how these algorithms group data points, 
how parameter choices affect results, and how clustering quality can be 
interpreted through visualizations and evaluation metrics.

## Key Insights

Hierarchical Clustering produced clearer and more interpretable clusters 
for the Wine dataset. The dendrogram showed a natural grouping structure, 
and the clustering results aligned better with the known class patterns.

DBSCAN showed that parameter tuning is very important. Smaller eps values 
caused many points to be labeled as noise, while larger values produced 
fewer clusters. This demonstrated DBSCAN’s sensitivity to parameter 
selection and its ability to identify noise points.

Overall, Hierarchical Clustering was more effective on this dataset, while 
DBSCAN was useful for showing how density-based methods handle noise and 
outliers.

## Challenges and Decisions

One challenge in this lab was selecting appropriate DBSCAN parameters. 
Initial parameter values caused all points to be treated as noise, so 
eps had to be adjusted to produce usable clustering results. Another 
important step was standardizing the dataset before clustering, since 
both Hierarchical Clustering and DBSCAN rely on distance calculations.
