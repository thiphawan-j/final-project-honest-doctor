# project-sentiment-analytics

Term Project: Sentiment Analysis (Due Date: 1 Month after Midterm Exam)

Assume that you are working as data scientist who was given a problem to analyze customer experiences of hospital services. Traditional survey has several limitations such as reluctance feedback. Moreover, it takes time to get data and the hospital cannot make decision on time to handle customer experiences.

You are proposing the sentiment analysis as a solution for acquiring voice of customers. Data are acquired by scraping from the website www.honestdocs.com. You will work as a team which has 4 team members at maximum. Each team has to select 3 hospitals to analyze. From the first week of this project, each team must declare which hospitals are your target. You are not allowed to select the set of hospitals that exactly the same as other teams.
Your data sources were mainly written in Thai. You need to call google translation service to transform your data to English. For each customer comment, the sentiment polarity is positive if the number of starts is greater or equal to 4, 3 stars will be excluded, lower than 3 stars are negative.

You need to perform text preprocessing tasks for each comment as follows: 1) tokenization 2) stopword removal 3) TFIDF vectorization 4) LDA vectorization. For the sentiment polarity, you can encode it is 1 for positive and 0 for negative.
For modeling, you have to conduct machine learning experiment. Select the 3 best models in your opinion. Give us your justification why you selected such a model. Train your model using 10-fold cross validation on X_train and y_train. Pick the best model from cross validation to predict X_test.

From your prediction, you will extract sentiment words and entities based on S-V-O schema. You will conduct post processing analysis to categorize entities for each sentiment polarity. Then you will show your data visualization using word cloud and radial chart for comparison.

Deliverable:
1) Create your project on GitHub and push your source codes and data to your Git. Share the link of your project to instructors.
2) Prepare Powerpoint presentation to explain each process in your project from data acquisition to sentiment visualization
