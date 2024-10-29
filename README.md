# CLIMATE 405: Machine Learning for Earth and Environmental Sciences (University of Michigan, Fall 2024)
Lecture materials for University of Michigan CLIMATE405: Machine Learning for Earth and Environmental Sciences (Fall 2024)
- Dr. Mohammed Ombadi (Email: ombadi@umich.edu)
- For any questions regarding this material, please contact Dr. Ombadi. Do not distribute any of the material in this repository before obtaining permission. 

## Basic Description
This course aims to introduce students (primarily of Earth and Enviromental Sciences background) to data-driven methods, ranging in complexity from autoregression to machine learning models. The course covers the basic theory behind machine learning and provides hands-on experience in building machine learning models. Students will learn to apply these models for both prediction and hypothesis formulation purposes. The methods will be taught through example applications in environmental sciences, with a specific focus on climate and hydrologic applications. Examples include short-term forecasts of temperature and precipitation, streamflow forecasting in selected hydrologic basins, understanding the relative contributions of temperature and precipitation in snowmelt trends, regional clustering of precipitation patterns and trends, and climatic teleconnections in regulating regional precipitation patterns.

- The Canvas coursespace can be accessed [here](https://umich.instructure.com/courses/710364)
- The course syllabus is available [here](https://clasp.engin.umich.edu/wp-content/uploads/sites/6/2024/02/Syllabus_Machine-Learning-in-Environmental-Sciences.pdf)

## Contents of this repository 
This repository contains the following content:

### Lecture Slides 
Each lecture slides are provided in a separate folder. The slides are provided both as a Jupyter Notebook and HTML. The HTML version can be downloaded or viewed directly via your web browser without the need to install any software or download additional files. In order to run the live Jupyter notebooks, you can download the folder in your local machine, and then execute the code (requires installing Jupyter Notebooks in your machine; _see Notes section for more information_). 

- **Lecture 0**: [Introduction to Class](slides/Lec_0/Lec0_climate405.ipynb)
- **Lecture 1**: [Stochastic and Deterministic systems; Random Variables; Review of Basic Statistics](slides/Lec_01/Lec1_climate405.ipynb)
- **Lecture 2**: [Probability Distributions; Model Evaluation Metrics](slides/Lec_02/Lec2_climate405.ipynb)
- **Lecture 3**: [Statistical Dependence, Hypothesis Testing and Statistical Significance](slides/Lec_03/Lec3_climate405.ipynb)
- **Lecture 4**: [Feature Selection, Dimensionality Reduction](slides/Lec_04/Lec4_climate405.ipynb)
- **Lecture 5**: [Supervised vs Unsupervised Learning, K-means Clustering](slides/Lec_05/Lec5_climate405.ipynb)
- **Lecture 6**: [Hierarchical and Density-based Clustering Algorithms; Examples of Clustering in EES](slides/Lec_06/Lec6_climate405.ipynb)
- **Lecture 7**: [Simple Linear Regression; Mutilple Linear Regression; Goodness of Fit](slides/Lec_07/Lec7_climate405.ipynb)
- **Lecture 8**: [Choice of Loss Function; Regularization (Ridge and Lasso Regression)](slides/Lec_08/Lec8_climate405.ipynb)
- **Lecture 9**: [Gradient Descent; The Anatomy of a Neural Network](slides/Lec_09/Lec9_climate405.ipynb)
- **Lecture 10**: [Multilayer Perceptron: Applications in Hydrology; Activation Functions](slides/Lec_10/Lec10_climate405.ipynb)
- **Lecture 11**: Hands-on Session
- **Lecture 12**: [Decision Trees](slides/Lec_12/Lec12_climate405.ipynb)
- **Lecture 13**: [Interpretability of Decision Trees, Feature Importance, Shapley Values](slides/Lec_13/Lec13_climate405.ipynb)
- **Lecture 14**: [Recurrent Neural Networks](slides/Lec_14/Lec14_climate405.ipynb)
- [Guest Lecture: LSTM Applications in Hydrology](https://github.com/PeishiJiang/Guest-Lecture-CLIMATE405-UMich)
- **Lecture 15**: [RNNs continued; Techniques used in training ML Models](slides/Lec_15/Lec15_climate405.ipynb)
- **Lecture 16**: Long-short Term Memory (LSTM) Networks
- **Lecture 17**: Convolutional Neural Networks (CNNs)
- **Lecture 18**: Applications of CNNs in Earth and Environmental Sciences



### Homework Assignments
Homework assignments will be posted here on Wednesdays. See lecture notes for more information on homework policy.
- Homework 1 [here](https://github.com/mombadi/umich-climate405/blob/b0dc8f3b3c7260d0da90e15eb2e7fef6a469026e/hw-assignments/Homework%201.pdf)





### Notes
- How to install Jupyter Notebook for _Mac_ [here](https://www.geeksforgeeks.org/how-to-install-jupyter-notebook-on-macos/)
- How to install Jupyter Notebook for _Windows_ [here](https://www.codecademy.com/article/setting-up-jupyter-notebook)
- Basics of GitHub [here](https://docs.github.com/en/get-started/start-your-journey/hello-world)

## Requirements 
We will be using Python3, mainly working with the following packages:
- numpy
- scipy
- pandas
- statistics
- matplotlib
- sickit-learn
- tensorflow (with keras)

Other packages will be used depending on the topics covered in each class. At the top of each Jupyter Notebook, you will find the required pacakages to execute the code under the heading "Import Libraries"

