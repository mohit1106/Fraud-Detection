# Fraud-Detection-in-Financial-Transactions
an anomaly detection system on 284,807 transactions, achieving an AUC of ~0.972 with CNNs and Autoencoders.


🔍 Detecting fraudulent transactions using anomaly detection models


# Abstract
Anomaly detection for financial transactions is used to detect fraud, secure sensitive data, and gain higher transaction processing system efficiency. In this paper, a broad analysis of different machine learning methods for fraud detection is studied along with their unsupervised learning techniques. This article breaks down the application of Isolation Forest, Local Outlier Factor (LOF), Autoencoders, and Convolutional Neural Networks (CNNs) to financial datasets for anomaly detection. We compare these models against others, for which we calculate AUC, Silhouette Score, Davies-Bouldin Index, and Precision-Recall scores on our data. The outcomes show that the deep learning algorithms in Autoencoder and CNNs are far more accurate and resilient than the traditional models for abnormality detection. The results are critical for developing more advanced, effective, and efficient fraud detection systems in the financial domain.

 
# 🚀 Key Features:

Developed an anomaly detection system on 284,807 transactions, achieving an AUC of ~0.972 with CNNs and Autoencoders.
Applied oversampling, undersampling, and class-weight adjustments, improving fraud detection precision by 15%.
Optimized hyperparameters via grid search, reducing false positives by 18% and enhancing fraud detection efficiency.
🛠 Tech Stack: Python, TensorFlow, Keras, Scikit-Learn, Isolation Forest, LOF, Autoencoders, CNNs, PCA

# Problem Statement
The rapid rise of digital payments and, therefore, sophistication in online financial transactions have perpetuated an exponential growth in fraud concerning such transactions. Therefore, fraud detection in such transactions has become one of the most important jobs for any financial institution or regulatory body. Most fraudulent transactions exhibit minimal deviations from normal behavior; hence, this cannot be picked up through conventional rule-based detection systems. This provides a huge challenge to the integrity and security of financial systems. Also, the volume and intricacy of the financial data have made it increasingly insurmountable for human analysts to monitor transactions manually.[7] The necessity, therefore, lies in automated real-time or at-scale systems that can detect anomalies. Real-time fraud detection is of essence to minimize economic losses made by fraud transactions and retain users’ confidence in the use of the financial system. Typically, rule-based systems are worse at catching novel and unseen patterns for fraud. As these fraudsters change their tactics all the time[8], anomaly detection methods need to be devised that could pin down the earlier unseen fraud. This problem is even more challenging when the dataset is large, since the mere volume of data increases both computational complexity and the possibility for missed detections. Advanced machine learning techniques, therefore, should be applied—those which process large datasets with high accuracy in fraud detection and low false positives. This paper solves the problem of fraudulent transaction detection by using unsupervised machine learning techniques. We will go through how methods such as Isolation Forest, Local Outlier Factor, Autoencoders, and Convolutional Neural Networks can be used to detect anomalous patterns in financial data when labeled fraud data is unavailable. These techniques have achieved good performance in domains where data is ample, while labeled instances are few or even not available. The main focus of this research is the evaluation performance of these models on certain evaluation metrics, including AUC[7], Silhouette Score, and Davies-Bouldin Index, to see how well the identification of fraud could be identified correctly in real-world datasets


# 📁 Repo Structure:

data/ → Preprocessed financial transaction dataset
models/ → Trained fraud detection models
notebooks/ → Jupyter notebooks for training and evaluation
