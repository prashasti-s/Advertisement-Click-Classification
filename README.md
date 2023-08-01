# Advertisement-Click-Classification
Advertisement-Click-Classification using Python

**The goal of the case study is to work with the historical advertising data of a marketing agency from january 2020 to july 2020 and develop a machine learning model using Python to predict if a particular user will click on the Advertisement given on the website in future based on the user behaviour and user profile. Using the results we should be able to understand the customer demographics and behavior in order to support the business's advertising efforts and improve click-through rates and conversions.**


**Data Description:**
*We have the historical data of various users and different ads which they were exposed to and if they have clicked on the ad or not.*

This data set contains the following features:

1. VistID: The id for the user who visits the website
2. Time_Spent: Average time spent by user on site in minutes
3. Age: User's age in years
4. Avg_Income: Average Income of the user
5. Internet_Usage: Average minutes a day user spent on the internet
6. Ad_Topic: Headline of the advertisement
7. Country_Name: Country of user
8. City_Code: City of user
9. Male: Whether or not user was male
10. Time_Period: Time at which consumer clicked on Ad
11. Weekday: Name of the day
12. Month: Name of the months
13. Year: Which year the data is collected
14. Clicked: 0 means not clicked and 1 means that user clicked the Ad.

We are mostly interested in the variable "Clicked" There are two possible outcomes for this variable: 0 and 1, where 0 denotes the situation in which a user did not click the advertisement and 1 denotes the event in which a user clicked the commercial.

**For the model we will use 'Clicked' as the target varable.**

# Model Used for Building classification:
 - **NAIVE BAYES**  - The Naive Bayes classification algorithm is a probabilistic machine learning classifier. It is based on probability models that incorporate strong independence assumptions. The independence assumptions often do not have an impact on reality. Therefore they are considered as naive.

**The accuracy for the naive bayes model is only 54 percent**

 - **SUPPORT VECTOR MACHINE** - Support Vector Machine (SVM) is a supervised machine learning algorithm capable of performing classification, regression and even outlier detection. The linear SVM classifier works by drawing a straight line between two classes. All the data points that fall on one side of the line will be labeled as one class and all the points that fall on the other side will be labeled as the second.

**The accuracy for SVM is 93.4 percent**

 - **DECISION TREES** - A decision tree is a widely used supervised machine learning algorithm employed for classification and regression tasks. It takes the form of a flowchart-like tree structure, where each internal node represents a test on a specific attribute (feature), each branch shows the outcome of the test, and each leaf node signifies a class label (in classification) or a numerical value (in regression).

**The accuracy for the decision tree model is 92.6 percent**

 - **RANDOM FOREST** - Random forest or Random Decision Forest is a method that operates by constructing multiple decision trees during training phases. The decision of the majority of the trees is chosen as final decision.

**The accuracy for the decision tree model is 94.2 percent**

# Conclusion:
 - Random forest model is the best out of all the models that we built.

 - People who spend more time on the website are clicking on ads less as compared to people who spend less time on the site and it is the people of lower age group who are spending more time on the site so to increase the number of clicks, the website should show ads of products that cater to the younger age group. This means that the company should focus on targeting ads for products and services that are likely to be of interest to younger users, such as fashion, technology, and entertainment. Using more modern design or featuring more current trends will be helpful.

 - It is also seen that people who are rich are clicking less on the ads even though they are spending more time on the website. One reason for not clicking could be that the site is showing ads of products that lower income group people buy. To increase the clicks the company can show ads of products that usually rich people buy This means that the company should focus on targeting ads for luxury products or high-end services that are likely to be of interest to wealthier users.

 - It is also seen that people who spend more time on the internet also spend more time on this website. This means that the company should focus on making sure that the website is easy to navigate and use for users who are already spending a lot of time online. This can be done by optimizing the website's layout, design, and functionality to make it more user-friendly.


These informations can be used to target different groups of users with different types of ads or to optimize the placement of ads on the website to optimize the user experience. 


