# Cryptocurrencies

## Purpose

This goal of this project was to apply unsupervised ML to the crytocurrency market. After cleaning the data, 532 activley traded coins remained. k means clustering was used to group the coins after feature reduction via PCA. Although imprecise, an elbow curve was used to estimate the optimal number of clusters. From the curve, a k means model using four clusters was employed to seperate the coins into groups. Further, a 3D visualization and a table were created based on the outcome of this model.

The highest magnitude numerical columns were then scaled using a MinMaxScaler to allow for easier production of a 2D scatterplot.