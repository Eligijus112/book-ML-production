# Welcome to the book

This book is intended to bridge the gap between machine learning model creators and web developer who ussually are responsible for serving predictions of machine learning models to the world. I hope that after reading this interactive book the two groups will find many tricky definitions and frameworks not so puzzling. 

# Motivation for writting 

My journey as a machine learning implementer began by studying mathematical models on a darkboard and using R or Python just to run scripts that generate either a plot or a spreadsheet. When learning the concepts of statistics (or going through the vast majority of online courses about it) the coded project is like a pipeline:

``` 
# All the necesary packages are importated in order for the pipeline to run 
import_packages()

# Reading data data, 95% of the time from a .csv
read_data() 

# scikit-learn, pytorch, tensorflow
model_creation_package_written_by_a_team_of_PHDs()

# model -> "output/model.pkl"
saving_output() 
```

To write such a pipeline in a robust manner takes years of coding and statistical knowledge, but for a business that intends to use the results of the pipeline the work is far from complete. 

This crucial process of creating an API from the outputed model is a weak point for many statisticians who devote much of their time in cleaning inputs, tunining parameters and explaining the results. I was there myself. The playfull nature of web applications' documentations for a mathematician that is used to cold and precises definitions does not help as well. 

On the other hand, I had to communicate basic concepts of machine learning to respected web developers and what to expect from a machine learning model output. Coming from a mathematics background it seemed very intuitive for me that a classifier should output a probability between 0 and 1 and we should write tests for that but for a front-end wizard the well known truths of statistics are not so well known. 

Here is where this book comes in handy - I will go through each of the pitfalls and misconceptions I went through personally when learning web development and will try to explain them from a data scientist perspective. Additionaly, I will try to explain popular math concepts for web developers as well. 

# Acknowledgment 

I do not believe in the "self-made" concept. Each person we meet life adds some value to us, be it a pleasant or unpleasant experience. Thus, I want to thank every person I had the privilage socializing and working with. 