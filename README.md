# Car-Popularity-Prediction

### Steps I followed :

1. First I have an overview on the training data using and seperate the popularity dataset from the training one to the target one.

2. To import the csv file I uses pandas.read_csv() function

3. Now I apply the RandomForestClassifier on the training datset with (n_estimator=20)

4. This classifier is imported using : from sklearn.ensemble import RandomForestClassifier

5. Now I train the model using this classifier

6. And at last we predict the popularity of the test_data.

7. And check our accuracy by uploading it to the Hackerrank plateform 

8. I get the accuracy of 97.96%
