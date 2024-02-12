<h1 align="center">
             Text Analysis Web App
</h1>

This app is used to perform an indepth analysis of a text
The analysis sections include ->

**1. Spam or Ham Detection**

**2. Sentiment Analysis**

**3. Stress Detection**

**4. Hate & Offensive Content Detection**

**5. Sarcasm Detection**

## Structure Of The Project

- Each prediction page is conneceted with a Machine Learning Model which uses either of Logistic Regression, Decision Tree, Random Forest Algorithms to predict the results.
- Also we have 5 different datasets being used for each prediction.
- We can land into each prediction site of the web app from the options in the Navigation Menu.
- We have only 1 relevant feature taken into consideration which is the text and then the text is preprocessed and vectoized with help of TF-IDF Vectorizer to fit into the model and tain it.
- So the user gets a broad overview of the text after the analysis

## The feature taken into consideration

| Text Analysis Type | Feature |
| - | - |
| Spam or Ham Detection Page | Text |
| Sentiment Analysis Page | Text |
| Stress Detection Page | Text |
| Hate & Offensive Content Page | Text |
| Sarcasm Detection | Text |

The text is preprocessed then fed to the model.
