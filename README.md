
A classification program to classify cover types in Colorado´s Roosevelt National Park

# Forest Cover Type Detector - Kaggle Competition 🌲🍂

![Forest Cover Type Detector](Roosevelt_National_Forest_Colorado.jpeg)



## Introduction 📚

This repository contains the code and analysis for the Kaggle competition, "Forest Cover Type Prediction." The competition focuses on solving a classification problem where the goal is to predict the predominant kind of tree cover (forest cover type) from cartographic variables, rather than remotely sensed data. The dataset includes 15120 observations in the training set, each representing a 30m x 30m patch in the Roosevelt National Forest of northern Colorado. The test set contains 565892 observations for which we need to predict the cover type.

![Forest Cover Type Detector](tree_types.png)

The forest cover types to predict are as follows:
1. Spruce/Fir
2. Lodgepole Pine
3. Ponderosa Pine
4. Cottonwood/Willow
5. Aspen
6. Douglas-fir
7. Krummholz

![Forest Cover Type Detector](satellite2.png)

## Data Analysis 📊

The repository contains an in-depth data analysis to understand the dataset better. It explores the data types, shape, and descriptive statistics of the features. The notebooks also explain the meaning and relevance of each variable, including wilderness area and soil type designations.

## Feature Engineering 🔧

Feature engineering is a crucial part of the data preprocessing process. The notebooks provide details about various feature engineering steps performed on the dataset. It covers outlier detection and treatment, feature transformations, and the creation of new features. Additionally, it discusses how soil types are grouped based on USFS ecological land type units and geological zones.

## Feature Selection ⛏️

To improve model performance and reduce overfitting, the repository includes feature selection techniques. It explains how different feature selection methods were employed, such as correlation analysis, filter methods, and recursive feature elimination. The selected features are used in subsequent model building.

## Model Building 🤖

The repository contains the code and evaluation of several machine learning algorithms for the forest cover type prediction task. The models used include:
- Decision Trees
- XGBoost
- Extra Tree Classifier
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes
- Logistic Regression
- Ensemble Methods

It provides details on how these models were implemented and their performance evaluation.

## Dimensionality Reduction 📉

In addition to feature selection, the repository explores dimensionality reduction techniques using PCA (Principal Component Analysis) and LDA (Linear Discriminant Analysis). The impact of dimensionality reduction on model performance is also discussed.

## Final Submission 🚀

It concludes with the final model used for prediction and instructions on how to make predictions on the test set. Additionally, it includes details on how to submit the predictions to the Kaggle competition.

Feel free to explore the code, analysis, and models provided in this repository. If you have any questions or suggestions, please don't hesitate to open an issue or reach out to the contributors.

## Authors 📚

 :tada:


<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/itayyoung"><img src="https://avatars.githubusercontent.com/u/108944195?v=4" width="100px;" alt="Itay Young"/><br /><sub><b>Itay Young</b></sub></a><br /><a href="https://github.com/codesandbox/codesandbox-client/commits?author=itayyoung" title="Data Analyst">📊</a></td>
    <td align="center"><a href="https://github.com/Callisthenes"><img src="https://avatars.githubusercontent.com/u/91435423?v=4" width="100px;" alt="Pedro Esteban"/><br /><sub><b>Pedro Esteban</b></sub></a><br /><a href="https://github.com/codesandbox/codesandbox-client/commits?author=callisthenes" title="Backend Developer">💻</a></td>
    <td align="center"><a href="https://github.com/steguess"><img src="https://avatars.githubusercontent.com/u/86976901?v=4" width="100px;" alt="Stephanie Gessler"/><br /><sub><b>Stephanie Gessler</b></sub></a><br /><a href="https://github.com/codesandbox/codesandbox-client/commits?author=steguess" title="Frontend Developer">💻</a></td>
    <td align="center"><a href="https://github.com/salmaelguendy"><img src="https://avatars.githubusercontent.com/u/108944312?v=4" width="100px;" alt="Salma Guendy"/><br /><sub><b>Salma Guendy</b></sub></a><br /><a href="https://github.com/codesandbox/codesandbox-client/commits?author=salmaelguendy" title="UI/UX Designer">🎨</a></td>
    <td align="center"><a href="https://github.com/conniekim"><img src="https://avatars.githubusercontent.com/u/16468772?v=4" width="100px;" alt="Connie Kim"/><br /><sub><b>Connie Kim</b></sub></a><br /><a href="https://github.com/codesandbox/codesandbox-client/commits?author=conniekim" title="Technical Writer">✍️</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->






---





