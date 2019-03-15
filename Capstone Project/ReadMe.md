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
3. Metrics : Recall were the most important metric for me as False positives is what matter the most here. However, accuracy was also monitored.

  ### Analysis
1. Data Exploration :The dataset consists of 5,856 labeled images. The images vary in size and the number of pixels, which can be a huge problem for the CNN model. Also, while the dataset contains a fair number of images to train the model, the dataset split is very unbalanced. The number of infected or sick patients is triple the number of normal healthy people.

1. Exploratory Visualization : The bar plot below shows how the classes are distrusted among the images. This
clearly agrees with the unbalancing issues that was discussed in the previous section ![](https://github.com/ahmedwael19/Udacity-Machine-Learning-Nano-Degree/blob/master/Capstone%20Project/2.JPG)


1. Algorithms and Techniques
