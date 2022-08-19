# Cryptocurrency Unsupervised Learning
## *Classify Currently Traded Cryptocurrencies for New Investment Portfolio*
### Project Overview: Look for groupings, trends, or other information that could help pitch cryptocurrencies to Accountability Accounting's firm for successful investment, and visualize our findings.
---

</br>
Accountability Accounting tasked us with creating an unsupervised machine learning algorithm, to develop a "cutting-edge" cryptocurrency investment portfolio for its customers.  We began cleaning and whittling the data down to the features of "algorithm," "proof type," "total coins mined" and "total coint supply," then optimized and scaled our data to prepare for the unsupervised machine learning model.
</br>
</br>

We clustered the cryptocurrencies using k-means clustering, intended to group similar data points together and discover underlying patterns. We reduced the data dimensions using PCA and used tools such as hvplot to continue to optimize our machine learning model.  We then visualized our results using a plotly scatterplot:
</br>

<img align="right" src="https://github.com/ajcurtis916/cryptocurrencies/blob/main/resources/total_coins_scatter.png" width="500"/>

The scatterplot shows most of the data fell into classification 0 or 3 out of 4 possible classes (0-4). Class 0 and 3 clusters gravitated towards no to minimal total coin supply and total coins mined, which were positively correlated.
</br>

Class 1 was not observed on the graph, and one clustered data point for class 2 was observed on the opposite side of the graph.  Class 2 also shows a positive correlation between total coin supply and total coins mined, but was close to 1 for both.

