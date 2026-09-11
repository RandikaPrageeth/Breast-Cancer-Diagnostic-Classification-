# Breast-Cancer-Diagnostic-Classification-
 ## 📌 Project Title

 
Breast Cancer Classifier

---------------------------------------------------------------------------------------------------------


## 🎯 Project Objective

Binary classification of cell nuclei features to predict whether a mass is malignant or benign.


---------------------------------------------------------------------------------------------------------



 ## 📌 Overview




This project is a PyTorch-based neural network that looks at cell measurement data from breast tissue samples and predicts whether a mass is malignant or benign.

It can build a clear, end-to-end pipeline that takes raw clinical features—like cell size, texture, and shape—and turns them into a reliable, easy-to-understand diagnostic result.



By using a deep learning model with proper scaling and evaluation metrics, this tool gives clear probability scores and helps track critical diagnostic errors, making medical AI easier to learn from and build upon.




----------------------------------------------------------------------------------------------------------------------

## 🛠️ Tech Stack
- **Framework:** PyTorch (`torch.nn`, `DataLoader`, `TensorDataset`)
- **Data Analysis & Visualization:** Pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning Utilities:** Scikit-Learn (StandardScaler, metrics, train_test_split)



----------------------------------------------------------------------------------------------------------------------

## 🏗️ Neural Network Architecture
The PyTorch model consists of a 3-layer Dense Neural Network with regularization:
- **Input Layer:** 30 continuous features
- **Hidden Layer 1:** 64 units + Batch Normalization + ReLU + Dropout (0.3)
- **Hidden Layer 2:** 32 units + Batch Normalization + ReLU + Dropout (0.2)
- **Output Layer:** 1 unit (Linear logit for `BCEWithLogitsLoss`)






 
