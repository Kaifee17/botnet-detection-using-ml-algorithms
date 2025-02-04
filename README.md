# Botnet Detection Using Machine Learning Algorithms

In this project, we utilize machine learning techniques to detect Botnet attacks. Leveraging the Bot-IoT and University of New South Wales (UNSW) datasets, we develop five machine learning models based on the K-Nearest Neighbor (KNN) algorithm, Logistic Regression, Support Vector Machine (SVM), Random Forest, and Decision Trees classifiers. Additionally, we created a hybrid model combining Logistic Regression and Decision Trees. Among these, the Decision Trees model demonstrated the highest performance, achieving 99.5% testing accuracy, while the other models, including KNN, Logistic Regression, SVM, and Random Forest, achieved around 99.3% accuracy when identifying botnet attacks using 82,000 records from the UNSW-NB15 dataset. The hybrid model also performed competitively, achieving the same 99.5% accuracy but yielding better results in other metrics such as precision and recall. We conducted our experiments on 10,000 data records, achieving an overall result of 99.63%.

## Introduction

Botnets pose a significant threat to cybersecurity, making it essential to develop effective detection mechanisms. This study focuses on using machine learning algorithms to accurately identify botnet activities.

## Datasets

We used two primary datasets:

- **Bot-IoT**: A comprehensive dataset for botnet activity detection.
- **UNSW-NB15**: A dataset provided by the University of New South Wales, which includes various types of network traffic.

## Machine Learning Models

We implemented and evaluated the following machine learning classifiers:

- K-Nearest Neighbor (KNN)
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Decision Trees
- Hybrid Model (Logistic Regression + Decision Trees)

## Results

Among the models tested, the Decision Trees classifier achieved the best accuracy with the following metrics on the UNSW-NB15 dataset:

- **Testing Accuracy**: 99.5%
- **Precision**: 99.5%
- **Recall**: 99.5%
- **F-Score**: 99.5%

The hybrid model (Logistic Regression + Decision Trees) also achieved **99.5% accuracy** but demonstrated superior performance in **precision and recall** compared to the other models.

For our experiments on a subset of 10,000 data records, we attained an overall accuracy of 99.63%.

## Conclusion

This study demonstrates the effectiveness of using machine learning algorithms, particularly Decision Trees and the hybrid model, in detecting botnet attacks. The high accuracy and reliability of these models highlight their potential for real-world application in cybersecurity.

## How to Run the Project

1. Clone the repository.
2. Load the datasets into the appropriate directories.
3. Run the provided Jupyter notebooks or Python scripts to train and evaluate the models.


