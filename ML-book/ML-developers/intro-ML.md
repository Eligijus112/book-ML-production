# Machine learning models

There are many books and videos about machine learning. From the many definitions I have read throughout my time as an machine learning (ML for short) practitioner, one stood out: 

"A computer program is said to learn from experience **E** with respect to some class of tasks **T** and performance measure **P** if its performance at tasks in **T**, as measured by **P**, improves with experience **E**." - Tom M. Mitchell {cite}`ML_definition` 

This definition holds for various types of data and models. Lets quickly go through each of the main letters in the definition.

## Building blocks of the definition 

### E - experience 

The experience can be viewed as data. Data can be stored in various of formats: spreadsheets, python or R files, database tables. 

For a machine learning algorithm to work the data needs to be **tidy**{cite}`tidy_data`: 

"Each variable is a column, each observation is a row, and each type of observational unit is a table" 

If a person observes if it is snowing or not (event) and measures the temperature (feature), appends a new row to a spreadsheet with the current temperature and event outcome (snow or not) then this kind of data can be called tidy. If the the current temperature is in one row, and the event of snow is logged in a separate sheet that cannot be attributed to a certain temperature, then the data is not tidy. 

### T - tasks 

The task for a machine learning algorithm can be one of many - better recommendations, a more precise evaluation of a house price, better identification of spam in an email, etc. 

When dealing with binary classification for example, the task is to classify whether an observation falls to one class or another. Ussualy, ML models output not 1 or 0 (meaning belonging to class "1" or "0") but a probability that an observation falls into a certain class: 

### P - performance measure 

In the previous section about tasks, I used words like "better" and "more precise". In order to not use sentiments and to be able to really prove that your results are "better" various metrics are used that are ussually a number - a probability, accuracy scores, precision and recall scores, etc. 

When thinking about a business problem which we want to solve using ML it is always advised to come up with concrete performance measures that we want to optimize. 

For example, an ML model outputs a probability whether a transaction is fraud or not. Then we can measure its precision and communicate the precision results to the higher ups. 