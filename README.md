# titanic-ML
This is my solution to the Kaggle competition "Titanic - Machine Learning from Disaster"

The challenge, is as follows:

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

The data for this challenge is split into a training set and a test set, along with an example submission. The training and test set contain the following features:

- survival, which indicates whether a passenger survived or not, and has values:	0 = No and a 1 = Yes (this is the class label)
- pclass, which indicates which class a passenger is sitting in, and has values:	1 = 1st, 2 = 2nd, 3 = 3rd
- sex, which indicates which Sex a passenger is
- age, which indicates a passenger's age in years
- sibsp, which indicates number of siblings/spouses aboard the Titanic a passenger has
- parch, which indicates numer of parents/children aboard the Titanic a passenger has
- ticket, while indicates a passenger's ticket number
- fare, which indicates the amount of money (fare) a passenger paid
- cabin, which indicates the Cabin number the passenger is staying in
- embarked, which indicates the	Port of Embarkation the passenger took off from, and has values:	C = Cherbourg, Q = Queenstown, S = Southampton

In this notebook, we perform exploratory data analysis, preprocess the training data, visualize all the features, and contextualize each feature's relationship with the class label (survival). Then, we train and run Logistic regression, K-nearest neighbors, Gaussian naive bayes, and Decision tree classifiers and assess their accuracy on the training dataset. After determining that the Logistic regression model is the most accurate, we preprocess the test data, and make predictions on the test data with this model, and submit the final predictions. 

Kaggle gave this submission a score of 0.76555. 

To use these files to perform your own predictions:
1. Download the data and the other files
2. Place all the files in the same directory
3. (Optional) Open the notebook in colab
4. Download/import all the dependencies: os, math, time, random, datetime, numpy, pandas, seaborn, matplotlib.pyplot, missingno, (OneHotEncoder, LabelEncoder, label_binarize) from sklearn.preprocessing, train_test_split from sklearn.model_selection, (model_selection, tree, preprocessing, metrics, linear_model) from sklearn, KNeighborsClassifier from sklearn.neighbors, GaussianNB from sklearn.naive_bayes, (LinearRegression, LogisticRegression, SGDClassifier) from sklearn.linear_model, DecisionTreeClassifier from sklearn.tree 
5. Run the code and make any adjustments to the models necessary

The actual Kaggle Titanic competition can be found here: https://www.kaggle.com/c/titanic
This work can also be accessed through Kaggle here: https://www.kaggle.com/abhivadali35/titanic-beginner-s-ml-w-logistic-regression

Thank you to Daniel Bourke for helping me learn and work my way through this competition, you can check out his work here: https://www.mrdbourke.com/. 
