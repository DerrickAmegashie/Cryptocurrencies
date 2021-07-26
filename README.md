# Cryptocurrencies

Unsupervised Machine Learning and Cryptocurrencies

## Overview
The project involved the use of unsupervised learning to analyze cryptocurrency data traded on the market. I implemented machine learning models to showcase what cryptocurrencies are present on the trading market and what classifications could be developed towards the new  investment product. I used unsupervised learing there was no known output for what was in search. The data was processed to  in order to fit the machine learning models. I used a clustering algorithm to help decide on investing in this product. 

## Results & Steps

### Steps
- Prepared the data for dimensions reduction with PCA and clustering using K-means.
- Reduced data dimensions using PCA algorithms from sklearn.
- Predicted clusters using cryptocurrencies data using the K-means algorithm form sklearn.
- Created visualizations to present the clustering results.

### Results
- Total number of cryptocurrencies in the market
The data also shows below information such as coin name, algorithm, if it is trading, the proof type, if the coin is mined, and the total supply of the coin.

<img width="603" alt="Screen Shot 2021-07-24 at 9 41 22 PM" src="https://user-images.githubusercontent.com/78401776/126922154-2f9d2970-5788-4d6a-bf71-b1a0aafc8806.png">


- Reduced data dimensions using PCA algorithms from sklearn.
Developed the Principal Component Analysis (PCA) algorithm and decreased the dimensions of the X DataFrame to three (3) principal components. 

<img width="456" alt="Screen Shot 2021-07-24 at 9 41 36 PM" src="https://user-images.githubusercontent.com/78401776/127034924-16fcacef-e288-4d0e-a396-3b9333fdbc17.png">


- Using K-means to cluster Cryptocurrencies
Created an elbow curve using hvPlot which resulted in finding the best value of K from Principal Component dataframe. Once completd, I predicted the K clusters for the cryptocurrency data my running it through the K-means algorithm. 

<img width="1085" alt="Screen Shot 2021-07-26 at 1 50 35 PM" src="https://user-images.githubusercontent.com/78401776/127035982-0a627ca4-873e-4dcb-a675-c93de5736f8a.png">


- Visualization of Cryptocurrency results
Using the clustered dataframe, developed a 3D scatter plot using Plotly Express to plot clusters. 

<img width="864" alt="Screen Shot 2021-07-24 at 9 42 32 PM" src="https://user-images.githubusercontent.com/78401776/127037486-ef83cf68-4c67-46be-a175-9cb6ea121359.png">


The second visualization was a scatter plot with Plotly Express and hvplot. The visualization shows distinct groups that align with the three PCA. 

<img width="793" alt="Screen Shot 2021-07-24 at 9 42 39 PM" src="https://user-images.githubusercontent.com/78401776/127037726-5dbdbc69-6bfb-4525-8fb5-0135e4d722bb.png">









