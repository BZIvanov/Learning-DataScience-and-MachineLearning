# Learning Machine learning and Data science

## Machine learning (ML)

Machine learning is a subset of artificial intelligence (AI) that focuses on the development of algorithms and statistical models that enable computers to learn and improve their performance on a specific task without being explicitly programmed. The core idea behind machine learning is to allow computers to learn from data and make predictions or decisions based on that learning.

### Types of ML

- **Supervised learning** - applied to labled dataset, the ML model predicts a value. Supervised learning algorithms can be further classified into regression and classification tasks:
  - Regression - In regression tasks, the algorithm predicts a continuous numeric value as the output. For example, predicting the price of a house based on its features
  - Classification - In classification tasks, the algorithm assigns input data points to predefined categories or classes. For example, classifying emails as spam or non-spam based on their content. Another example is to tell if the animal on a picture is dog or cat.
- **Unsupervised learning** - applied to unlabeled dataset, the ML model discovers possible patterns in the data. Unsupervised learning algorithms can be used for tasks such as:
  - Clustering
  - Dimensionality reduction
  - Anomaly detection
- **Reinforcement learning**- This type involves an agent interacting with an environment and learning through trial and error.

## Initial environments download

Google search for `anaconda download` and download the installer.
After Anaconda was installed, search for and open the `Anaconda Navigator`.

Anaconda contains all the tools we need (Python notebooks, usefull python librarires etc..)

## Working with Jupyter Notebooks

#### Opening notebooks folders

In Anaconda Navigator on the Home tab click Launch on the Jupyter Notebook card. It will open a directory with folders in the browser.

#### Starting a notebook

From the New dropdown select Python 3

#### Basic commands

- Ctrl + Enter - will execute the current cell
- Shift + Enter - will execute the current cell and go to the next cell

## Projects

- MovieRatings - this first project to start with after learning numpy, pandas, matplotlib and seaborn
- Heartbeat
- FoodProducts
- Countries
- Digits

## Table of content

- Manipulating and displaying data
  - Numpy - library
  - Pandas - library
  - Matplotlib - library
  - Seaborn - library
  - Project-MovieRatings - demo project
  - Data Normalization - preprocessing step
- Machine Learning
  - Supervised Learning
    - Gradient Descent - optimization algorithm
    - Linear Regression - model
    - Support Vector Regression - model
    - Feature Engineering - data preparation process
    - Cross Validation - performance technique
    - Logistic Regression - model
    - Project-Heartbeat - demo project
    - K Nearest Neighbors - model
    - Support Vector Machines - model
    - Decision Trees - model
    - Random Forest - model
    - Boosting models (Adaptive and Gradient Boosting) - model
  - Unsupervised Learning
    - Clustering Algorithms
      - K-means Clustering - model
      - Project-Countries - demo project
      - Hierarchial Clustering - model
      - DBSCAN - model
      - Project-FoodProducts - demo project
    - Dimensionality Reduction
      - Principal Component Analysis - model
      - Project-Digits - demo project
  - Reinforcement Learning - not included in this repository
- Natural Language Processing - application domain. Can be approached using both supervised and unsupervised learning techniques, depending on the nature of the problem
