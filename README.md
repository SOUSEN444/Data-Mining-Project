Introduction
This project studies the growing risk of developing thyroid-based cancers. The problem that this dataset handles is classifying individuals based on their risk level of developing this type of cancer, which is based on numerous background, health, and lifestyle factors. This classification problem categorizes individuals into three risk groups: high, medium, and low. This project is beneficial as it can help with better prediction and provide more information on early detection of thyroid cancer developing. 

The main questions that this project answers some of the following:​
1. How can we accurately classify individuals into certain categories?
2. What types of factors mainly lead to an increase in risk of developing thyroid cancer?
​
Data Summary
Thyroid-based cancer is a growing concern throughout the world and the thyroid risk cancer dataset delves into several factors that affect one’s likelihood of developing such cancers. Specifically, the dataset analyzes demographic facts, clinical history, lifestyle factors, and key thyroid hormone degrees to assess the probability of thyroid cancers. 

The dataset includes 212,691 statistics related to risk factors regarding thyroid cancer. There are 17 column descriptions that delve into different demographics, such as patient IDs, their age, ethnicity, gender, smoking or other lifestyle habits, diseases of the patients, and more.  
​
Though there are 16 columns of factors that can potentially have an impact on the risk levels of developing this cancer, this project particularly focuses on the effects of smoking, exposure to radiation, and family history. 
​
Pre-processing data
To pre-process my data, I first check for missing values for me to handle
before creating visualizations. Upon checking for this, I find that there are
no missing values as there are valid entries for each of the 17 columns. 

In addition, I also checked for duplicates in the dataset by using the
code line “data.duplicated().sum().” Upon running that code, the result
showed 0, meaning that there were no duplicates in the set. 

As there were no missing values or duplicates found, the data was
good to go and I started on my data visualizations.
​
​
