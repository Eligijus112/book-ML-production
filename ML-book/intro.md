# Welcome to the book

An anecdotal definition of a data scientist is that it is a person who "is better in software development than an average statistician and is better at statistics than an average software developer". In todays business world, it is expensive to keep a person who is just above average in all the fields and a master of none. From my experience, a data scientist must be very competent in machine learning as well as be able to create a fast and secure way for people around the world to access the machine learning models that are created. 

I would introduce a new definition of a true data scientist: 

"A person that is able to create, present and serve machine learning models to the world". 

The main focus are on the words **create**, **present** and **serve**. Each has a huge depth underneath them. This book will be like a personal notebook that links all of these parts together. I have heard numerous times that the way I explain things makes sense to everybody in the room thus I want to share my experience to the world.

All the codes and the book are tracked in GIT: https://github.com/Eligijus112/book-ML-production 

The main programming language is **python**.

# Motivation for writting 

There are two main motivations: one altruistic and one egoistic. 

**The altruistic one**:

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

**The egoistic one**: 

I have realized early in my education that the best way to figure out a concept is by presenting and teaching it to others. By putting everything I know about machine learning in a digital document I will have a handy refference book and will get a better grasp of the concepts in my head.

# Overview of the book 

The book is split into two major parts:

**Machine Learning model creation and presentation**

**Machine Learning model serving through an API** 

It is essential to know some concepts of machine learning before trying to implement models in production. That is why we will start from the broad theme of machine learning. 

If you feel very comfortable in one of the themes, skip ahead to the next one. If you are a master of both, please email me at elasorama@gmail.com and share your critism of the book. Or even better, create a merge request and let me review it. It is much appreciated! 