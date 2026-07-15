# Logistics-Analytics-Project
Analysis of the publically-available DataCo dataset, comprised of supply chain records of multiple companies using PowerBI and MS-Excel to demonstrate the use of KPIs and data transformation. It contains several important features describing the process of shipping products such as: Delivery Date, Product Category, Delivery and shipping locations, etc.

***

# Raw Data
Contains the raw datasets from : https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis. (We have used the DataCoSupplyChainDataset.csv for our analysis, other two datasets are just descriptive of the columns in the main dataset.)

***

# Excel (Data Prep)
We have transformed the DataCoSupplyChainDataset.csv to add a lookup table for selected products to enable us to use LookUp commands to engineer a feature for assigning the Handliing instructions for various categories of products. Also delay and lead time functions were engineered as well.

***

# Power BI
Visualization of the transformed data from excel to create a dashboard featuring the KPIs, KPIs used:
  1. Average delay (sum of delays across all orders/no. of orders)
  2. Average lead time (sum of delivery days across all order/ no. of orders)
  3. High Risk Deliveries (no. of high-risk (prone damage during shipping) deliveries)

Visualizations in the dashboard:
  1. Bar Graph (showing the average delay across various delivery types (according to handling instructions))
  2. Donut Chart (showing the distribution of deliveries according to the risk level (high-risk vs standard))

Apart from this sliders have are also present to further highlight deliveries using a specific shipping mode and delivery status.

  Below is a screenshot of the Dashboard:
[<img width="1122" height="633" alt="image" src="https://github.com/user-attachments/assets/06283396-d43c-4949-af53-eee6bfa3e99c" />
](https://github.com/neutraleccentric/Logistics-Analytics-Project)
