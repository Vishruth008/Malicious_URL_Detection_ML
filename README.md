# Malicious URL Detection System Using Machine Learning and Deep Learning

## Overview

This project leverages the [Malicious URLs Dataset](https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset) from Kaggle to build a machine learning system capable of detecting malicious URLs. The system is designed to improve cybersecurity by identifying potentially harmful web links based on various features.

## Dataset

The dataset consists of labeled URLs categorized as either malicious or benign. It includes various features extracted from URLs, such as domain attributes, lexical analysis, and host-based information.

### Key Features:
- **URL**: The complete web address.
- **Label**: Classifies each URL as malicious (`1`) or benign (`0`).
- **Additional Attributes**: Features derived from URL structure, domain details, and other parameters to assist in classification.

### Size:
- Total records: Approximately 650,000 entries.

## Objectives

1. **Preprocess and clean the dataset**:
   - Handle missing values and outliers.
   - Normalize and encode features as needed for machine learning models.
2. **Train machine learning models**:
   - Apply algorithms such as XGBoost, LightGBM, and others.
   - Optimize hyperparameters for improved model performance.
3. **Evaluate model performance**:
   - Use metrics such as accuracy, precision, recall, and F1-score.
   - Analyze confusion matrices for detailed insights.

## Tools and Technologies

- **Languages**: Python
- **Libraries**:
  - **Data Preprocessing**: pandas, NumPy
  - **Visualization**: matplotlib, seaborn
  - **Machine Learning**: Scikit-learn, XGBoost, LightGBM
- **Development Tools**: Jupyter Notebook
- **Dataset Storage**: Kaggle

## Key Highlights

1. Achieved **95% detection accuracy** using gradient boosting algorithms.
2. Streamlined preprocessing of over **650,000 records** for feature engineering and model training.

## How to Use

1. Clone the repository and set up the environment:
   ```bash
   git clone <repository-link>
   cd malicious-url-detection
   pip install -r requirements.txt
   ```
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset) and place it in the `data` folder.
3. Run the preprocessing and model training scripts using:
   ```bash
   python preprocess.py
   python train_model.py
   ```

