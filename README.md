<p align="center"> 
  <img src="Clustering_Image.jpeg" alt="Clustering Image" width="400px" height="200px">
</p>

<h1 align="center"> Online_Retail_Customer_Segmentation </h1>


## Abstract:
Customer segmentation plays a key role in making business decisions. In the competitive field of e-commerce, it is very important to satisfy the customer needs and to identify the potential customer and these things should be done at the right time in the right manner. In this project, various segments
of customer segmentation are discussed and different techniques in customer segmentation are presented.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Problem Statement:

In this project, The task is to identify major customer segments on a transnational data set which
contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Attribute Information:

**InvoiceNo**: Invoice number. A 6-digit integral number is uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.

**StockCode**: Product (item) code. A 5-digit integral number is uniquely assigned to each distinct product.

**Description**: Product (item) name.

**Quantity**: The quantities of each product (item) per transaction.

**InvoiceDate**: Invoice Date and time. The day and time when each transaction was generated.

**UnitPrice**: Unit price. Product price per unit in sterling.

**CustomerID**: Customer number. A 5-digit integral number is uniquely assigned to each customer.

**Country**: Country name. The name of the country where each customer resides.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Introduction:

The world is getting digitalised day by day. The role of the internet in our life is becoming unavoidable. We are depending on the internet for various purposes like studies, work, shopping etc. The most common word we hear now a day is e-commerce. E-commerce is also known as internet commerce or electronic commerce. It is a modem business which works with the help of technology. E-commerce is the process of buying a product or selling a product using the internet in online mode. With the interests of customers changing from traditional shopping to online internet shopping,The customer can now shop for things anywhere in the world. This makes e-commerce more popular among people.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Models Used:

**K-means Clustering**:

The k-means algorithm searches for a pre-determined number of clusters within an unlabeled multidimensional dataset. It accomplishes this using a simple conception of what the optimal clustering looks like:
* The "cluster centres" is the arithmetic mean of all the points belonging to the cluster.
* The "cluster centres" is the arithmetic mean of all the points belonging to the cluster.

Those two assumptions are the basis of the k-means model.
Expectation–maximization (E–M) is a powerful algorithm that comes up in a variety of contexts within data science. k-means is a particularly simple and easy-to-understand application of the algorithm

1. K-means Clustering using K-Elbow - To determine the optimal number of clusters, we have to select the value of k at the “elbow” ie the point after which the inertia starts decreasing in a linear fashion. Inertia Meaning: It is calculated by measuring the distance between each data point and its centroid, squaring this distance, and summing these squares across one cluster. 

2. K-means Clustering using Silhouette Score - It is used to evaluate the quality of clusters created using clustering algorithms such as K-Means in terms of how well samples are clustered with other samples that are similar to each other. The Silhouette score is calculated for each sample of different clusters. To calculate the Silhouette score for each observation/data point, the following distances need to be found for each observation belonging to all the clusters:
Mean distance between the observation and all other data points in the same cluster. This distance can also be called a mean intra-cluster distance. The mean distance is denoted by a.
Mean distance between the observation and all other data points of the next nearest cluster. This distance can also be called a mean nearest-cluster distance. The mean distance is denoted by b.

**The Silhouette Coefficient for a sample is (b - a) / max(a,b)**

The Silhouette Coefficient value ranges from -1 to 1.

1: This means clusters are well apart from each other and clearly distinguished.

0: This means clusters are indifferent, or we can say that the distance between clusters is not significant.

-1: This means clusters are assigned in the wrong way. 

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## Conclusion:

After implementing K-means clustering using K-Elbow & Silhouette methods, I came to the conclusion that the optimal number of clusters should be 3 because it provides the opportunity to convert modest customers into important customers unlike when K = 2.


