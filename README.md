# MENA
The Global Terrorism Database (GTD) 
documents more than 190,000 international and domestic terrorist attacks that occurred worldwide since 1970

![gt](https://user-images.githubusercontent.com/46167070/73257226-0585a580-41cc-11ea-8aff-f39dca1fd159.PNG)


## Missing values
are representative of the messiness of real world data. There can be a multitude of reasons why they occur — ranging from human errors during data entry, incorrect sensor readings, to software bugs in the data processing pipeline.
### Categorial
Let’s start with the most simple thing you can do: removal. As mentioned before, while this is a quick solution, and might work in some cases when the proportion of missing values is relatively low (<25%), most of the time it will make you lose a ton of data. Imagine that just because of missing values in one of your features you have to drop the whole observation, even if the rest of the features are perfectly filled and informative!
Numerical NaNs A standard and often very good approach is to replace the missing values with mean, median or mode. 
### For numerical values
you should go with mean, and if there are some outliers try median (since it is much less sensitive to them).

### Dictionary Encoding
encode is a method that string instances has, not dictionaries. You can't simply use it with every instance of every  categorical  object Better encoding of categorical data can mean better model performance. In this series I’ll introduce you to a wide range of encoding options .

## Training and Testing
required to use the tuples of years from [2000. 2016] as training set b. Tuples of year 2017 will be used as testing set. c. We have 2 approaches in this assignment i. Train and test using features of GTD only. ii. Train and test using features of GTD and WHR combined.
 
## The F measure

(F1 score or F score) is a measure of a test's accuracy of Classifier Models and is defined as 
For the GTD Dataset:

## Classification

We used different classifiers and measured  accuracy, precision, recall and F-measure as a resultant confusion matrix of each model.The highest accuracy was from applying Decision Tree
model which reached 99% And it is considered good
KNN
This will apply KNN model and cross validation to get the best K
Best K found at K = 3For GTD DataSet
Best K found at K = 21 For Combined DataSet


