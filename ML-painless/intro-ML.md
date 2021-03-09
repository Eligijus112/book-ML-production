# Machine learning for developers 

There are many books and videos about machine learning. From the many definitions I have read throughout my time as an machine learning (ML for short) practitioner, one stood out: 

"A computer program is said to learn from experience **E** with respect to some class of tasks **T** and performance measure **P** if its performance at tasks in **T**, as measured by **P**, improves with experience **E**." - Tom M. Mitchell {cite}`ML_definition` 

This definition holds for various types of data and models but for the sake of simplicity and intuition building lets plug in an object from every day computing to each of the capital letters in the definition. 

# E - experience 

The experience can be viewed as data. Data can be stored in various of formats (altough the good old .csv is still king in big corporations): spreadsheets, python or R files, database tables. 

For a machine learning algorithm to work the data needs to be **tidy**{cite}`tidy_data`: 

"Each variable is a column, each observation is a row, and each type of observational unit is a table" 

