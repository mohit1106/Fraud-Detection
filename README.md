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

📁 Repo Structure:

data/ → Preprocessed financial transaction dataset
models/ → Trained fraud detection models
notebooks/ → Jupyter notebooks for training and evaluation
