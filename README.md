# Review-Claasification
About:
The mmodel takes comments(movie review,amazon product review,restaurant review)of a dataset, trains it and uses it to predict if a comments can be claassified as good comment or a bad comment.

libraries used: 
1.pandas
2.numpy
3.re -to work on regular expressions 
4.matplotlib.pyplot -for visualization of data using plots
5.nltk -which inturn has text processing libraries in it. 
6.scikit-learn -library which implements regression, classification and other machine learning algorithms.

Approach:
1.importing the restaurant reviews dataset using pandas libraries.
2.stemmatization
3.vectorizing the words into 0's and 1's where 0 implies negative and 1 implies positive
4.creating bag of words using countVectorizer.
5.splitting the dataset into the training set and testset
6.using logistic regression as the classification algorithm to make prediction and find accuracy.
7.Few examples

Execution:
execute it on jupyter notebooks in anoconda,both csv and python files should be in folder.
to try with different datasets just change the name of csv file while reading csv in:
dataset=read_csv("file_name");
To give your own comments and check,call the deftest() function,pass a list of comments as arguements.
