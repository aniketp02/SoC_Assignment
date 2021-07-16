# SoC Final Submission

Hey, all!!

This repo contains links to all the content and the team solution to the tasks and also the code for my final project on Age Classification using OpenCV and RandomForest Classifier.

## [Topic: Tools for Data Science](https://github.com/Tools-For-Data-Science-SOC)

The project included tutorials introducing a ML topic each week and corresponding algorithms used and their implementations.
It also included 3 task, solutions to which were to be submitted in teams.

Thanks to Dev Desai for hosting this project.

- ### [Week1](https://github.com/Tools-For-Data-Science-SOC/reading-material/blob/main/Week1_numpy_pandas.ipynb)

Week 1 was a introduction to numpy and pandas libraries, and basic git and bash commands.

- ### [Week2](https://github.com/Tools-For-Data-Science-SOC/reading-material/blob/main/Week2_regression.ipynb)

Week 2 was about Linear Regression, it also included content regarding data pre-processing.

- ### [Week3](https://github.com/Tools-For-Data-Science-SOC/reading-material/blob/main/Week3_clustering.ipynb)

Week 3 introduced Clustering and K-means algorithm.

- ### [Week4](https://github.com/Tools-For-Data-Science-SOC/reading-material/blob/main/Week4_neuralNet.ipynb)

Week 4 introduced Neural Networks and its implementation using the Pytorch library.

## Task 1

Task 1 was a Linear Regression task.

- [Problem statement](https://github.com/Tools-For-Data-Science-SOC/tasks/blob/main/task1/task1-regression.pdf)
- [Solution](https://github.com/Tools-For-Data-Science-SOC/tasks/blob/main/task1/Team_Warrature/task1.ipynb)

## Task 2

To solve a classification task using Gaussian Naive Bayes algorithm.

- [Problem statement](https://github.com/Tools-For-Data-Science-SOC/tasks/blob/main/task2/task2-classification.pdf)
- [Solution](https://github.com/Tools-For-Data-Science-SOC/tasks/blob/main/task2/Pineapple_People/task2.ipynb)

## Task 3

Task 3 was based on Principle Component Analysis and implementing K-means Clustering.

- [Problem statement](https://github.com/Tools-For-Data-Science-SOC/tasks/blob/main/task3/task3-PCA.pdf)
- [Solution](https://github.com/Tools-For-Data-Science-SOC/tasks/blob/main/task3/Pineapple_People/task3.ipynb)

# Final Project

## Topic: Age Classification using OpenCV and RandomForest Classifier.

The final stage of SoC was to submit a project using the things learnt.

My project is about classifying a person in one of the 10 age brackets.<br>
It takes in input an image of 200x200 pixels and uses OpenCV to extract an array of 800 unique features from the image,<br>
which is then fed to a Random Forest Classifier to predict the age bucket of the given image.<br>
Further to improve the accuracy of the model on random dataset I used GridSearchCV to find the best hyperparameters.

The code can be found [here](https://github.com/aniketp02/SoC_Assignment/blob/main/Soc_final.ipynb)

One of the predictions of the model on a random web image<br>

![image](https://github.com/aniketp02/SoC_Assignment/blob/main/img1.jpg)

The model predicted the age bracket to be 37-45.(which seems pretty correct!!)
