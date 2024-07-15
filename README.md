
# K-Nearest Neighbors (KNN) Algorithm for Banknote Authentication

This repository contains a Jupyter notebook for implementing and demonstrating the K-Nearest Neighbors (KNN) algorithm to classify banknotes as authentic or forgery. The notebook includes steps for data preprocessing, model training, evaluation, and visualization of results.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

The goal of this project is to build and evaluate a K-Nearest Neighbors (KNN) classifier to predict whether a banknote is authentic or forgery based on its features. The notebook demonstrates the following steps:

1. Data Preprocessing
2. Exploratory Data Analysis (EDA)
3. Model Training using KNN from scratch and sklearn
4. Model Evaluation
5. Visualization of Results

## Dataset

The dataset used in this project is the Banknote Authentication dataset, which consists of the following features:

- Variance of Wavelet Transformed image (continuous)
- Skewness of Wavelet Transformed image (continuous)
- Curtosis of Wavelet Transformed image (continuous)
- Entropy of image (continuous)
- Class (integer: 0 for authentic, 1 for forgery)

## Installation

To run the notebook, you need to have Python and Jupyter installed. Additionally, you need to install the required libraries specified in the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/knn-algorithm-banknote-authentication.git
    cd knn-algorithm-banknote-authentication
    ```

2. Open the Jupyter notebook:
    ```bash
    jupyter notebook K\ Nearest\ Algo.ipynb
    ```

3. Run the cells in the notebook to preprocess the data, train the model, and evaluate the results.

## Results

The notebook evaluates the KNN model using various metrics such as accuracy, precision, recall, F1-score, and ROC AUC score. Additionally, it compares the performance of the KNN implementation from scratch with the implementation using sklearn's KNeighborsClassifier.

### E Output:

- **Accuracy Score (Scratch):** 0.986
- **Accuracy Score (Sklearn):** 0.993
- **Confusion Matrix (Scratch):**
  ```
  [[153,  2],
   [  1, 89]]
  ```

- **Performance Metrics:**
  ```
  - Precision: 0.978
  - Recall: 0.978
  - F1 Score: 0.978
  - Specificity: 0.993
  - Mean Absolute Error: 0.014
  - ROC Area: 0.986
  ```

### Visualization:

The notebook includes visualizations such as:
- Pair plot of the features colored by class
- Pie chart showing the distribution of authentic vs forgery banknotes
- Bar plots comparing accuracy of KNN from scratch and sklearn
- Confusion matrix heatmap
- Bar plot of various performance metrics

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
