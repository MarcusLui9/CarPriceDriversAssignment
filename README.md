# What drives the price of a car?
GitHub Repository for work done for Professional Certificate in Machine Learning and Artificial Intelligence: 2025

### OVERVIEW 
In this application, you will explore a dataset from Kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing.  Your goal is to understand what factors make a car more or less expensive.  As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car.

### CRISP-DM Framework
To frame the task, throughout our practical applications, we will refer back to a standard process in industry for data projects called CRISP-DM.  This process provides a framework for working through a data problem.  Your first step in this application will be to read through a brief overview of CRISP-DM [here](https://mo-pcco.s3.us-east-1.amazonaws.com/BH-PCMLAI/module_11/readings_starter.zip).  After reading the overview, answer the questions below.

### Business Understanding
From a business perspective, we are tasked with identifying key drivers for used car prices.  In the CRISP-DM overview, we are asked to convert this business framing to a data problem definition.  Using a few sentences, reframe the task as a data task with the appropriate technical vocabulary. 

### Understand the Data
Upon first inspection of the data, we can tell that there are 426880 rows of data, many of which are littered with null values. The data provides information about car prices based on the model, condition, type, size, color, and several more features. 

### Prepare the Data
Some values were also unrealistic. These would be considered extreme outliers and must be removed. Null values must also be filled in with either correlative data or the most common option available. Some columns, such as ID, VIN, and region, may be dropped completely due to their unique value or due to its insignificance in a sale.

### Interpreting the Data 
