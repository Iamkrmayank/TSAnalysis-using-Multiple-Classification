Twitter Sentimental Analysis-using-Multiple-Classification

About Twitter Sentimental Analysis

Nowadays, people from all around the world use social media to share their views or any information. 
Twitter is an online news and social networking site where people communicate in short messages called tweets.
Users share their daily lives, post their opinions on everything such as brands and places. 
Companies can benefit from this massive platform in various ways: 
• They can use twitter to increase their brand awareness 
• Inform customers about the updates 
• To get instant feedback about their product and services 
• Collect data related to opinions on them the most important thing for a company is to listen to market and meet the customers need.
When companies grow it becomes difficult for them to pay attention to each customer’s review and know what people think about them, this is where SENTIMENTAL ANALYSIS comes to use. 
About the project Twitter sentiment analysis identifies negative, positive emotions within the text of a tweet. It is a text analysis using multiple classification machine learning algorithm.

.... METHODOLOGY .....

<img width="166" alt="image" src="https://github.com/Iamkrmayank/TSAnalysis-using-Multiple-Classification/assets/103871423/96d81964-65c4-4cbb-a5ca-a32ac4970c70">

Flowchart of Sentimental Analysis Methodology

1.About Dataset:
The dataset being used is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the Twitter API. The tweets have been annotated (0 = Negative, 4 = Positive) and they can be used to detect sentiment.
It contains different features are sentiment, ids ,  date , flag, user and  text.

2.Pre-processing Dataset:
Text Pre-processing is 3traditionally an important step for Natural Language Processing (NLP) tasks. It transforms text into a more digestible form so that machine learning algorithms can perform better.
It includes 
i. Lower Casting : Converting all the tweet into lowercase.
ii. Replacing Emojis : Emojis can be replaced by using a pre-defined vocabulary that includes the symbols and their definitions.
iii. Replacing URL: Replace urls like “https” into HTTPS words.
iv. Removing Stop Words : Stopwords are English words that don't really add anything to a sentence. Without jeopardising the sentence's meaning, it is safe to ignore them.
v. Words with a length of fewer than two are eliminated.
vi. Lemmatizing is the process of returning a word to its fundamental form.
vii. Words containing more than 3 consecutive words like ‘heyyyy’ into two words ‘heyy’.

3.Analyse the data:
To better comprehend the pre-processed data, we will now analyse it.
To determine which words are most frequently used, we will plot Word Clouds for both positive and negative tweets from our dataset.

<img width="335" alt="image" src="https://github.com/Iamkrmayank/TSAnalysis-using-Multiple-Classification/assets/103871423/a10450f9-7c56-4705-b2ac-995236268a9f">

Fig of Tweets  where the font which bigger is mostly used in whole dataset like USER , day are of bigger font , these words are mostly used here.


4.Evaluating the model:
For our issue with sentiment analysis, we are developing three different types of models:

(BernoulliNB) Bernoulli Naive Bayes

<img width="232" alt="image" src="https://github.com/Iamkrmayank/TSAnalysis-using-Multiple-Classification/assets/103871423/609472bb-c7f4-48a3-ab1b-badd963271fe">

(c) Evaluation of Bernoulli Naive Bayes

Logistic Regression (LR) 

<img width="224" alt="image" src="https://github.com/Iamkrmayank/TSAnalysis-using-Multiple-Classification/assets/103871423/8bb46a58-f4fa-4b36-b82a-57a7c79e4eed">

Linear Support Vector Classification (LinearSVC)

<img width="222" alt="image" src="https://github.com/Iamkrmayank/TSAnalysis-using-Multiple-Classification/assets/103871423/0c7904a1-62f5-49d0-9657-9bf2ad4f2cb8">

Since there are an equal number of positive and negative predictions in our dataset, it is not skewed.
Accuracy will serve as our evaluation metric. To further assess how well our model is doing on both categorization classes, 
we are charting the Confusion Matrix.

5.Result and Discussion

<img width="371" alt="image" src="https://github.com/Iamkrmayank/TSAnalysis-using-Multiple-Classification/assets/103871423/9432cbd3-26c7-4aab-a928-e276a4fb23db">

Results shown in the above fig is the tweet given by the user and we are getting it sentiment where it’s a positive tweet or negative tweet.

Conclusion

In conclusion, Twitter sentiment analysis using machine learning approaches highlights the diverse methodologies and techniques employed in this field. 
By comparing various algorithms, including Bernoulli Naive Bayes , Logistic Regression (LR) and LinearSVC  . 
It provided valuable insights into their effectiveness and limitations.
These findings contribute to the ongoing development and improvement of sentiment analysis techniques for Twitter data.

Future Work

In the future, researchers can focus on a few key areas to improve sentiment analysis of Twitter data using machine learning.
They can explore using additional information like user profiles and social connections to better understand the context of tweets. 
They can also work on addressing challenges related to sarcasm, irony, and ambiguous language by developing smarter language models.
Additionally, considering images and videos alongside text can provide a more complete picture of sentiment.
Lastly, finding ways to adapt sentiment analysis techniques to different topics and languages will be important. 
By focusing on these areas, we can make sentiment analysis on Twitter more accurate and useful.
