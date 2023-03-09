# DS-Take-Home-Challenge

### 1. Conversion Rate
##### Goal:
Optimizing conversion rate is likely the most common work of a data scientist, and rightfully so. 
The goal of this challenge is to build a model that predicts conversion rate and, based on the model, come up with ideas to improve re]enue.
##### Challenge Description:
- Predict conversion rate.
- Come up with recommendations for the product team and the marketing team to improve conversion rate.


### 2. Spanish Translation A/B Test
##### Goal:
A/B tests play a huge role in website optimization. Furthermore, companies often run tens, if not hundreds, of A/B tests at the same time. Manually analyzing all of them would require lot of time and people. Therefore, it is common practice to look at the typical A/B test analysis steps and try to automate as much as possible. 
The goal of this challenge is to analyze results from an A/B test.
##### Challenge Description:
- Confirm that the test is actually negative. That is, it appears that the old version of the site with just one translation across Spain and LatAm performs better.
- Explain why that might be happening. Are the localized translations really worse?
- If you identified what was wrong, design an algorithm that would return FALSE if the same problem is happening in the future and TRUE if everything is good and the results can be trusted.


### 3. Employee Retention
##### Goal:
Employee turn-over is a very costly problem for companies. Understanding why and when employees are most likely to leave can lead to actions to improve employee retention as well as planning new hiring in advance. This application of DS is sometimes called people analytics or people data science.
The goal of this challenge to predict when employees are going to quit by understanding the main drivers of employee churn.
##### Challenge Description:
- Assume, for each company, that the headcount starts from zero on 2011/01/23. Estimate employee headcount, for each company, on each day, from 2011/01/24 to 2015/12/13.
That is, if by 2012/03/02 2000 people have joined company 1 and 1000 of them have already quit, then company headcount on 2012/03/02 for company 1 would be 1000. You should create a table with 3 columns: day, employee_headcount, company_id.
- What are the main factors that drive employee churn? Do they make sense? Explain your findings.
- If you could add to this data set just one variable that could help explain employee churn, what would that be?


### 4. Identifying Fraudulent Activities
##### Goal:
The goal of this challenge is to build a machine learning model that predicts the probability that the first transaction of a new user is fraudulent.
##### Challenge Description:
- Build a model to predict whether an activity is fraudulent or not. Explain how different assumptions about the cost of false positives vs false negatives would impact the model.
- How would you explain how the model is making the predictions? Not from a mathematical perspective, but from a user perspective. What kinds of users are more likely to be classified as at risk? What are their characteristics?
- Let's say you now have this model which can be used live to predict in real time if an activity is fraudulent or not. From a product perspective, how would you use it? That is, what kind of different user experiences would you build based on the model output?


### 5. Funnel Analysis
##### Goal:
The goal is to perform funnel analysis for an e-commerce website.
##### Challenge Description:
The company CEO isn't very happy with the ]oluTe oM sales and, especially, oM sales coming from new users. Therefore, she asked you to investigate whether there is something wrong in the conversion funnel or, in general, if you could suggest how conversion rate can be improved.
Specifically, she is interested in :
- A full picture of funnel conversion rate for both desktop and mobile
- Some insights on what the product team should focus on in order to improve conversion rate as well as anything you might discover that could help improve


### 6. Pricing Test
##### Goal:
The goal here is to evaluate whether a pricing test running on the site has been successful.
##### Challenge Description:
Company XYZ sells a software for $39. Since revenue has been flat for some time, the VP of Product has decided to run a test increasing the price. She hopes that this would increase revenue. In the experiment, 66% of the users have seen the old price ($39), while a random sample of 33% users a higher price ($59).
The test has been running for some time and the VP of Product is interested in understanding how it went and whether it would make sense to increase the price for all the users.
Especially he asked you the following questions:
- Should the company sell its software for $39 or $59?
- The VP of Product is interested in having a holistic view into user behavior, especially focusing on actionable insights that might increase conversion rate. What are your main findings looking at the data?
- [Bonus] The VP of Product feels that the test has been running for too long and he should have been able to get statistically significant results in a shorter time. Do you agree with her intuition? After how many days you would have stopped the test? Please, explain why.


### 7. Marketing Email Campaign
##### Goal:
The goal is to optimize marketing campaigns.
##### Challenge Description:
You are in charge of figuring out how the email campaign performed and were asked the following questions:
- What percentage of users opened the email and what percentage clicked on the link within the email?
- The VP of marketing thinks that it is stupid to send emails to a random subset and in a random way. Based on all the information you have about the emails that were sent, can you build a model to optimize in future email campaigns to maximize the probability of users clicking on the link inside the email?
- By how much do you think your model would improve click through rate (defined as # of users who click on the link / total users who received the email). How would you test that?
- Did you find any interesting pattern on how the email campaign performed for different segments of users? Explain.


### 8. Song Challenge
##### Goal:
The goal is to learn dealing with json files.
##### Challenge Description:
- What are the top 3 and the bottom 3 states in terms of number of users?
- What are the top 3 and the bottom 3 states in terms of user engagement? You can choose how to mathematically define user engagement. What the CEO cares about here is in which states users are using the product a lot/very little.
- The CEO wants to send a gift to the first user who signed-up for each state. That is, the first user who signed-up from California, from Oregon, etc. Can you give him a list of those users?
- Build a function that takes as an input any of the songs in the data and returns the most likely song to be listened next. That is, if, for instance, a user is currently listening to "Eight Days A Week", which song has the highest probability of being played right after it by the same user? This is going to be v1 of a song recommendation model.
- How would you set up a test to check whether your model works well and is improving engagement?


### 9. Clustering Grocery Items
##### Goal:
The goal of this challenge is to look at user purchase history and create categories of items that are likely to be bought together and, therefore, should belong to the same section.
##### Challenge Description:
- The company founder wants to meet with some of the best customers to go through a focus group with them. You are asked to send the ID of the following customers to the founder:
  - the customer who bought the most items overall in her lifetime 
  - for each item, the customer who bought that product the most
- Cluster items based on user co-purchase history. That is, create clusters of products that have the highest probability of being bought together. The goal of this is to replace the old/manually created categories with these new ones. Each item can belong to just one cluster.


### 10. Credit Card Transactions
##### Goal:
You have a dataset of credit card transactions and you have to identify unusual/weird events that have a high chance of being a fraud.
##### Challenge Description:
- Your boss wants to identify those users that in your dataset never went above the monthly credit card limit(calendar month). The goal of this is to automatically increase their limit. Can you send him the list of Ids?
- On the other hand, she wants you to implement an algorithm that as soon as a user goes above her monthly limit, it triggers an alert so that the user can be notified about that. We assume here that at the beginning of the new month, user total money spent gets reset to zero (i.e. she pays the card fully at the end of each month) Build a function that for each day, returns a list of users who went above their credit card monthly limit on that day.
- Finally, your boss is very concerned about frauds cause they are a huge cost for credit card companies. She wants you to implement an unsupervised algorithm that returns all transactions that seem unusual and are worth being investigated further.


### 11. User Referral Program
##### Goal:
The goal of this challenge is to analyze the data from a referral program and draw conclusions about its effectiveness.
##### Challenge Description:
- Can you estimate the impact the program had on the site?
- Based on the data, what would you suggest to do as a next step?
- The referral program wasn't really tested in a rigorous way. It simply started on a given day for all users and you are drawing conclusions by looking at the data before and after the test started. What kinds of risks this approach presents? Can you think of a better way to test the referral program and measure its impact?
