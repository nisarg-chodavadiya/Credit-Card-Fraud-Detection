# Credit-Card-Fraud-Detection
**Problem Statement: Detect Credit Card Fraud from transaction data.**
* Data Source: https://www.kaggle.com/mlg-ulb/creditcardfraud
* This is a good example of the shared dataset, which is created from an original dataset that has privacy issues so this dataset has masked, transformed, PCA features or information. 
* As all features are already transformed, any domain-specific thing can not be analyzed through this dataset.
* It is a highly imbalanced dataset for classification problems that require special class imbalance learning strategies. 

# Approch
For class imbalance treatment, the Random Under-Sampling technique was used.

**This correlations are before the under sampliing**
![image](https://user-images.githubusercontent.com/75474944/137634882-0b549887-6ed9-4720-91ab-4384349ef8d1.png)
**This correlations are after the under sampliing**
![image](https://user-images.githubusercontent.com/75474944/137634957-9f72a1dd-55e2-4035-88bc-b99fbb16cdfd.png)
**Geometry also looks good after the under sampliing**
![image](https://user-images.githubusercontent.com/75474944/137634973-37a42e4f-38c7-40b1-a115-4151982044e8.png)

# Result (AUC-ROC)
![image](https://user-images.githubusercontent.com/75474944/137635001-20cd4e54-1f59-4c41-a14c-f122beec3610.png)


