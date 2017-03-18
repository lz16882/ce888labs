# Lab6


- [ ] Use a seaborn pairplot ``sns.pairplot()`` to visualise the data, the plot is shown below
![pairplot](./pairplot1.pdf?raw=true)
- [ ] Loop over different cluster size starting from 2 until 10, using all the features present and pick the one with the lowest silhouette score. The lowest silhouettescore is 0.284, with the number of clusters being 2.
- [ ] Save 10 runs for each cluster size and use a seaborn pointplot without joining the lines to plot the confidence intervals for the silhouette score. The followed figure is the result
![kmeans](./pointplot.pdf?raw=true)
- [ ] Change your clusterer to ``AgglomerativeClustering``  and re-do the above experiment. The result is shown in the following figure
![AgglomerativeClustering](./Agg.pdf?raw=true)

