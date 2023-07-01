# Fraud Transaction Detection

This project focuses on detecting fraudulent transactions using various machine learning algorithms. The dataset consists of transaction data with labeled fraudulent and non-fraudulent transactions.

## Algorithms Used

The following machine learning algorithms were employed in this project:

1. CatBoost: An ensemble method that utilizes gradient boosting on decision trees. It is known for its robustness and ability to handle categorical features effectively.

2. XGBoost: Another ensemble method based on gradient boosting. It is widely used for its efficiency, scalability, and high performance.

3. SVM (Support Vector Machine): A conventional method that aims to find a hyperplane to separate different classes. It is particularly useful for binary classification tasks.

4. KNN (K-Nearest Neighbors): A conventional method that classifies data points based on the majority class of their neighboring points. It is simple yet effective for both classification and regression tasks.

5. Decision Tree: A conventional method that creates a tree-like model to make decisions. It is intuitive and interpretable, suitable for binary classification tasks.

## Dataset

To access the dataset, please follow these steps:

1. Go to the [Synthetic Financial Datasets](https://www.kaggle.com/code/imranp/starter-synthetic-financial-datasets-cd6449a6-6) Kaggle page.
2. Download the dataset by clicking on the "Download" button on the right-hand side of the page.
3. Upload the downloaded dataset to your Google Drive or any other accessible location.

## Colab Notebooks

The project includes the following Colab notebooks, each representing a different solution:

1. `Final_21522380_NguyenDuyNgoc_Boost.ipynb`: This notebook implements the CatBoost and XGBoost algorithms for fraud transaction detection.

2. `Final_21522284_BuiLeKhanhLinh_Tree.ipynb`: This notebook utilizes the Decision Tree algorithm for fraud transaction detection.

3. `Final_21521065_NguyenThiThanhLan_KNN.ipynb`: In this notebook, the K-Nearest Neighbors (KNN) algorithm is implemented for fraud transaction detection.

4. `Final_21522635_LeQuangThinh_SVM.ipynb`: This notebook applies the Support Vector Machine (SVM) algorithm for fraud transaction detection.

Each notebook focuses on a specific algorithm and provides the necessary code to preprocess the dataset, train the model, and evaluate its performance.

## Usage

To run the notebooks, please follow these steps:

1. Upload the dataset to a location accessible by the Colab notebooks.
2. Open each Colab notebook in Google Colab or any other compatible environment.
3. Adjust the file paths and configurations according to your setup.
4. Execute the cells in the notebooks sequentially to run the code and observe the outputs.
5. Feel free to modify the code, experiment with different parameters, or add additional analyses as needed.
