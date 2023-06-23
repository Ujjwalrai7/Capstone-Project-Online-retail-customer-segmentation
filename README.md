# Capstone-Project-Online-retail-customer-segmentation

# **Project Summary -**
The purpose of this project was to conduct a comprehensive customer segmentation analysis for an online retail company. The company, an established e-commerce platform, wanted to gain a deeper understanding of its customer base and identify distinct customer segments based on their behaviors, preferences, and characteristics. By segmenting customers, the company aimed to personalize marketing efforts, improve customer targeting, and enhance overall customer experience.

The project followed a data-driven approach, utilizing advanced analytical techniques to segment customers. The methodology consisted of the following steps:

Data Preprocessing: The collected data underwent preprocessing steps to ensure data quality and consistency. This involved cleaning the data, handling missing values, and transforming variables into suitable formats for analysis.

Exploratory Data Analysis: An in-depth exploration of the data was conducted to gain insights into customer behavior and identify patterns. Descriptive statistics, visualizations, and correlation analysis were employed to uncover key trends and relationships within the data.

Feature Engineering: To enhance the effectiveness of segmentation, additional features were derived from the existing data. These features were designed to capture specific aspects of customer behavior, such as recency of purchase, frequency of interaction, and monetary value.

Segmentation Analysis: Advanced clustering techniques, such as K-means clustering, hierarchical clustering, or Binning models, were applied to segment customers into distinct groups based on their similarities and differences. The appropriate number of segments was determined by evaluating different clustering solutions and selecting the one that provided the most meaningful and actionable insights.

Segment Profiling: Each customer segment was carefully profiled and characterized based on their unique attributes. This involved analyzing the key features and behaviors that differentiated one segment from another. The profiles provided a deep understanding of customer preferences, motivations, and needs within each segment.


### Variables Description

* ### **InvoiceNo**: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* ### **StockCode**: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* ### **Description**: Product (item) name. Nominal.
* ### **Quantity**: The quantities of each product (item) per transaction. Numeric.
* ### **InvoiceDate**: Invoice Date and time. Numeric, the day and time when each transaction was generated.
* ### **UnitPrice**: Unit price. Numeric, Product price per unit in sterling.
* ### **CustomerID**: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* ### **Country**: Country name. Nominal, the name of the country where each customer resides.


## . Data Vizualization

![image](https://github.com/Ujjwalrai7/Capstone-Project-Online-retail-customer-segmentation/assets/125723652/76c07a59-8388-4d9a-b3cc-c9dd7a7ef699)
 Visualizing top 10 countries based on total invoices
 
 United Kingdom is making most of the purchases as compared to other countries

 ![image](https://github.com/Ujjwalrai7/Capstone-Project-Online-retail-customer-segmentation/assets/125723652/b6537c7d-2a85-4a93-9073-53be08ec0f68)
 Most of the customers have purchased the items in Thursday ,Wednesday and Tuesday also it can be said that as there is no data for saturday the store might be closed on saturday

 ![image](https://github.com/Ujjwalrai7/Capstone-Project-Online-retail-customer-segmentation/assets/125723652/fbf8cb62-0b9b-459f-a377-4bd74347b67e)

 * Most numbers of customers have purchased the gifts in the month of November,December October and  September

* less numbers of customers have purchased the gifts in the month of April ,January and February

![image](https://github.com/Ujjwalrai7/Capstone-Project-Online-retail-customer-segmentation/assets/125723652/0211cfb6-0af7-4c02-afde-9727160f158f)
From this graph we can see that from 11:00 am to 4:00 pm most of the customers have purchased the item.



***RFM (Recency, Frequency, Monetary) modeling is a statistical technique used in marketing and customer relationship management to analyze customer behavior and determine the value of each customer to a business. It involves analyzing the transactional data of customers and grouping them based on their buying behavior.***

![image](https://github.com/Ujjwalrai7/Capstone-Project-Online-retail-customer-segmentation/assets/125723652/c031d365-b9cc-422d-9561-76e3c126ab13)
For n_clusters = 2 The average silhouette_score is : 0.39469123089738556 which is the highest.

![image](https://github.com/Ujjwalrai7/Capstone-Project-Online-retail-customer-segmentation/assets/125723652/bb829eae-6b74-4958-889b-a76a3e970896)
## From the above elbow curve we can see that optimal no of clusters would be 2 ##

![image](https://github.com/Ujjwalrai7/Capstone-Project-Online-retail-customer-segmentation/assets/125723652/59b9eb04-f6a9-47d4-a382-259be80cee2f)
![image](https://github.com/Ujjwalrai7/Capstone-Project-Online-retail-customer-segmentation/assets/125723652/78c29ee6-7f9e-4699-b6ba-b768b97f1258)


## Summary 

![image](https://github.com/Ujjwalrai7/Capstone-Project-Online-retail-customer-segmentation/assets/125723652/2e56a4f4-3197-4f62-9b2d-f7709faaff38)

**Algorithm**

* RFM (Recency, Frequency, and Monetary) dataframe helps in solving problems in a particular order, making it easy to recommend and display new products to selected customers.

* Different clustering algorithms were applied to the dataset, including: Clustering on Recency, Frequency & Monetary (RFM) with 2 clusters.

1. K-Means with Silhouette_score
2. K-Means with Elbow Method
3. Hierarchical Clustering
4. DBSCAN





 



