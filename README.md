# supervised-machine-learning-challenge

The data is located in the Resources Folder:

lending_data.csv

I think Logistic Regression suits the model,because the data looks like categorical.My prediction of output is also categorical.So I prefer logistic regression model is best for this. As of now I predict Random Forest model do not suit well for this data.

Create a Logistic Regression model, fit it to the data, and print the model's score. 
![image1](https://user-images.githubusercontent.com/111449865/223534984-028689a0-fa89-497f-b3a7-69f0673dae26.png)

Did the same for a Random Forest Classifier.
![image2](https://user-images.githubusercontent.com/111449865/223535070-69ce28db-45af-42fb-bf82-60e2f242a1f8.png)
![image3](https://user-images.githubusercontent.com/111449865/223535143-e8c708d4-c0ce-494f-b974-9172fe42215a.png)


Tried to find answers for the following questions:
Which model performed better?
How does that compare to your prediction? 

My Conclusion:
After the evaluation,Random Forest Model is consistent with 99% either with actual data or test data.
We can see Logistic regression is also consistent with 99% with scaled data or test data. My prediction in the begining was wrong.
A forest is less interpretable than a single decision tree. Single trees may be visualized as a sequence of decisions. 
A trained forest may require significant memory for storage, due to the need for retaining the information from several hundred individual trees. So I conclude both Random Forest Model and Logistic Regression model suits for this data.
But I prefer Logistic Regresssion than RandomForest model,because the time taking to process Random Forest model is more than logistic Regression.
