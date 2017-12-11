Hands-On ML with Scikit-Learn and TensorFlow
---

Contains Jupyter Notebooks for Hands-On Machine Learning with Scikit-Learn and TensorFlow

#### Chapter 2 - End-To-End Machine Learning Project

Notebooks in `chapter2/`

1. [Exploring the Dataset.ipynb](Exploring\ the\ Dataset.ipynb)
    - Initial overlook of dataset, points out dirtyness of dataset
2. [Cleaning the Dataset.ipynb](Cleaning\ the\ Data.ipynb)
    - Contains code to identify outliers using a modified z-score method
    - Contains some initial transformation pipeline code, not used
3. [Stratified Sampling.ipynb](Stratified\ Sampling.ipynb)
    - Stratified sampling of train and test sets
4. [Prepare Training Data and Train.ipynb](Prepare\ Training\ Data\ and\ Train.ipynb)
    - Load the cleaned and stratified data
    - Build the transformation pipeline
    - Identify `RandomForestRegressor` as a good model
    - Perform `GridSearchCV` to identify best model
        - **Probably should have tried `RandomSearchCV` too**
    - Run the model on the test set

#### Chapter 3 - Classification

Notebooks in `chapter3/`

1. [MNIST Classification-Binary.ipynb](MNIST\ Classification-Binary.ipynb)
    - Binary Stochastic Gradient Descent (SGD) & Random Forest (RF) Classification
2. [MNIST Classification.ipynb](MNIST\ Classification.ipynb)
    - Multiclass Classification with SGD, RF, and One-Versus-One Classification
