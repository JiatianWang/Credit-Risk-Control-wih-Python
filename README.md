# Credit-Risk-Control-wih-Python
My purpose is to control the financial risk, minimize the risk of losing money while lending to customers. Also, I automate the loan eligibility process based on the customer detail provided.

The dataset has over 600 observations. The independent variables include ID number, customer gender, marital status, applicant income, loan amount, loan term, credit history, and so on. The target dependent variable is the loan approved status with yes or no.

![data](https://user-images.githubusercontent.com/32876600/107391770-06336600-6ac7-11eb-8444-f18f0f3dfdf8.JPG)

The dataset is not clean. It contains a lot of missing values which will cause our model problems. I used few techniques to fill the missing values. I filled the missing value with the most frequent values, with mean. I used the correlations between data to fill the missing ones. For data exploratory analysis, I used pie chart, bar graph, histogram, boxplot, heatmap for further understanding of clients’ details. I found that Male with graduation certificate who is not self-employed tend to have high approved status. The married applicants with 0 children also have higher approved status compared to many dependents. I created dummy variables for the categorical variables to feed my model. For the model selection, I compared the decision tree, random forest, and support vector machine to predict whether the financial department will approve the loan.

![category](https://user-images.githubusercontent.com/32876600/107391695-f6b41d00-6ac6-11eb-9772-5d6f86ff518f.JPG)

Eventually, with the tuned model, I concluded that random forest was the best model to automate the process because it gave me the higher accuracy with no overfitting or underfitting problems. And As a financial department, they tend to approve the loan to the customers who have a good credit history, and both the applicants and co-applicants with high income.  

![importance](https://user-images.githubusercontent.com/32876600/107391919-2b27d900-6ac7-11eb-8696-59d7410224e6.JPG)
