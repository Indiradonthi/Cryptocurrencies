# Cryptocurrencies

Investment bank is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data we will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what we is looking for, we have decided to use unsupervised learning. To group the cryptocurrencies, we decided on a clustering algorithm. We’ll use data visualizations to share the findings.

This challenge consists of four technical analysis deliverables:

- Deliverable 1: Preprocessing the Data for PCA
- Deliverable 2: Reducing Data Dimensions Using PCA
- Deliverable 3: Clustering Cryptocurrencies Using K-means
- Deliverable 4: Visualizing Cryptocurrencies Results

## Results

Visualized Cryptocurrencies Results

## Elbow Curve

![image](https://user-images.githubusercontent.com/90879122/157173446-152b98c8-918a-473f-8f9a-8dcd39f244b2.png)


## 3-D Cluster

![image](https://user-images.githubusercontent.com/90879122/157173853-9c7a6762-fe2b-4086-bfd9-f4d280f3c557.png)

## Scatter Plot

![image](https://user-images.githubusercontent.com/90879122/157174011-1d324d5c-a497-4388-a4ff-3eeef5438e74.png)


## Summary


Preprocessing of data required removal of nulls, filter for traderable currencies, removal of unneeded columns and conversion of text data to numeric data. There are 532 tradable cryptocurrencies. The best k-mean value for clustering cryptocurrencies determined on a Elbow Curve chart was 4. Though fun to rotate the 3D chart, the 2D chart proved more readible for this data set.
