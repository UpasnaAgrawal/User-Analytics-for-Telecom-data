TELECOM DATA ANALYSIS
The dataaset consists of 150,000 records with 55 features detailing user interactions and metrics
used : NumPy for numerical operations and Pandas for data manipulation.
Data is divided into - User Overview Analysis, User Engagement Analysis ,User Experience Analysisand User Satisfaction Analysis.
We have Identify the Top 10 Handsets Used by Customers and Identify the Top 3 Handset Manufacturers.and Identify the Top 5 Handsets per Top 3 Handset Manufacturer.
In  USER OVERVIEW ANALYSIS there are Different applications ( Social Media, Google, YouTube) contribute to total data usage-Gaming Consumes the most data, accounting for approximately 61.56 GB. email and social media have a relatively minor impact on overall data consumption
We have taken Cluster -Cluster sizes were Cluster 0 Contains around 30,000 customers . Cluster 1 Is the smallest group, with fewer than 5,000 customers . Cluster 2: Is the largest group, with over 40,000 customers.
In EXPERIENCE ANALYTICS Normalize each experience metric and run k-means clustering (k=3) to classify customers.After the normalized value come between 0 and 1  We Perform k-means clustering (k=3) based on experience metrics.
We have  find top 10 satisfied customers on Engagement Metric by using top_10_satisfied_customers=engagement_metrics.nlargest(10,'Engagement_Score')top_10_satisfied_customers
In User Behavior Insights: The analysis also sheds light on user behavior concerning data limits and application usage.
The analysis of the telecom dataset provides valuable insights into user behavior, device preferences, and performance metrics that can inform strategic decisions for telecom service providers to enhance customer satisfaction and optimize service delivery.



