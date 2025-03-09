# Phase-3-Syriatel-churn-project

## *_A PROJECT BY K-MEANS KAPITAL_*

A company named Syriatel, has tasked us to analyze their data and build models to help them predict the churn for the customer base.

They have been experiencing customer loss and as such they need us to help the determine whether a customer shall leave or stay based on the data set provided.

**Analysis was conducted on;**

1. Churn
2. Voice mail plan
3. International plan
4. Customer service calls
5. Among other columns in the data

**Data Used**
1. We used a dataset provided to us by SyriaTel

**Packages Used**
pandas, seaborn, matplotlib.pyplot, numpy, warnings, sklearn.preprocessing(MinMaxScaler), sklearn.linear_model(LogisticRegression), sklearn.metrics(accuracy_score, recall_score, precision_score, f1_score, classification_report, confusion_matrix), sklearn.model_selection (train_test_split), sklearn.model_selection(GridSearchCV), sklearn.ensemble(RandomForestClassifier), sklearn.tree(DecisionTreeClassifier).

**Insights**

![image](https://github.com/user-attachments/assets/3331ec32-9e5a-4a8f-ac9b-36dd4deaa23c)

We can see that they are losing customers only 483 out of their total 3333 customer base, though a somewhat small number is very alarming.

**Distribution of other numeric variables**

![image](https://github.com/user-attachments/assets/3e11b1dc-7c24-4954-9b0d-ab9684f0ef7c)

**Correlation between variables**

![image](https://github.com/user-attachments/assets/c24308e1-da74-4f88-83ae-205b37d7ff26)

**Customer service calls by Churn to determine if a causing factor**

![image](https://github.com/user-attachments/assets/e91e668f-0633-4527-b7c8-2bb5276a29c2)

**Account length by Churn to detrmine if customer loyalty is a factor**

![image](https://github.com/user-attachments/assets/69132c36-4d2c-4d9c-b9f7-44c69a98acd6)

# **Classification Model Results**

![image](https://github.com/user-attachments/assets/97d3cba0-66e7-4c00-b8f3-904cfbd150e5)

# **Conclusion**

The company can rely on our Random Forest Classifier Model when testing impact of churn when applying customer retention strategies.




