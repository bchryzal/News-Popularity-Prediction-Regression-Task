# Competition url 
https://www.kaggle.com/competitions/ml-lab-ii-c35/overview

# Problem Statement
In this competition, you will build Regression models which accurately predict the popularity of new articles (the number of times it will be shared online) based on ~60 features provided to you.

# Importance of online news
The consumption of online news is expediting day by day due to the extensive adoption of smartphones and the rise of social networks. Note that online news content comprises various key properties. For example, it is easily produced and small in size; its lifespan is short and the cost is low. Such Qualities make news content more effective to be consumed on social sharing platforms. More interestingly, this sort of content can capture the eye of a signiﬁcant amount of Internet users within a brief period of your time. As a result, the main target on the analysis of online news content like predicting the recognition of stories articles, demonstrating the decay of interest over time to know the world of online news has greatly increased since it has so many practical meanings.

# Why news popularity prediction?
There are multiple areas of applications for online news popularity prediction. Some of these benefits include gaining better insights into the audience consuming online news content. Consequently, it increases the ability of news organizations to deliver more relevant and appealing content in a proactive manner as well as the company can allocate resources more wisely to prepare stories over their life cycle. Moreover, prediction of news content is also beneﬁcial for trend forecasting, understanding the collective human behavior, advertisers to propose more proﬁtable monetization techniques, and readers to ﬁlter the huge amount of information quickly and efﬁciently.

# Evaluation
## Goal
It is your job to predict how many times an article will be shared online (target variable name: "shares"), given the ~60 columns containing a summary about the content of the article, temporal features, features associated with metadata of the article, and features pulled from other NLP models run on the data.

## Metric
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the value of the predicted value and the actual value of # of shares for each article.


## Submission file format
The file should contain a header and have the following format (CSV):

id,shares

29733,3262.0

29734,802.0

29735,953.0

etc.
