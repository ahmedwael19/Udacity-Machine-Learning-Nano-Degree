# Udacity-Machine-Learning-Nano-Degree

This repo is a portofolio for all the assignments and projects that I have done throughout the 6-month Udacity Machine Learning Nano Degree.

## Table of content

- [Projects](#Projects)
  1. [Predicting Boston Housing Prices](#Predicting-Boston-Housing-Prices)
  2. [Finding Donors for Charity](#Finding-Donors-for-Charity)
  3. [Dog Breed Classifier](#Dog-Breed-Classifier)
  4. [Creating Customer Segments](#Creating-Customer-Segments)
  5. [Teach a Quadcopter How to Fly](#Teach-a-Quadcopter-How-to-Fly)

- [Capstone Project](#Capstone-Project)
    1.- [Definition](#Definition)
    2. - [Analysis](#Analysis)
    3. - [Methodology](#Methodology)
    4. - [Results](#Results)
    5. - [Conclusion](#Conclusion)
- [Mini Projects](#Mini-Projects)
    - [Upload the page tree file](#upload-the-page-tree-file)
    - [Go to the import view](#go-to-the-import-view)
    - [Import the uploaded page tree file](#import-the-uploaded-page-tree-file)
- [License](#license)
- [Links](#links)

## Projects:

### Predicting Boston Housing Prices
  In this project, I worked on Boston Housing [dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/), which consists of 506 entries representing 14 different features for houses in Boston. Decision Tree was used as regressor to predict the price of a house with a given features. The flow of the project was as following :
  1. Data Exploration  : Calculate Statistics and Observe the features
  2. Developing a Model :  Define a Performance Metric and check Goodness of Fit. 
  3. Analyzing Model Performance : Use simple and complex learning curves, and observe the bias-variance tradeoff
  4. Evaluating Model Performance:  Use Grid-Search and cross-validation
  5. Making Predictions : Test uing the test sub-dataset, and discuss the applicability of such application in real-life
  
### Finding Donors for Charity
  In this project, I worked on Charity Donors  [dataset](https://archive.ics.uci.edu/ml/datasets/Census+Income), which consists of 48842 entries representing 14 different features for people income. Different classifers were used to classify if a person is making more than 50,000 or not.The flow of the project was as following :
  1. Data Exploration : Calculate Statistics and Observe the features
  2. Preparing the Data : Transforming Skewed Continuous Features, Normalizing Numerical Features
  3. Evaluating Model Performance : Metrics and the Naive Predictor
  4. Supervised Learning Models:  Gaussian Naive Bayes (GaussianNB), Decision Trees, Ensemble Methods (Bagging, AdaBoost, Random Forest, Gradient Boosting), K-Nearest Neighbors (KNeighbors), Stochastic Gradient Descent Classifier (SGDC), Logistic Regression
  5. Initial Model Evaluation : Test uing the test sub-dataset
  6. Improving Results : Choosing the Best Model, Model Tuing
  7. Final Model Evaluation
  8. Feature Importance and Selection

### Dog Breed Classifier
  In this project, I developed a CNN model that can classify if a given image is dog, human, or neither. Moreover, if it a dog, it can classify to which breed it belongs (out of 133 breeds), and if it's a human, it can classify it to the most resembling dog breed. The flow of the project was as following :
  1. Import Datasets  : Import Dog Dataset, Import Human Dataset.
  2. Detect Humans :  Using openCV. 
  3. Detect Dogs : Pre-process the Data, and Making Predictions with ResNet-50
  4. Create a CNN to Classify Dog Breeds (from Scratch): Pre-process the Data, define Model Architecture, compile it, train it, and test it.
  5.Use a CNN to Classify Dog Breeds (Transfer Learning) : Obtain Bottleneck Features, and do the same steps as 4
  6. Hyperparamter tuning and testing
  
### Creating Customer Segments
  In this project, I worked on Wholesale customers [dataset](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers), which consists of 440 entries representing 8 different features for the annual spending in monetary units (m.u.) on diverse product categories. Different Clustring algorithms were used to clustera and segment the features.The flow of the project was as following :
  1. Data Exploration : Calculate Statistics and Observe the Feature Relevance by Visualizing Feature Distributions
  2. Data Preprocessing : Feature Scaling, Outlier Detection, Feature Transformation using PCA
  3. Creating Clusters: Cluster Visualization, and Data Recovery
  4. Visualizing Underlying Distributions
  
### Teach a Quadcopter How to Fly
  In This project, I used Deep Reinforcement Learning to teach a quadcopter how to fly and reach a specified target. Neural Networks were used in designing the action and the states. The project consists of the following main functions:
  * Agent
  * Actor
  * Critic
  * Noise
  * Policy Search
  * Replay Buffer
  * Final Task : which calls all the functions in other .py files and start training given the designed reward function.
  
  ## Capstone Project
  
  ### Definition
    1. Project Overview : Pneumonia is a widely known in lung infection that affect the air sacs. While not very acute if diagnosed in the early stages, it can be fatal if not. 
    2. Problem Statement: The goal is to create a machine learning model that has X-Ray image as inputand returns the class of it as an output, by being either normal or having pneumonia infection. The tasks involved are the following: 
      1. Download the dataset generically, by using a single command. The dataset is avaliable on [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
      2. Explore the dataset statistically and visually.
      3. Preprocess the dataset to remove any outliers (if any), resize all images, and link each image to its label
      4. Perform basic data augmentation to have more training examples (double the size).
      5. Use k-fold validation technique to decrease overfitting. 
      6. Train and test the dataset on a benchmark model.
      7. Experimenting with different models and fine-tuning.

