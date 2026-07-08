# MS Computer Science Projects

A collection of graduate coursework projects spanning cloud computing, machine learning, and data science, completed from 2018 to 2021 as part of my M.S. in Computer Science (University of Illinois Urbana-Champaign) and UCLA Extension data science coursework.

## Projects

### [CS598 Capstone Project - Task 1: Batch Processing Big Data in AWS](<CS598 Capstone Project- Task 1- 6.29.2020vFinal.pdf>)
Designed and built a batch-processing pipeline on AWS to query a 20+ GB historical airline dataset. Moved raw data from an EBS snapshot into S3, then used AWS Athena for large-scale batch querying, following a Lambda-style architecture based on AWS's published big data reference designs.

### [CS598 Capstone Project - Task 2: Stream Processing Big Data in AWS](<CS598 Capstone Project- Task 2-7.24.2020vFinal.pdf>)
Extended the Task 1 pipeline to a real-time streaming architecture using AWS Managed Streaming for Kafka (MSK) and Spark Structured Streaming (PySpark) in AWS Glue. Compares the tradeoffs of stream vs. batch processing for the same dataset, concluding batch was the better fit for this historical (non-live) data given its lower operational complexity.

### [Machine Learning Using R: Predicting BMI Status](<Final Project-UCLA Machine Learning- Christopher Johnson Laurence Giglio 9.7.18 Final.pdf>)
Built and compared four classification models (logistic regression, classification tree, KNN, SVM) in R on NHANES health survey data to predict whether a patient is overweight/obese. KNN achieved the highest test accuracy (using all 18 variables), but logistic regression (8 variables, 75.1% test accuracy) was recommended as the best overall model for its balance of accuracy, interpretability, and speed. Co-authored with Laurence Giglio.

### [Diabetes in the US: Education and Preventative Measures](<Intro to Data Science- Final Project- Chris Johnson 8.19.18F.pdf>)
Data science analysis identifying which U.S. metro areas (MSAs) have the highest concentrations of at-risk, undiagnosed diabetes/prediabetes patients, aimed at targeting preventative education campaigns given that 90%+ of Type II diabetes is preventable.

### [Streamlining Healthcare Data Distribution with Tableau & Cloud Storage](<UCLAx EDA & Visualization- Final Project 10.21.18v1.pdf>)
Proposed a cloud storage + Tableau dashboarding solution to improve how healthcare organizations distribute complex medical billing/revenue data across teams (Operations, RCM, Accounting) with varying levels of analytics skill, drawn from real-world experience in M&A at Radiology Partners.

### [Data Science in the UFC](<UFC Data Science Presentation 6.10.18v1.pdf>)
Python (Pandas/Matplotlib) analysis of 3,000+ UFC fights (UFC 1 through UFC 195, spanning ~1993-2016) scraped from Sherdog.com, exploring the most effective fighting tactics, how top athletes compare, and historical trends across two decades of the sport.

---
*These projects were completed for academic coursework and are shared here as a portfolio reference.*
