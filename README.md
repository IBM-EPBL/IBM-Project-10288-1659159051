# IBM-Project-10288-1659159051
DemandEst - AI powered Food Demand Forecaster
A food delivery service has to deal with a lot of perishable raw materials which makes it all, the most important factor for such a company is to accurately forecast daily and weekly demand. Too much inventory in the warehouse means more risk of wastage, and not enough could lead to out-of-stocks - and push customers to seek solutions from your competitors. The replenishment of majority of raw materials is done on weekly basis and since the raw material is perishable, the procurement planning is of utmost importance, the task is to predict the demand for the next 10 weeks.

The main aim of this project is to create an appropriate machine learning model to forecast the number of orders to gather raw materials for next ten weeks. To achieve this, we should know the information about of fulfilment center like area, city etc., and meal information like category of food sub category of food price of the food or discount in particular week. By using this data, we can use any classification algorithm to forecast the quantity for 10 weeks. A web application is built which is integrated with the model built.
Technical Architecture:



In Order To Develop This Project, We Need To Install Following Software’s/Packages:
Anaconda Navigator:

Anaconda Navigator is a free and open-source distribution of the Python and R programming languages for data science and machine learning related applications. It can be installed on Windows, Linux, and macOS. Conda is an open-source, cross-platform, package management system. Anaconda comes with so very nice tools like JupyterLab, Jupyter Notebook, QtConsole, Spyder, Glueviz, Orange, Rstudio, Visual Studio Code. For this project, we will be using Jupyter notebook and Spyder

To Build Machine Learning Models You Must Require The Following Packages
Numpy:

 It is an open-source numerical Python library. It contains a multidimensional array and matrix data structures and can be used to perform mathematical operations

Pandas:

It is an open-source numerical Python library. It is mainly used for data manipulation.

Scikit-learn:

It is a free machine learning library for Python. It features various algorithms like support vector machine, random forests, and k-neighbours, and it also supports Python numerical and scientific libraries like NumPy and SciPy

Matplotlib and Seaborn:

Matplotlib is mainly deployed for basic plotting. Visualization using Matplotlib generally consists of bars, pies, lines, scatter plots and so on. Seaborn: Seaborn, on the other hand, provides a variety of visualization patterns. It uses fewer syntax and has easily interesting default themes.

Flask: 

Web framework used for building Web applications


If you are using anaconda navigator, follow below steps to download required packages:

Open anaconda prompt.

Type “pip install jupyter notebook” and click enter.

Type “pip install spyder” and click enter.

Type “pip install numpy” and click enter.

Type “pip install pandas” and click enter.

Type “pip install matplotlib” and click enter.

Type “pip install seaborn” and click enter.

Type “pip install sklearn” and click enter.

Type “pip install Flask” and click enter.

If you are using Pycharm IDE, you can install the packages through the command prompt and follow the same syntax as above.

Prior Knowledge
One should have knowledge of the following Concepts:
Supervised and Unsupervised Learning
Linear Regression
Decision Tree
Flask

Project Objectives
By the end of this project:

You’ll be able to understand the problem to classify if it is a regression or a classification kind of problem.

You will be able to know how to pre-process / clean the data using different data pre-processing techniques.

You will able to analyze or get insights of data through visualization.

Applying different algorithms according to dataset and based on visualization.

You will able to know how to find accuracy of the model.

You will be able to know how to build a web application using Flask framework.

Project Flow
The user interacts with the UI (User Interface) to upload the input features.

Uploaded features/input is analyzed by the model which is integrated.

Once the model analyses the uploaded inputs, the prediction is showcased on the UI.

To accomplish this, we have to complete all the activities and tasks listed below

Project Structure
Create a Project folder which contains files as shown below



We have three folders dataset, Flask and training.

A python file called app.py for server side scipting.

We need the model which is saved and the saved model in this content is fdemand.pkl

Templates folder which contains home.html and upload.html files.

Static folder which contains css folder which contains styles.css.

