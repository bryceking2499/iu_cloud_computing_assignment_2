# iu_cloud_computing_assignment_2
Cloud Computing Assignment 2

This README contains information about Assignment 2 for Engineering Cloud Computing at IU taught by Professor Dingwen Tao.

The purpose of this assignment is to use Apache Spark (PySpark by Extension) to analyze two different data sets.

I was unable to setup a Spark multi node cluster on my local machine (attempted multiple times without success) so I utilized Databricks in conjunction with an S3 bucket from AWS.

For Problems 1 (A-D) and Problem 2 (A) I utilized PySpark (Databricks builtin) along with pyspark SQL libraries to analyze the necessary conditions to answer the following questions

I was unable to complete Problems 1E (KMEANS) and 2B (Comfortable Zone)

1A: When are tickets most likely to be issued?
  Based on counts, it would appear that tickets are issued most at hours 21, 20, and 23.

1B: What are the most common years and types of cars to be tickets?
1B (Part 1):
  Based on counts, it would appear that tickets are issued most to 0 (unidentified year) 2021, and 
  2019 vehicles

1B (Part 2):
  Based on counts, it would appear that tickets are issued most to Honda, Toyota, and Ford vehicles

1C Where are tickets most commonly issued?:
  Based on counts, it would appear that tickets are issued most at vehicle location null (unidentified), 19, and 13

1D Which color of the vehicle is most likely to get a ticket?
  Based on counts, it would appear that tickets are issued most to GY, WH, and BK vehicles

1E KMEANS Clustering (Unable to Complete)

2A For each pair of players (A,B) we define the fear score of A when facing B as the hit rate, such that B is the closest defender when A is shooting. Based on the fear score, for each player, please find out who is his "most unwanted defender":

  See IPYNB
