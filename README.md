# Credit_Risk_Analysis #

##Purpose of this analysis: ##
We will be trying to solve credit card risk. Using the credit card dataset provided by LendingClub and applied machine learning skills to predict credit risk. We built and evaluated models using different techniques to train and evaluate the models with unbalanced classes. 
## Results: ##

o	Describe the balanced accuracy scores
o	The precision{TP/(TP+FP)}
o	Recall scores of all six machine learning models{YP/(TP+FN)

Naïve Random Oversampling: accuracy score 64%, precision 99%, recall 55%
![NaiveRandomOversampling](https://user-images.githubusercontent.com/83199109/133880287-ef59d20e-5bf2-485a-9387-5f0ab3832897.png)

Smote Oversampling: accuracy score 66%, precision 99%, recall 69%


Undersampling: accuracy score 54%, precision 99%, recall 42%
![Undersampling (2)](https://user-images.githubusercontent.com/83199109/133879988-2532cf1f-e9e6-45d9-92ac-d94957c54062.png)

Over and under: accuracy score 64%, precision 99%, recall 58%
![OverUnderSampling (2)](https://user-images.githubusercontent.com/83199109/133880005-a5301b54-2b5f-4218-8890-0ee94ed0c8c1.png)

## Summary: ##
The overall results were not as promising as hoped for. The highest accuracy score acheived was from using the Smote Oversampling. Giving only a 66% accuracy score leaves a pretty high risk percentage.
