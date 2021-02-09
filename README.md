## data_analysis

### PCA plot and clustering plots 

Can be used for example for analysis of expression data matrices. 

-Creates numpy array with the  random data - the features of the created data can be changed

-centers and scales the data from the array and then calculates the PCA

-clusters the PCA output using 3 different methods: KMeans, Affinity Propagation and MeanShift

-Plots 4 graphs containing PCA and 3 graphs representing different clustering methods.

-Prints silhouette scores for every clustering method in the title of the graph.

#### Requirements 

- Python 3.5.1.
- Scikit-learn, Numpy, Matplotlib 


### Heatmap


Creates a heatmap on the basis of the data set  from http://hadobs.metoffice.com/hadsst3/ containing inf about anomalies
in sea surface temperature.

#### Requirements 

- Python 3.5.1.
- Pandas, Matplotlib, Seaborn 

