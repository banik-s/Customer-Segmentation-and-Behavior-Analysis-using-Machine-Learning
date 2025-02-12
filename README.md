# Customer-segmentation-and-consumer-behavior-analysis

(Please click on the Consumer buying behavior - Paul.ipynb above to see the detailed application of analytics and its interpretation)

Brief Snapshot: 

Topic # 1:

Segmenting consumer based buying behavior and applying 80/20 rule to identify top customers/products/geographic locations driving 80% of total $ sales

This is a real sales data set of a UK based retailer

Objective: Segment customers based on buying behavior by applying k-means clustering algorithm to calculate the optimal number of customer segments with similar buying habits (features).

Data Source: https://archive.ics.uci.edu/ml/datasets/Wholesale+customers


Topic 2:

Apply 80/20 rule to identify the top 20% 

1) Customer segments 

2) Products and

3) Geographic locations

resulting in 80% of $ sales revenue.

Data Source used: https://archive.ics.uci.edu/ml/datasets/online+retail

## Customer segments based on buying behavior by applying k means clustering (unsupervised learning) algorithm :

### Elbow method to choose the optimal number of customer segments (clusters):

![image](https://github.com/banik-s/Customer-Segmentation-and-Behavior-Analysis-using-Machine-Learning/blob/main/Images/2.png)


### Customer segments:

![image](https://github.com/banik-s/Customer-Segmentation-and-Behavior-Analysis-using-Machine-Learning/blob/main/Images/1.png)


## Distribution of customers in the 3 (optimal # of) clusters:

![image](https://github.com/banik-s/Customer-Segmentation-and-Behavior-Analysis-using-Machine-Learning/blob/main/Images/3.png)


### Analysis:
There are some overlap between segment No. 3 with each of Segment No. 1 & 2 at the boundaries which we need to keep in mind while analyzing customers.

The k-means clustering algorithm being a un-supervised learning algorithm, we can perform a quick visual check on the model's performance based on the visualization chart.

Business Strategy:
Customer segment # 1 & 2 have opportunities for growth and future expansion. As the retails industry is a saturated industry, hence customer segment # 3 may already be dominated by other retailers so our client can try to increaese sales in the 2 other cutomer segments (# 1 & 2) through suitable competitive positioning, pricing stratgey, cohesive sales & marketing efforts, promotions, bundling etc.


### Buying behavior of customers within each cluster:

![image](https://github.com/banik-s/Customer-Segmentation-and-Behavior-Analysis-using-Machine-Learning/blob/main/Images/4.png)

![image](https://github.com/banik-s/Customer-Segmentation-and-Behavior-Analysis-using-Machine-Learning/blob/main/Images/5.png)

### Analysis:

For all 3 customer segments: majority of customers are from Region 3. So Region is not a key factor to segment customers.

Fresh: Segment # 2 makes significant purchases compared to other segments folloewed by Segment # 3

Milk: Segment # 1 makes significant purchases compared to other segments

Grocery: Segnment # 1 makes significant purchases compared to other segments

Frozen: Segment # 2 makes significant purchases followed by Segment # 3

Detergent_Paper: Segment # 1 is a major purchaser

Delicassen: Segnment # 2 on average makes most purchases, followed by Segmnet # 1


## Snapshots of few Analysis: 
(Detailed analysis shown in Consumer buying behavior - Paul.ipynb file)

### Customers:

1084 out of total 3877, top 25% of customer segments result in 79% of total $ sales amount.

![image](https://github.com/banik-s/Customer-Segmentation-and-Behavior-Analysis-using-Machine-Learning/blob/main/Images/6.png)


### Products:

775 out of total 3877, top 20% of products result in 79% of total $ sales amount.

![image](https://github.com/banik-s/Customer-Segmentation-and-Behavior-Analysis-using-Machine-Learning/blob/main/Images/7.png)


### Geographic Locations: Top 10 countries by revenue

![image](https://github.com/banik-s/Customer-Segmentation-and-Behavior-Analysis-using-Machine-Learning/blob/main/Images/8.png)

### Geographic Locations: Bottom 20 countries by revenue

![image](https://github.com/banik-s/Customer-Segmentation-and-Behavior-Analysis-using-Machine-Learning/blob/main/Images/9.png)

### Analysis:
UK alone results in 82% of total $ revenue which is expected for a UK based retailer.

### Business Strategy:
The senior management for the retail company should consider expanding to the other countries (after UK) where they have significant sales such as Neatherland, EIRE, Germany & France for future geographic expansion.
