# Food Delivery Subscription Customer Churn Analysis & Retention Strategy
A comprehensive end-to-end customer analytics and machine learning solution for understanding customer churn causes from food delivery subscriptions has been developed. This involves analyzing customer behavior, spending, satisfaction level, and engagement with their subscriptions in order to forecast customer churn and suggest data-informed retention methods.
The process uses Exploratory Data Analysis (EDA), customer segmentation, and machine learning algorithms to help subscription-based companies minimize customer churn and increase their retention rate.

**Business Problem**
The subscription food ordering services suffer huge losses because of customer churn rates. Customer retention proves to be cheaper than customer acquisition, making customer retention one of the essential goals for any business.

The company needed to know the following things:
1. Who are the customers who tend to churn
2. Which behaviors have an impact on the churn rate
3. How does customer satisfaction affect retention
4. Which customers tend to churn
5. How predictive analytics could help in improving retention strategies
6. What operations need improvement to reduce customer churn

**Business Objective**
1. Identify factors contributing to customer churn
2. Analyze customer subscription behavior
3. Analyze behavioral differences between retained and churned customers
4. Predict high-risk customers using machine learning
5. Segment customers based on churn risk
6. Provide data-driven recommendations to improve retention

**Tools & Technology**
1. Python -  Data analysis & machine learning (libraries used: Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn)
2. Excel (Data Cleaning & Exploration)

**Dataset**
Food delivery subscription customer dataset - primary data collection through google form
500+ customer records

**Key Business KPI's**
1. Total Customers - 500
2. Customer Churn Rate - 21.8%
3. Customer Retention Rate - 78.2 %
4. Average Monthly Spend - 814 rs
5. Average Subscription Duration - 8 months
6. Random Forest Model Accuracy - 93%

**Analysis**
**1. Customer Demographic Analysis**
* Age groups
* Occupation
* City distribution
* Customer engagement patterns
  
**Key Findings**
* Young adults and professionals were the main subscribers to the subscription packages
* The highest rate of subscriber turnover was among professionals (~33.7%)
* Students displayed relatively high subscription retention rates

**Business Insight**
* Working professionals showed higher subscription cancellation risk, indicating a need for targeted retention campaigns and personalized engagement strategies.

**2. Customer Spending Behavior Analysis**
* Monthly customer spending
* Spending behavior of retained vs churned customers
* Revenue contribution patterns

**Key Findings**
* Average monthly expenditure: ₹814
* The retained customers outspent the churned customers substantially.
* High-expenditure customers exhibited greater loyalty and lesser churn tendency.

**Business Insight**
Customers receiving higher value from the platform were more likely to remain subscribed, highlighting the importance of increasing customer engagement and platform dependency.

**Recommendations**
Implement Subscription-exclusive offers & Personalized restaurant recommendations also give Loyalty rewards for frequent users

**3. Subscription Duration & Retention Analysis**
* Subscription duration patterns
* Relationship between subscription length and churn

**Key Findings**
* Average time to subscription: 8.56 months
* New clients were more likely to churn
* Long-term clients had better loyalty towards the platform
  
**Business Insight**
Early stage customers are high likely to churn.

**Recommendations**
Improve onboarding experience by giving welcome offers, have early stage campaigns, personalised onboarding, free delivery and discounts.

**4. Customer Satisfaction Analysis**
* Delivery ratings
* App ratings
* Value-for-money ratings
* Restaurant experience ratings

**Key Findings**
* Delivery Rating	- 4.03
* App Rating	- 3.96
* Value Rating	- 3.36

**Business Insight**
Customers with low satisfaction are high likely to churn. 

**Recommendations**
Focus on customer satisfaction & operations like timely delivery, optimize user experience & implement customer support responsiveness

**5. Order Frequency Analysis**
* Customer order frequency
* Relationship between engagement and churn

**Key Findings**
* Retained customers placed orders more frequently
* Lower engagement customers showed higher churn probability

**Business Insight**
Customers who use the platform frequently are less likely to churn 

**Recommendations**
Increase customer engagement through personalised offers, rewards, loyalty programs, discounts

**6. Cancellation Intent Analysis**
*Relationship between cancellation intent and actual churn behavior

**Key Findings**
* Customers planning to cancel had ~41.7% probability of churn
* Customers without cancellation intent showed only ~11.5% churn probability

**Recommendation**
Create a retention strategy for the customers who may churn give them retention discounts, customer support outreach & Personalised communication.

**Machine Learning Churn Prediction**
**Built predictive models to identify customers at high risk of subscription cancellation.**
**Model used**
* Logistic Regression - Accuracy 79%
* Random Forest Classifier - Accuracy 93%

**Model Performance Analysis**
The Random Forest model performed much better than the Logistic Regression model by analyzing complex relationships between behaviors, expenses, and customer satisfaction.

The predictive model allows organizations to:

* Predict risky customers prior to churn
* Implement proactive retention initiatives
* Increase efficiency in customer retention efforts
* Minimize revenue leakage from lost customers
* Target valuable customers for retention

**Business Impact**
Operational Risks Identified such as Loss of recurring revenue, Increased customer acquisition costs, Reduced customer lifetime value, Weak long-term customer loyalty

**Recommendations**
1. Implement Predictive Churn Monitoring
2. Improve Customer Satisfaction
3. Launch Personalized Retention Campaigns
4. Strengthen Early Customer Engagement
5. Build Real-Time Customer Risk Dashboard
