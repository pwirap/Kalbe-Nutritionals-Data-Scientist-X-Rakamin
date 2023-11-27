# Exploratory Data Analysis

## Total Quantity from Month to Month

![image](https://github.com/pwirap/Kalbe-Nutritionals-Data-Scientist-X-Rakamin/assets/99533745/829a2779-40a0-41b3-bf89-4225e8c164c3)

1. When viewed as a whole over each month, there are no significant increases or decreases in Quantity.
2. The highest Quantity of sales was recorded in March.
3. The lowest Quantity of sales was recorded in February

##  Total Amount from Day to Day

![image](https://github.com/pwirap/Kalbe-Nutritionals-Data-Scientist-X-Rakamin/assets/99533745/ee001126-66f7-433c-8cde-da96728f6f4c)

1. There was a decrease in the Total Amount on the last date
2. The highest total was on the 1st
3. And the lowest total number was on the 31st

## Sales Quantity by Product

![image](https://github.com/pwirap/Kalbe-Nutritionals-Data-Scientist-X-Rakamin/assets/99533745/9d91a74c-9524-423b-b7da-d8acc24783bf)

1. The following is a table of Sales Quantity for each product.
2. It is evident that the highest total is in Thai Tea, with a total of 2,853.
3. The lowest total is for Cashew, with 627

## Total Sales Amount by Store Name

![image](https://github.com/pwirap/Kalbe-Nutritionals-Data-Scientist-X-Rakamin/assets/99533745/cb168924-7f0b-489f-acf5-643ddfb3c065)

1. The following is a graph displaying the total sales amount for each store name.
2. It is apparent that there isn't a significant difference in the total sales amount among the various store names.
3. However, the lowest is Buana Indah with a total of 10.63 million, while the highest is Lingga with a total of 13.11 million

# Machine Learning Reggresion (Time Series) using ARIMA

![image](https://github.com/pwirap/Kalbe-Nutritionals-Data-Scientist-X-Rakamin/assets/99533745/99a2c9bf-d3a6-4aac-8196-fe584fe7c4f7)

![image](https://github.com/pwirap/Kalbe-Nutritionals-Data-Scientist-X-Rakamin/assets/99533745/72d4f044-b67d-4d59-9c80-1295324a1b91)

By using the ARIMA method for time series, predictions can be made on a time series. After hyperparameter tuning according to the table above, it is almost close to the actual value, but the prediction is not 100 percent close to the correct result, this is done to prevent overfitting.

# Machine Learning Clustering

## Elbow Method 

![image](https://github.com/pwirap/Kalbe-Nutritionals-Data-Scientist-X-Rakamin/assets/99533745/756af133-9f51-4bb3-8770-1194e8ee41af)

To find the most optimal cluster in machine learning clustering, the elbow method can be used to find out the most optimal total clusters, where to look for broken points. From this search it can be seen that the largest clusters are in 3 clusters

## Silhouette score

![image](https://github.com/pwirap/Kalbe-Nutritionals-Data-Scientist-X-Rakamin/assets/99533745/b239d69e-c534-4590-9e2c-1c9e2581bf84)

from Silhouette score it can also be seen that cluster 3 has the most optimal value, then cluster 3 is the most optimal

## 3-D Visualization

![image](https://github.com/pwirap/Kalbe-Nutritionals-Data-Scientist-X-Rakamin/assets/99533745/1d45d704-b699-495c-a4c8-4135a42ba494)

![image](https://github.com/pwirap/Kalbe-Nutritionals-Data-Scientist-X-Rakamin/assets/99533745/987408c1-490d-4647-a428-725390aa8e41)

1. Cluster 1 represents customers with the lowest total count, characterized by average transaction values, average purchased quantity, and the lowest total amount compared to the other clusters.
2. Cluster 2 represents customers with a moderate total count, but they exhibit characteristics of higher average transaction values, average purchased quantity, and the highest total amount compared to the other clusters.
3. Cluster 0 is the largest cluster in terms of customer count.
