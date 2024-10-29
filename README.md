# intrusion-detection-system
Leveraged machine learning techniques to develop a robust Intrusion Detection System (IDS) capable of accurately distinguishing between malicious and legitimate network traffic. By applying feature extraction on the KDD Cup 1999 dataset, I constructed a predictive model that effectively identifies potential security threats. 
# Dataset used
https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html

#  Dataset
KDD Cup 1999 (DARPA): A benchmark dataset for IDS projects, containing a variety of network connections labeled as either normal or attack.
Data Characteristics: Includes features such as protocol type, service, flag, and traffic statistics, which are used for identifying anomalies and attack patterns.

# Objectives
Develop a Classifier: Create a model that accurately distinguishes between legitimate and malicious connections.

Feature Engineering: Apply feature extraction and selection techniques to optimize the dataset and improve classification accuracy.

Algorithm Comparison: Evaluated multiple machine learning algorithms to identify the most effective model for intrusion detection.

# 🛠️ Implementation
Data Preprocessing:

Handled missing values, normalized data, and applied necessary data transformations.

Feature Selection: Used techniques like correlation analysis, PCA, or mutual information to identify the most impactful features.

Model Training and Testing:

Trained various machine learning algorithms, including Decision Trees, Random Forest, SVM, and Neural Networks.
Split the data into training and testing sets for validation and comparison.
Optimized hyperparameters to improve accuracy, precision, and recall.

Performance Metrics:

Evaluated models based on key metrics: accuracy, precision, recall, F1-score, and time efficiency.
Selected the best-performing model for final deployment.

# ⚙️ Technologies Used
Programming Language: Python

Libraries: Scikit-Learn, Pandas, Numpy, Matplotlib

Platform: google colab (for prototyping and testing)

# 📈 Results
Models Performance: 
![image](https://github.com/user-attachments/assets/9bbb1be8-0d09-4bb2-a47c-2460d86b1b26)
![image](https://github.com/user-attachments/assets/28ae9432-b40a-4c6d-a7b2-6f114916aef0)
![image](https://github.com/user-attachments/assets/8b2f8eab-66d7-4ce2-a150-74b8ceb7abdb)
![image](https://github.com/user-attachments/assets/34c2d776-1d66-42b1-8e8c-a8bdb76a4a29)
![image](https://github.com/user-attachments/assets/9897d019-e56f-4532-b757-903994f06260)




