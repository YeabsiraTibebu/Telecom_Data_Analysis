# TellCo_Data_Analysis

**Requirement for Completing this task**

**Task-1:
Overview of the user's behavior on those applications:**
  1. Aggregate per-user information in the column
      Number of xDR(data sessions Detail Record), 
      Session duration, 
      Total download and upload data,
      Total data volume (in Bytes) during the session for each application.
  2. Conduct an EDA on those data and communicate useful insights.

**Task-2:
Tracking the user's engagement using the following engagement metrics:**
  1. Session's frequency, duration, and total traffic.
  2. Aggregate and report the metric per customer ID (MSISDN).
  3. Normalize each engagement metric and run a K-means(k=3) to classify customers in three groups of engagement.
  4. Compute minimum, maximum, average & total non-normalized metrics for each cluster.
  5. Plot the top 3 most used applications using appropriate charts.

**Task-3:
This section focuses on network parameters like TCP retransmission, Round Trip Time (RTT), Throughput, and the customers’ device characteristics like the handset type to conduct a deep user experience analysis.**
  1. Aggregate, per customer average TCP retransmission, RTT, throughput, and       Handset type
  2. Compute & list 10 of the top, bottom, and most frequent TCP values, RTT values, and Throughput values in the dataset.
  3. Compute & report the distribution of the average throughput, and average TCP retransmission view per handset type and provide interpretation.
  4. Using the experience metrics above, perform a k-means clustering (where k = 3) to segment users into groups of experiences and provide a brief description of each cluster.

**Task-4:
This section is to analyze customer satisfaction in depth. assuming that the satisfaction of a user is dependent on user engagement and experience.**
  1. Write a Python program to assign an engagement score to each user. Consider the engagement score as the Euclidean distance between the user data point & the less engaged cluster.
  2. Experience score for each user. Consider the experience score as the Euclidean distance between the user data point & the worst experience cluster.
  3. Consider the average of both engagement & experience scores as  the satisfaction score & report the top 10 satisfied customers.
  4. Build a regression model of your choice to predict the satisfaction score of a customer.
  5. Run a k-means (k=2) on the engagement & the experience score.









