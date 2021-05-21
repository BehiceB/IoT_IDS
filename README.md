# IoT_IDS
## Summary
Internet of Things (IoT) can be thought of as a system that exchanges information between devices operating over the internet. IoT is a combination of several layers, including a complex network layer. The network layer is a vulnerable part of the IoT architecture, leading to various security issues. In order to use this architecture safely, it must be protected from various types of attacks and threats. Intrusion Detection Systems (IDS) are systems used to detect unauthorized interventions on network traffic. The traditional approach used in the security of IDS can only protect the system against previously known and defined attacks, but this approach is insufficient when it comes to attacks other than these. In cyberspace, it is more advantageous to use learning-based systems thanks to their ability to react very quickly to events, learn from historical data and solve problems ehven with missing data. Hece, Machine Learning and Artificial Intelligence technologies; It is critical for automated cyber defense techniques, including monitoring, control, threat detection and alarm systems. The speed, accuracy, efficiency, cost and scope aspects of intrusion detection methods on existing IOT networks need to be improved and developed. The dataset, feature selection methods and classification algorithms affect the success rate of intrusion detection systems.
## Dataset
Downloaded from - https://www.unb.ca/cic/datasets/ids-2017.html

CICIDS 2017 dataset consists of approximately 2.8 million traffic flow records. It is a data set containing 14 different attacks consisting of 5 days of records.

The 2 attack types with a small amount of data were removed and the remaining attacks were labelled on the basis of attack type.

## Methods

### Normalization

-Robust Normalization

-MinMax Normalization

-Maximum Absolute Normalization

-Standard Normalization

### Outlier Techniques

-Local Outlier Factor

-Isolation Forest

-Elliptic Envelope

### Sampling

-Random Over Sampling

-SMOTE

-Bootstrap

### Feature Selection

-Random Forest

-Linear Discriminant Analysis

### Classifiers

-Decision Tree

-Random Forest

-Naive Bayes

-Logistic Regression

## Hardwares on HPC
|                                            |
| --------------                             | 
| HPE 868703-B21 DL380 Gen10 85FF CTO Serv  | 
| HPE 733660-B21#0D1 2U SFF Easy Install R  | 
| HPE 815100-B21#0D1 32GB 2Rx4 PC4-1666V-R  | 
| HPE 826690-B21#0D1 DL38X Gen10 Premium B  | 
| HPE 804331-B21#0D1 Smart Array P408İ-a S  | 
| HPE 865414-B21#0D1 800W FS Plat Ht Plg L  | 
| HPE 826694-B21#0D1 DL38X Gen10 x16 x16 R  | 
| HPE 826882-L21 DL380 Gen10 6148 Xeon-G F  | 
| HPE 826882-B21#0D1 DL380 Gen10 6148 Xeon  |
| HPE P01366-B21# 0D1 96W Smart Storage Ba  |
| HPE 867810-B21#0D1 DL38X Gen10 High Perf  |
| HPE 871674-B21 DL38X Gen10 x16 x16 Riser  |
| HPE P04474-B21#0D1 480GB SATA RI SFF SC   |

## Experiment Results

| Accuracy       | Decision Tree    | Random Forest | Naive Bayes | Logistic Reggression |
| -------------- | :----------------: | :--------: 	| :--------:   | :--------: 			 |
| Random Forest  | 0.9995           |   0.9994  	| 0.6141      | 0.9029    			 |
| LDA            | 0.9992           |   0.9994  	| 0.8731      | 0.9070   			 |
| RF & LDA       | 0.9989           |   0.9993  	| 0.6182      | 0.7581    			 | 
