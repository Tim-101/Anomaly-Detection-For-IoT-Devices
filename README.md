# Anomaly Detection For IoT Devices
This project is part of my capstone project at The University of Sydney.
The repo has three folders: Dimensionality Reduction, Clustering and Anomaly Detection.

This project performed anomaly detection on a cluster of IoT devices. 
Hence, it has slightly lower accuracy and recall rate compared to other models used on this dataset.

Models used in this projects include:
1. PCA and Autoencoders to reduce the dataset dimensionality from 200 features to 20 features
2. tSNE to visualise dimensionality reduction result
3. K-means and GMM to cluster the IoT devices
4. One Class SVM and Autoencoder to detect anomalies

The model also works on this order.

Overall, we managed to achieve roughly 99% accuracy accross all IoT clusters. Additionally, we found that 
it was possible to use the model to detect anomalies on out of sample IoT devices given certain conditions were satisfied.
This include: less complex or exactly the same features and older version device.

# Dataset
The data used as part of this project can be downloaded from: http://archive.ics.uci.edu/ml/datasets/detection_of_IoT_botnet_attacks_N_BaIoT

More information regarding the dataset can be found here:<br />
Y. Meidan, M. Bohadana, Y. Mathov, Y. Mirsky, D. Breitenbacher, A. Shabtai, and Y. Elovici 'N-BaIoT: Network-based Detection of IoT Botnet Attacks Using Deep Autoencoders', IEEE Pervasive Computing, Special Issue - Securing the IoT (July/Sep 201

# Feature Extraction
For feature extraction the author used the following algorithm:<br />
Y. Mirsky, T. Doitshman, Y. Elovici & A. Shabtai, 'Kitsune: An Ensemble of Autoencoders for Online Network Intrusion Detection', in Network and Distributed System Security (NDSS) Symposium, San Diego (2018), CA, USA.
