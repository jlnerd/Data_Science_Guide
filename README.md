# Data Science Guide
A High-level guide to getting started and diving deep into data science &amp; machine learning

Author: John T. Leonard </br>
Contact: jtleona01@gmail.com

## Introduction
So you've decided to figure out what AI, machine learning, and data science is all about. Congratulations! This is going to be a long journey, but, as [Hari Seldon](https://en.wikipedia.org/wiki/Hari_Seldon) said, "[is] there anything more exciting in life than seeking answers?". Whether you're actually looking for a career change, or just want to learn something new, I think you'll find that the more data science & ML you learn, the more applications you'll find to apply it in your personal and/or work related projects. So, best of luck & happy learning!

Note: This doc/guide is a work-in-progress. Feel free to contact me with any suggestions/comments/requests. My hope is that some day it will be sufficiently developed to the point where I will publish it on [Towards Data Science](https://towardsdatascience.com)

## Approach
To really dive-deep in ML, you need to immerse yourself in it. There are 4 key steps you should take towards this end: 

1. Start following [Towards Data Science](https://towardsdatascience.com)
2. Take massive online open courses (MOOCs) while simultaneously working on [Kaggle](https://www.kaggle.com) projects.
3. Build your own API/package & use it in your projects and/or at work.
4. Always look for ways to apply your new ML/data science techniques to your day time job

## Why should you follow Towards Data Science? 
There are many data science & machine learning blogs out there, and many of them are outstanding. In particular, I have found Jason Brownlee's [Machine Learning Mastery](https://machinelearningmastery.com) blog to be a great resource for many things. However, what's so great about Towards Data Science is that there are countless authors publish articles that cover all of data science & ML, while simultaneously offering different perspectives on the same subject. Furthermore, Toward's Data Science is a great filter for academic literature, meaning that the high-level articles published there often reference various papers which could be read if you wish to dive deeper in one area or another.

Below are some good articles to get you started:
COMING SOON...

## Why Build Your Own API/Package
One of the key [principles of programming](https://www.makeuseof.com/tag/basic-programming-principles/) is DRY (Don't Repeat Yourself). This is probably actually a good principle to live by in general, since repeating yourself is a waste of time. In data science & ML, particularly in more basic problems, the steps you take to do some explorarory data analysis (EDA) and build and test a model are often quite similar. Thus, I recommend you start building your own API/Package to try to automate these steps for your own work-flows. Aside minimizing the number of times you repeat yourself, this will also start to get you familiar with more Dev-Ops side of things, such as building a package, running unit tests, code coverage, and much more. Furthermore, your API will be a good reference point where you can point people to see some code you've independantly built, and perhaps one day you'll even be able to use it in practice problems you may be given for job interviews. The API I built, and continue to build on occasion is [pyDSlib](https://github.com/jlnerd/pyDSlib). Feel free to go check it out if you're curious.

## Massive Online Open Courses (MOOCs) Overview
MOOCs are the best place to start if you're trying to get into data science/ML. The data science/ML community in particular seems to have really outstanding MOOCs which give you the basic knowledge you need to go off and start working on projects independantly. There are basically 5 big MOOC companies heavily competing:

1. [Coursera](https://www.coursera.org)
2. [Data Camp](https://www.datacamp.com)
3. [Udemy](https://www.udemy.com)
4. [Udacity](https://www.udacity.com)

In my opinion, Coursera & Data Camp are the best. The courses are the most well structured with high quality instructional videos, examples, and practice problems. Of course, things do very somewhat from course to course within each of the MOOC companies, so if you see something interesting offered by any of these, you should definateley go check it out.

Another commonly asked question related to MOOCs is whether or not the certificates they offer mater. Most people say no, and I agree that having 1 or 2 certificates from MOOCs doesn't really matter. However, if you have 20, 30, 40 certificates, I think this starts to have an impact. This shows you've invested a really significant amount of time to independantly learn this subject, and if you've taken that many courses and have projects as well, you'll probably be able to get pretty technical on a lot of data science/ML topics.

Aside from MOOCs, many Universities offer more thorough certicate programs, at a cost. I've taken such a program, and I was rather disapointed. One of the problems with my particular course was that it focused on using R. Just don't use R. It's on it's way out and honestly it's a waste of your time to learn it. The other problem, and arguably the more important problem with these kinds of programs from acredited universities, is that they prevent you from focusing your learning on areas you are most uncertain about or most interested in. In my experience, you can more quickly get up to speed if you have the flexibility to decide yourself what area you need to dive deeper on.

One question I found myself asking when I first started getting into ML was "which types of models should I really focus on". There are so many models out there and it can be a bit overwhelming at first if you think you need to be a master of all of them and understand each and every hyperparameter/architecture within each model. Fortunately, there a really just 2 types of general model styles/classes people are heavily using today:

1. Neural Networks (via [Tensorflow w/ Keras](https://www.tensorflow.org/guide/keras)) 
2. Gradient Boosted Decision Trees (via [xgboost](https://xgboost.readthedocs.io/en/latest/python/python_intro.html))

It's super important to learn about SVMs, KNNs, and all the other models out there, but you should really focus on becoming an expert in using Tensorflow & xgboost, as these two APIs have the widest use in industry. Also, it is of note that you rarely hear of decisions trees in the press, however xgboost is an extremely powerful model which can often perform better than neural networks (simpler model, less prone to overfitting, faster prediction, etc.) on many tasks, so don't buy into all the hype completely.

## Guide to MOOCs
Below are the MOOCs I recommend taking. They are roughly ordered, but you should feel free to jump around a bit if you'd like. Also, while you're working on MOOCs, try to work on a Kaggle competition/project as well. The Kaggle competitions I recommend are listed in the next section

1. [Coursera: Machine Learning, Andrew Ng, Stanford](https://www.coursera.org/learn/machine-learning)</br>
*This is a classic intro. to ML course. Almost everyone I've spoken to who moved into ML from another field said they took this course. It's pretty heavy on MatLab, which is a bit strange, but don't focus too much on learning MatLab, since all the other courses will focus on Python.*

2. [DataCamp: Career Track: Data Scientist with Python](https://www.datacamp.com/tracks/data-scientist-with-python)
    * [Introduction to Python](https://www.datacamp.com/courses/intro-to-python-for-data-science)
    * [Intermediate Python](https://www.datacamp.com/courses/intermediate-python-for-data-science)
    * [Project: TV, Halftime Shows, and the Big Game](https://www.datacamp.com/projects/684)
    * [Python Data Science Toolbox (Part1)](https://www.datacamp.com/courses/python-data-science-toolbox-part-1)
    * [Python Data Science Toolbox (Part2)](https://www.datacamp.com/courses/python-data-science-toolbox-part-2)
    * [Importing Data in Python (Part1)](https://www.datacamp.com/courses/importing-data-in-python-part-1)
    * [Importing Data in Python (Part2)](https://www.datacamp.com/courses/importing-data-in-python-part-2)
    * [Cleaning Data in Python](https://www.datacamp.com/courses/cleaning-data-in-python)
    * [Pandas Foundations](https://www.datacamp.com/courses/pandas-foundations)
    * [Manipulating DataFrames with pandas](https://www.datacamp.com/courses/manipulating-dataframes-with-pandas)
    * [Merging DataFrames with pandas](https://www.datacamp.com/courses/merging-dataframes-with-pandas)
    * [Analyzing Police Activity with pandas](https://www.datacamp.com/courses/analyzing-police-activity-with-pandas)
    * [Introduction to SQL](https://www.datacamp.com/courses/intro-to-sql-for-data-science)
    * [Introduction to Relational Databases in SQL](https://www.datacamp.com/courses/introduction-to-relational-databases-in-sql)
    * [Introduction to Data Visualization in Python](https://www.datacamp.com/courses/introduction-to-data-visualization-with-python)
    * [Interactive Data Visualization with Bokeh](https://www.datacamp.com/courses/interactive-data-visualization-with-bokeh)
    * [Statistical Thinking in Python (Part 1)](https://www.datacamp.com/courses/statistical-thinking-in-python-part-1)
    * [Statistical Thinking in Python (Part 2)](https://www.datacamp.com/courses/statistical-thinking-in-python-part-2)
    * [Joining Data in SQL](https://www.datacamp.com/courses/joining-data-in-postgresql)
    * [Introduction to Shell](https://www.datacamp.com/courses/introduction-to-shell-for-data-science)
    * [Conda Essentials](https://www.datacamp.com/courses/conda-essentials)
    * [Supervised Learning with scikit-learn](https://www.datacamp.com/courses/supervised-learning-with-scikit-learn)
    * [Machine Learning with the Experts: School Budgets](https://www.datacamp.com/courses/machine-learning-with-the-experts-school-budgets)
    * [Unsupervised Learning in Python](https://www.datacamp.com/courses/unsupervised-learning-in-python)
    * [Machine Learning with Tree-Based Models in Python](https://www.datacamp.com/courses/machine-learning-with-tree-based-models-in-python)
    * [Introduction to Deep Learning in Python](https://www.datacamp.com/courses/deep-learning-in-python)
    * [Network Analysis in Python (Part 1)](https://www.datacamp.com/courses/network-analysis-in-python-part-1)
3. [DataCamp: Career Track: Coding Best Practices with Python](https://www.datacamp.com/tracks/coding-best-practices-in-python)
    * [Writing Efficient Python Code](https://www.datacamp.com/courses/writing-efficient-python-code)
    * [Optimizing Python Code with pandas](https://www.datacamp.com/courses/optimizing-python-code-with-pandas)
    * [Writing Functions in Python](https://www.datacamp.com/courses/writing-functions-in-python)
    * [Object-Oriented Programming in Python](https://www.datacamp.com/courses/object-oriented-programming-in-python)
    * [Creating Robust Python Workflows](https://www.datacamp.com/courses/creating-robust-python-workflows)
    * [Software Engineering for Data Scientists in Python](https://www.datacamp.com/courses/software-engineering-for-data-scientists-in-python)
    * [Unit Testing for Data Science in Python](https://www.datacamp.com/courses/unit-testing-for-data-science-in-python)
4. [DataCamp: Career Track: Machine Learning Scientist with Python](https://www.datacamp.com/tracks/machine-learning-scientist-with-python)
    * [Supervised Learning with scikit-learn](https://www.datacamp.com/courses/supervised-learning-with-scikit-learn)
    * [Unsupervised Learning in Python](https://www.datacamp.com/courses/unsupervised-learning-in-python)
    * [Linear Classifiers in Python](https://www.datacamp.com/courses/linear-classifiers-in-python)
    * [Machine Learning with Tree-Based Models in Python](https://www.datacamp.com/courses/machine-learning-with-tree-based-models-in-python)
    * [Extreme Gradient Boosting with XGBoost](https://www.datacamp.com/courses/extreme-gradient-boosting-with-xgboost)
    * [Clustering Methods with SciPy](https://www.datacamp.com/courses/clustering-methods-with-scipy)
    * [Dimensionality Reduction in Python](https://www.datacamp.com/courses/dimensionality-reduction-in-python)
    * [Preprocessing for Machine Learning in Python](https://www.datacamp.com/courses/preprocessing-for-machine-learning-in-python)
    * [Machine Learning for Time Series Data in Python](https://www.datacamp.com/courses/machine-learning-for-time-series-data-in-python)
    * [Feature Engineering for Machine Learning in Python](https://www.datacamp.com/courses/feature-engineering-for-machine-learning-in-python)
    * [Model Validation in Python](https://www.datacamp.com/courses/model-validation-in-python)
    * [Introduction to Natural Language Processing in Python](https://www.datacamp.com/courses/natural-language-processing-fundamentals-in-python)
    * [Feature Engineering for NLP in Python](https://www.datacamp.com/courses/feature-engineering-for-nlp-in-python)
    * [Introduction to TensorFlow in Python](https://www.datacamp.com/courses/introduction-to-tensorflow-in-python)
    * [Introduction to Deep Learning in Python](https://www.datacamp.com/courses/deep-learning-in-python)
    * [Introduction to Deep Learning with Keras](https://www.datacamp.com/courses/deep-learning-with-keras-in-python)
    * [Advanced Deep Learning with Keras](https://www.datacamp.com/courses/advanced-deep-learning-with-keras-in-python)
    * [Image Processing in Python](https://www.datacamp.com/courses/image-processing-in-python)
    * [Image Processing with Keras in Python](https://www.datacamp.com/courses/convolutional-neural-networks-for-image-processing)
    * [Hyperparameter Tuning in Python](https://www.datacamp.com/courses/hyperparameter-tuning-in-python)
    * [Introduction to PySpark](https://www.datacamp.com/courses/introduction-to-pyspark)
    * [Machine Learning with PySpark](https://www.datacamp.com/courses/machine-learning-with-apache-spark)
    * [Winning a Kaggle Competition in Python](https://www.datacamp.com/courses/winning-a-kaggle-competition-in-python)
5. [Coursera: Specialization: Deep Learning, deeplearning.ai](https://www.coursera.org/specializations/deep-learning)</br>
*This series of courses will help you dive deeper into deep learning and neural networks. In my opinion, Tensorflow 1.x was a pretty confusing API. There are so many ways to do the same thing and just getting a model setup was a bit tedious. Tensorflow 2.x integrated another super popular neural network API, Keras, into its main code, and focused on using the much more elegant higher-level architecture building style that keras provides. Many of the early courses focused on neural networks will leverage Tensorflow 1.x and may show you some non-ideal styles of building models, however as you progress you'll start to leverage the keras-style of model definition, which will greatly simplify things.*
    * [Neural Networks and Deep Learning](https://www.coursera.org/learn/neural-networks-deep-learning?specialization=deep-learning)
    * [Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization](https://www.coursera.org/learn/deep-neural-network?specialization=deep-learning)
    * [Structuring Machine Learning Projects](https://www.coursera.org/learn/machine-learning-projects?specialization=deep-learning)
    * [Convolutional Neural Networks](https://www.coursera.org/learn/convolutional-neural-networks?specialization=deep-learning)
    * [Sequence Models](https://www.coursera.org/learn/nlp-sequence-models)
6. [Coursera: Specialization: Tensorflow in Practice, deeplearning.ai](https://www.coursera.org/specializations/tensorflow-in-practice#courses)
    * [Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning](https://www.coursera.org/learn/introduction-tensorflow)
    * [Convolutional Neural Networks in TensorFlow](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow)
    * [Natural Language Processing in TensorFlow](https://www.coursera.org/learn/natural-language-processing-tensorflow)
    * [Sequences, Time Series and Prediction](https://www.coursera.org/learn/tensorflow-sequences-time-series-and-prediction)
7. PLACEHOLDER
8. PLACEHOLDER
9. PLACEHOLDER
10. PLACEHOLDER
11. PLACEHOLDER
12. PLACEHOLDER
13. PLACEHOLDER
14. PLACEHOLDER
15. PLACEHOLDER
16. PLACEHOLDER
17. PLACEHOLDER
18. PLACEHOLDER
19. PLACEHOLDER
20. PLACEHOLDER
21. PLACHOLEDER
22. [iOS App Development with Swift Specialization](https://www.coursera.org/specializations/app-development)</br>
*So, you've done it! You can fetch data, clean it, run some feature engineering and model selection and save your best model. What's the next step? Deploying the model! There are many ways to deploy a model, however one of the most interesting/exciting ways to deploy the model would be to deploy it to an app. For this reason, we'll start by learning how to build general iOS Apps in Swift (this will also get you exposure to a new programming language), Then, in the next specialization, we'll learn how to use TensorFlow Lite to deploy pre-trained models to Java & Swift.*
    * Introduction To Swift Programming
    * iOS App Development Basics
    * App Design and Development for iOS
    * Build Your Own iOS App
23. [TensorFlow: Data and Deployment](https://www.coursera.org/specializations/tensorflow-data-and-deployment)
    * [Browser-based Models with TensorFlow.js](https://www.coursera.org/learn/browser-based-models-tensorflow)
    * [Device-based Models with TensorFlow Lite](https://www.coursera.org/learn/device-based-models-tensorflow)
    * [Data Pipelines with TensorFlow Data Services](https://www.coursera.org/learn/data-pipelines-tensorflow)
    * [Advanced Deployment Scenarios with TensorFlow](https://www.coursera.org/learn/advanced-deployment-scenarios-tensorflow)

## Guide to Kaggle
Below are the Kaggle projects/competitions I recommend taking. As with the MOOCs, they are roughly sorted in the order they should be completed. When working on Kaggle competitions, you should push your results to your public github. This will beef-up your github account while giving you practice of working with git and managing projects with models that may require large datasets and/or outputs large files that cannot be saved in git. Also, be sure to checkout the Notebooks published on each project page. Seeing how other data scientists/ML experts do exploratory data analysis, feature engineering, model selection, and more, is one of the key reasons why doing projects via Kaggle can be so effective as a learning technique.

1. [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Interview Prep. Questions
* [Five Data Science Interview Questions that you must be able to answer](https://towardsdatascience.com/five-data-science-interview-questions-that-you-must-be-able-to-answer-8f2ec53b409a)

