Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus, and user reviews of restaurants, and also has food delivery options from partner restaurants in select cities.

India is quite famous for its diverse multi-cuisine available in a large number of restaurants and hotel resorts, which is reminiscent of unity in diversity. The restaurant business in India is always evolving. More Indians are warming up to the idea of eating restaurant food whether by dining outside or getting food delivered. The growing number of restaurants in every state of India has been a motivation to inspect the data to get some insights, interesting facts, and figures about the Indian food industry in each city. So, this project focuses on analyzing the Zomato restaurant data for each city in India.

The Project focuses on Customers and Companies, you have to analyze the sentiments of the reviews given by the customer in the data and make some useful conclusions in the form of Visualizations. Also, cluster the Zomato restaurants into different segments. The data is visualized as it becomes easy to analyze data in an instant. The Analysis also solves some of the business cases that can directly help the customers find the Best restaurant in their locality and for the company to grow and work in the fields they are currently lagging in.

This could help in clustering the restaurants into segments. Also, the data has valuable information about cuisine and costing which can be used in cost vs. benefit analysis

Data could be used for sentiment analysis. Also, the metadata of reviewers can be used for identifying the critics in the industry.

There are two datasets provided 1st one has information about the restaurant and 2nd one Review of the restaurant.



# Zomato_Restaurant_Analysis

**Restaurant DataSet**

There are 105 total observations with 6 different Variables/features.

The Collection Variable has a high volume of null values present and timing also has null values.

There is no duplicate value present in the restaurant dataset.

The cost feature represent the amount but it shows the object type because it is separated by ',' comma

Timing represents operational hour but as it is represented in the form of text has an object data type.

**Review DataSet**

There are a total of 10000 observations and 7 Variables/features.

Only the picture and restaurant features do not have null values.

There are a total of 36 duplicate values present in the review dataset

Rating represents ordinal data, has object data type should be integer.

Timing represents the time when the review was posted but shows object data time, it should be converted into date time.
