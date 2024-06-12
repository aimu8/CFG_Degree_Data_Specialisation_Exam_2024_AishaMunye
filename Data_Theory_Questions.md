### 1.1 In your own words, what does the role of a data scientist involve?
A data scientist's job involves gathering, organizing, and analyzing large sets of data to find patterns and insights. They use statistics and machine learning to create models that predict outcomes and automate tasks. They also communicate their findings through visualizations and reports to help make data-driven decisions.

### 1.2 What is an outlier? 
**a. Definition**: An outlier is a data point that is significantly different from other data points in a dataset. It can be due to variability or an error.

**b. Examples**: 
   - In a dataset recording the ages of patients, the age 187 is an outlier.
   - In a dataset where daily water consumption is recorded between 2-4 liters a day, 14 liters would be an outlier.

**c. Should outliers always be removed? Why?**: 
Outliers shouldn't always be removed. It depends on why they're there. If it's an error, it might be good to remove it. But if it shows something important, like a rare event or fraud, it should stay as this uncovers insights.Outliers can be very informative about the subject-area and data collection process. 

**d. Other possible issues in a dataset**: 
   - Missing data
   - Duplicate records
   - Inconsistent data formats, for example, writing "40" as "forty" in a dataset of integers.
   - Incorrect data entries

### 1.3 Describe the concepts of data cleaning and data quality.
**a. What is data cleaning?**: Data cleaning involves fixing errors and inconsistencies in a dataset, like handling missing values, removing duplicates, and correcting incorrect information.

**b. Why is data cleaning important?**: 
It's important because clean data leads to accurate analyses and reliable results. It helps ensure that the insights and decisions based on the data are correct.

**c. Common mistakes in datasets**: 
   - Missing values
   - Duplicate entries
   - Inconsistent formatting (like dates)
   - Typographical errors
   - Misleading data points

### 1.4 Discuss what is Unsupervised Learning - Clustering in Machine Learning using an example.

**a. Definition**: 
Unsupervised learning is a type of machine learning where models learn from data without labeled outcomes. Clustering is a technique within unsupervised learning that groups data points based on their similarities. This method, known as cluster analysis, helps identify natural groupings within data without predefined categories or target variables.

**b. When is it used?**: 
Clustering is useful when we want to discover natural groupings within a dataset. It's often applied in scenarios like customer segmentation, where businesses want to categorize customers based on their buying behavior, or in anomaly detection, where finding outliers is important.

**c. Real-world application**:
For instance, a retail business can use clustering to analyze customer buying habits. By grouping customers with similar purchasing patterns, the business can create targeted marketing strategies for each group. This approach allows for personalized promotions and advertisements, enhancing customer engagement and potentially boosting sales.

**d. Main limitations**: 
   - Deciding the number of clusters can be hard.
   - Clustering can be sensitive to initial settings and outliers.
   - Results can be tough to interpret and verify.

### 1.5 Supervised Learning - Classification in Machine Learning

**a. Definition**:

Supervised learning is when we teach a model using data that already has labels. In classification, a type of supervised learning, we sort data into specific categories based on their characteristics. The goal is to build a model that can correctly label new data it hasn't seen before.

**b. When is it used?**:

Classification is used when we want to predict a specific category. Examples include deciding if an email is spam, diagnosing diseases, or predicting if a customer will leave a service.

**c.What is a possible real-world application of supervised learning?**:

A real-world example is in healthcare, where classification models can predict if a patient has a particular disease based on their symptoms and medical history. This helps doctors catch diseases early and provide timely treatment.

**d. What data do we need for it? Is there any processing that needs to be done?**:

- **Data**: We need labeled data, meaning each data point comes with a label. For instance, patient records might include whether or not they have a disease.
- **Processing**: Before training the model, we need to prepare the data. This involves normalizing it to ensure everything is on the same scale, extracting the important features, and handling any missing information to ensure the data is complete and usable.

By preparing and using the data correctly, we can train a classification model to make accurate predictions, which is useful in areas like healthcare, email filtering, and customer retention.
