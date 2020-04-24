# Python

Data: 

The data consists of aggregated trip logging metrics from commercial vehicles, 
such as semi-trucks. The data have been grouped by intersection, month, hour of day, 
direction driven through the intersection, and whether the day was on a weekend or not.

The data consists of the 20th, 50th, and 80th percentiles for the total time stopped at an intersection 
and the distance between the intersection and the first place a vehicle stopped while waiting




1) What is the question you want to ask?

- Predict congestion time from the dataset that includes aggregate stopped vehicle information and intersection wait times
- How does this differ from a weekday to weekend - Done
- Also, how does the wait time differ in Peak and lean hours? - Done
- Top 50/100 traffic junctions/intersections - Pending


2) How do you plan on using data to answer that question?

- Explore data that I have by typical EDA( Exploratory data Analysis Steps)
- The data is grouped at month,intersection, hour of the day, direction driven through the intersection, a weekend or not
- Planning to cluster the data to see if there is a way to summarize the distribution of wait times and stop distances at each intersection
- 'Total time stopped' and 'Distance to first stop' are the vital metrics which would help me understand the above question 

3) How are you going to get that data?

- Kaggle Data Set


4) What analysis are you planning to perform on it?

- Exploratory data Analysis
- K-Means Clustering 
- Understanding Wait times via heat Maps
- City wise Top Wait time junctions/intersections at Morning Peak and Evening Peak hours (To make sure that commuters in that city know how long it takes to wait at a juction)


5) How are you going to present your results?

- Jupyter Notebook 
- Heatmaps
- Matplotlib and Seaborn utilization
- Graphs showcasing the patterns - clusters 
- predict and minimize the RMSE from the model 
