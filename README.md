# CriptoClustering


In this project unsupervised learning is used to predict if cryptocurrencies are affected by price changes in different time periods.

<img
  src="Plots/coin_changes.png"
  alt="plot"
  title="12 months of precipitation"
  style="display: inline-block; margin: 10 auto; max-width: 500px">


K-Means clustering is used to group cryptocurrencies by their performance. 
Elbow method is used to calculate the the optimal number of clusters.

<img
  src="Plots/elbow_curve.png"
  alt="plot"
  title="12 months of precipitation"
  style="display: inline-block; margin: 10 auto; max-width: 500px">

 K-Means algorithm, with the optimal number of clusters, is applied on the original dataset to predict the clusters.


 <img
  src="Plots/scatter_plot.png"
  alt="plot"
  title="12 months of precipitation"
  style="display: inline-block; margin: 10 auto; max-width: 500px">

Then Principal Component Analysis (PCA) is applied to optimize the clusters. Features are reducd to three principal components. The total explained variance of the three principal components are 89%, which means 89% information is attributed to each principal component.

Again, K_Means method is applied on the new dataset (made of PC-s). The optimal number of clusters is detrmined by Elbow method.

<img
  src="Plots/elbow_curve.png"
  alt="plot"
  title="12 months of precipitation"
  style="display: inline-block; margin: 10 auto; max-width: 500px">

New clusters are predicted for the reduced features dataset.

<img
  src="Plots/scatter_plot_PCA.png"
  alt="plot"
  title="12 months of precipitation"
  style="display: inline-block; margin: 10 auto; max-width: 500px">









<br/><br/>



## References
This project is a part of UC Berkeley "Data Analysis and Visualisation" Boot Camp education services.

 
