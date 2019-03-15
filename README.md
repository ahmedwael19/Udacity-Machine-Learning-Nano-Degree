# Udacity Machine Learning Nano Degree

This repo is a portofolio for all the projects, mini-projects, and the capstone project that I have done throughout the 6-month Udacity Machine Learning Nano Degree journy.
![](https://github.com/ahmedwael19/Udacity-Machine-Learning-Nano-Degree/blob/master/Certificate%20of%20Completion.JPG)

## Table of content
- [Capstone Project](#Capstone-Project)
- [Projects](#Projects)
  1. [Predicting Boston Housing Prices](#Predicting-Boston-Housing-Prices)
  2. [Finding Donors for Charity](#Finding-Donors-for-Charity)
  3. [Dog Breed Classifier](#Dog-Breed-Classifier)
  4. [Creating Customer Segments](#Creating-Customer-Segments)
  5. [Teach a Quadcopter How to Fly](#Teach-a-Quadcopter-How-to-Fly)
- [Mini Projects](#Mini-Projects)
    - [Method Validation](#Method-Validation)
    - [Supervised Learning](#Supervised-Learning)
    - [Deep Learning](#Deep-Learning)
    - [Unsupervised Learning](#Unsupervised-Learning)
    - [Reinforcement Learning](#Reinforcement-Learning)

- [License](#license)
- [Links](#links)

  
## Capstone Project
 For the capstone project, I worked on the Chest X-Ray images dataset available on [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia). I reached a recall of ** **96.8%** ** which beats all the scores on Kaggle, except for the top one with a recall of 98%.
You can find all the information in the [Project Report](https://github.com/ahmedwael19/Udacity-Machine-Learning-Nano-Degree/blob/master/Capstone%20Project/MLND%20cap%20project.pdf) for the project.
 
P.S. It is very interesting :open_mouth: . 
## Projects:

### Predicting Boston Housing Prices
  In this project, I worked on Boston Housing [dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/), which consists of 506 entries representing 14 different features for houses in Boston. Decision Tree was used as a regressor to predict the price of a house with a given feature. The flow of the project was as follows:
  1. Data Exploration: Calculate Statistics and Observe the features
  2. Developing a Model: Define a Performance Metric and check the Goodness of Fit. 
  3. Analyzing Model Performance: Use simple and complex learning curves, and observe the bias-variance tradeoff
  4. Evaluating Model Performance:  Use Grid-Search and cross-validation
  5. Making Predictions: Test using the test sub-dataset, and discuss the applicability of such application in real-life
  
### Finding Donors for Charity
  In this project, I worked on Charity Donors  [dataset](https://archive.ics.uci.edu/ml/datasets/Census+Income), which consists of 48842 entries representing 14 different features for people income. Different classifiers were used to classify if a person is making more than 50,000 or not. The flow of the project was as follows:
  1. Data Exploration: Calculate Statistics and Observe the features
  2. Preparing the Data: Transforming Skewed Continuous Features, Normalizing Numerical Features
  3. Evaluating Model Performance: Metrics and the Naive Predictor
  4. Supervised Learning Models:  Gaussian Naive Bayes (GaussianNB), Decision Trees, Ensemble Methods (Bagging, AdaBoost, Random Forest, Gradient Boosting), K-Nearest Neighbors (Kneighbors), Stochastic Gradient Descent Classifier (SGDC), Logistic Regression
  5. Initial Model Evaluation: Test using the test sub-dataset
  6. Improving Results: Choosing the Best Model, Model Tuning
  7. Final Model Evaluation
  8. Feature Importance and Selection

### Dog Breed Classifier
  In this project, I developed a CNN model that can classify if a given image is a dog, human, or neither. Moreover, if it a dog, it can classify to which breed it belongs (out of 133 breeds), and if it's a human, it can classify it to the most resembling dog breed. The flow of the project was as follows:
  1. Import Datasets: Import Dog Dataset, Import Human Dataset.
  2. Detect Humans: Using OpenCV. 
  3. Detect Dogs: Pre-process the Data, and Making Predictions with ResNet-50
  4. Create a CNN to Classify Dog Breeds (from Scratch): Pre-process the Data, define Model Architecture, compile it, train it, and test it.
  5. Use a CNN to Classify Dog Breeds (Transfer Learning): Obtain Bottleneck Features, and do the same steps as 4
  6. Hyperparameter tuning and testing
  
### Creating Customer Segments
  In this project, I worked on Wholesale customers [dataset](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers), which consists of 440 entries representing 8 different features for the annual spending in monetary units (m.u.) on diverse product categories. Different Clustering algorithms were used to cluster and segment the features. The flow of the project was as follows:
  1. Data Exploration: Calculate Statistics and Observe the Feature Relevance by Visualizing Feature Distributions
  2. Data Preprocessing: Feature Scaling, Outlier Detection, Feature Transformation using PCA
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
  * Final Task: which calls all the functions in other .py files and start training given the designed reward function.

 ## Mini Projects
  
 ### Method Validation
   * Grid Search

 ### Supervised Learning
 * Decision Trees Titanic
 * Spam Classifier
 ### Deep Learning
 * Gradient Descent
 * IMDB data in Keras 
 * Student Admissions in Keras 
 ### Unsupervised Learning
 * k-means Clustering of Movie Ratings 
 * DBSCAN
 * GMM Clustering and Cluster Validation 
 * Hierarchical Clustering 
 * PCA Mini Project 
### Reinforcement Learning
* Dynamic Programming
* Monto Carlo
* Temporal Difference
* Deep Q-Learning
