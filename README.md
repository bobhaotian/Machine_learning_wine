# Machine_learning_wine
## Table of contents

- [Table of contents](#table-of-contents)
- [Introduction](#introduction)
- [Steps](#steps)
  - [Load Data](#load-data)
  - [Data visualization](#data-visualization)
  - [Data Preperation](#data-preperation)
  - [Model Building](#model-building)
## Introduction
The project is to discover which algorithm should be used to fit the dataset by noticing the accuracy.
This time, we use the dataset that contains qualities of wine, and predict the quality by using Linear Regression, Random Forrest, and RForestClassifier.

<p align="center">
  <img src="https://www.winemag.com/wp-content/uploads/2021/10/HERO_Strcutural_Elements_of-Wine_GettyImages-1233242907_1920x1280.jpg" alt="Structural Elements of Wine" width="50%">
</p>

We followed the platform Kaggle provides, [wine quality prediction](https://www.kaggle.com/code/ankitakumar/linear-regression-using-wine-quality-dataset), with using three different algorithms to learn about the correlation between type of dataset and algorithms.

## Steps
### Load Data💻
Import panda
(Experienced a tiny problem when reading the csv file. Every time we refresh it, the file we imported is gone. Solved by conncecting with google drive)
### Data Visualization
Data Visualization provides tremendous help for determining which algorithm we can use to predict the data.
<p align="center">
  <img src="https://user-images.githubusercontent.com/112147566/235041473-7e826aba-c7ea-4644-b209-7e0778d1dd25.png" alt="Structural Elements of Wine" width="50%">
</p>

Ex. we can find the correlation between each factor. If they all have strong connections, then Linear Regression might be a good choice.
### Data Preperation
Splitting the data into X and Y sections, where Y is the part we predicts. 
An essential step is setting the size of X and Y. The test size can affect the accuracy. In this case, we tested with 0.2 and 0.12, whcih gives us different results (0.72 vs. 0.76). 
### Model Building
We chose three different main predition algorithms. 
The RForestClassifier gives the most accurate prediction.
That says, since the 10 'x' factors are not related linearly strictly, LinearRegression is not the best algorithm.

