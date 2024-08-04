#Botnet Detection Using Machine Learning Algorithms

In this project, we utilize machine learning techniques to detect Botnet attacks. Leveraging the Bot-IoT and University of New South Wales (UNSW) datasets, we develop four machine learning models based on the Naive Bayes, K-Nearest Neighbor, Support Vector Machine, and Decision Trees classifiers. Among these, the Decision Trees model demonstrated the highest performance, achieving 98% testing accuracy, 94.2% precision, 95.9% recall, and 95.8% F-score when identifying botnet attacks using 82,000 records from the UNSW-NB15 dataset. We conducted our experiments on 10,000 data records, achieving an overall result of 98.63%.

#Introduction
Botnets pose a significant threat to cybersecurity, making it essential to develop effective detection mechanisms. This study focuses on using machine learning algorithms to accurately identify botnet activities.

#Datasets
We used two primary datasets:

#Bot-IoT: A comprehensive dataset for botnet activity detection.
UNSW-NB15: A dataset provided by the University of New South Wales, which includes various types of network traffic.
Machine Learning Models
We implemented and evaluated the following machine learning classifiers:

Naive Bayes
K-Nearest Neighbor (KNN)
Support Vector Machine (SVM)
Decision Trees
Results
Among the models tested, the Decision Trees classifier achieved the best results with the following metrics on the UNSW-NB15 dataset:

Testing Accuracy: 100%
Precision: 100%
Recall: 100%
F-Score: 100%
For our experiments on a subset of 10,000 data records, we attained an overall accuracy of 99.63%.

Conclusion
This study demonstrates the effectiveness of using machine learning algorithms, particularly Decision Trees, in detecting botnet attacks. The high accuracy and reliability of these models highlight their potential for real-world application in cybersecurity.

#How to Run the Project
Clone the repository.
Load the datasets into the appropriate directories.
Run the provided Jupyter notebooks or Python scripts to train and evaluate the models.
