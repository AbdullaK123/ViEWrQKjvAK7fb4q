# ViEWrQKjvAK7fb4q

# Introduction

In this project, we aim to help a logistics company improve their customer experience and supply chain by developing a machine learning model to help predict whether a customer will be happy or unhappy with their delivery experience. With this model, we can discover what factors influence customer happiness the most and suggest actions stakeholders can take mined from the data itself.

# The Data

Our survey data is a csv file with the following data dictionary:

 - **X1**: My order was delivered on time.
 - **X2**: The contents of my order were what I expected.
 - **X3**: I was able to order everything I wanted.
 - **X4**: I paid a good price for my order.
 - **X5**: I am satisfied with my Courier.
 - **X6**: The app makes ordering easy for me.
 - **Y**: Our target. A binary column with 0 indicating the customer was not happy with their experience and 1 indicating the opposite.

`Y` is the target variable for our classification model, and we will use the other variables as features.

# Methods

To accomplish our goals, we will use Bernoulli Naive Bayes classifier, augmented with recursive feature elimination. Naturally, we will split our data into training and test sets with an 80-20 split, and we aim to achieve an accuracy score of at least 80% on the test set.
