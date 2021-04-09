# RM-fault-detection-in-dhs

These RapidMiner models are used for the fault detection of district heating substations (DHSs) using typical smart meter data, which is discussed in more detail in our paper "Fault detection and condition monitoring in district heating using smart meter data" (submitted to the 6th European Conference of the PHM Society).

Based on our publication (see Davies-Bouldin-Index in sect. 3.1.1), we have published a model for DHS with k = 2 clustering and with k = 3 clustering. To calculate the Davies-Boulding-Index of a DHS, the "Cluster Distance Performance" operator can be used with the corresponding main criterion "Davies Bouldin".

The JSON file "Regression_Clustering_chart_config" should be loaded in order to visually examine the result of the regression analysis. For each cluster, this shows the distribution of the data points and the regression line between power (kW) and outdoor temperature (°C):

<img src="https://user-images.githubusercontent.com/81910313/114170197-db348980-9932-11eb-95be-eeeb07d54f59.png" width="500">
