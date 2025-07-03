INTRODUCTION

This project studies the growing risk of developing thyroid-based cancers. The problem that this dataset handles is classifying individuals based on their risk level of developing this type of cancer, which is based on numerous background, health, and lifestyle factors. This classification problem categorizes individuals into three risk groups: high, medium, and low. This project is beneficial as it can help with better prediction and provide more information on early detection of thyroid cancer developing. 

The main questions that this project answers some of the following:​
1. How can we accurately classify individuals into certain categories?
2. What types of factors mainly lead to an increase in risk of developing thyroid cancer?
​
DATA SUMMARY

Thyroid-based cancer is a growing concern throughout the world and the thyroid risk cancer dataset delves into several factors that affect one’s likelihood of developing such cancers. Specifically, the dataset analyzes demographic facts, clinical history, lifestyle factors, and key thyroid hormone degrees to assess the probability of thyroid cancers. 

The dataset includes 212,691 statistics related to risk factors regarding thyroid cancer. There are 17 column descriptions that delve into different demographics, such as patient IDs, their age, ethnicity, gender, smoking or other lifestyle habits, diseases of the patients, and more.  
​
Though there are 16 columns of factors that can potentially have an impact on the risk levels of developing this cancer, this project particularly focuses on the effects of smoking, exposure to radiation, and family history. 
​
PRE-PROCESSING DATA

To pre-process my data, I first check for missing values for me to handle before creating visualizations. Upon checking for this, I find that there are
no missing values as there are valid entries for each of the 17 columns. 

In addition, I also checked for duplicates in the dataset by using the code line “data.duplicated().sum().” Upon running that code, the result
showed 0, meaning that there were no duplicates in the set. 

As there were no missing values or duplicates found, the data was good to go and I started on my data visualizations.

DATA VISUALIZATIONS

The first visualization used is a pie chart that explores the overall percentage of people from the 212,691 statistics collected in each of the risk categories. As evidenced in the graph, the low-risk category has the highest percentage of risk distribution, followed by the medium-risk and high-risk having the same percentage.

The first visualization is a bar graph that explores the amount of people in low, medium, or high risk levels, depending on their indulgence in smoking. As evidenced in the graph, amongst the people who do smoke, more classified as medium risk or high risk, instead of low risk. On the contrary, amongst nonsmokers, majority of the people were in the low-risk category in comparison to medium-level or high level risk. 

The second bar graph that explores the amount of people in low, medium, or high risk levels, depending on radiation exposure. As evidenced in the graph, amongst the people who experience more radiation exposure, there is an equal amount of people in both high and low risk categories, which are both singiciantly more than the people in the medium risk category. Amongst the population who do not face as much radiation exposure, there is an equal amount of people in both low and medium risk categories, which are both singiciantly more than the people in the high risk category. 

The third bar graph that explores the amount of people in low, medium, or high risk levels, depending on their family history of possessing this cancer type. As evidenced in the graph, amongst the people do have this family history, there are more people in the low risk category, with a slightly smaller amount people in the high risk category, with no individuals in medium risk category. However, amongst the people that do not have such a history, the highest number of people in the medium risk category, while high and low risk categories have significantly lower, but equal, counts of people. 

MODELING


​
​
