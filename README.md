# Sentiment-Analysis-for-E-Commerce-Company

To analyze the sentiment for women’s clothing ecommerce, I along with a teammate analyze the reviews from customers on their products.

The dataset had close to 24000 rows and 10 variables. The important variables were Ratings, recommendation, review text, and product information. We started analyzing the text columns by using regex, removing special characters, creating bag of words.

We developed predictive models like **Naive Bayes, Logistic Regression, and Multilayer Perceptron** to differentiate the sentiment of reviews. We obtained 90%+ accuracy for each of our model. We also implemented **SVM** model with an accuracy of 91%. 

To obtain the best model, we changed multiple parameters for each of the model. We also evaluated each model using the basic evaluation metrics. We develop confusion matrix and AUC-ROC curve for our models.

**Results:** We were able to differentiate the sentimes of each customer of the ecommerce company with an accuracy of 92%.

**Python Libraries:** NumPy, Pandas, Sklearn, Matplotlib, Seaborn
