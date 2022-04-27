# Data-Science-Professions-Survey-Analysis

This project originated from an open data scientist comptition on Kaggle in 2020 titled "Kaggle ML & DS Survey Challenge". The purpose of this challenge was to "tell a data story about a subset of the data science community reprenstetd in this survey, through a combination of both narrative and data exploration." 

The first part of the project is to perform data cleaning and exploratory analysis to identify patterns that could be leveraged to provide more insights.

In the first part of the project, data cleaning and exploratory data analysis is performed to summarize the dataset's main characteristics. More specfically, gender, education leve, salary, and age are analyzed in detail and corresponding figures are presented.

The difference between average salary of men and women is analyzed. More specifically, the distribution of the two groups are visualized and the homogeneity of the variance between the two groups is anaylzed using Levene test. Finally, bootstrapping is used to compare the mean of salary of these two groups.

The difference between average salary of different levels of education (Bachelor's degree, Master's degree, Doctoral degree) is analyzed. Following the same apporach, the distribution of the two groups are visualized and the homogeneity of the variance between the two groups is anaylzed using Levene test. Once deemed ANOVA is not suitable for these three groups, Kruskal-Wallis h-test and Welch's ANOVA test is performed to provide more insights into whether there is a difference in the salary mean among the three groups.

The second part of the project is to build an ordinal logistic regression model to classify the survey respondents' annual salary bucket.

Prior to building the model, data exploration and cleaning is performed, followed by feature selection. Then a ordinal logistic regression model is built from scratch and trained on a subset of the survey responses. Cross-validation is used to perform model tuning. Finally, the optimal set of parameters is chosen to be used on the test set.
