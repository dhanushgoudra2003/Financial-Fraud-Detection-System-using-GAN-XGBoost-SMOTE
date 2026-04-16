# Financial Fraud Detection System Using GAN, XGBoost & SMOTE

## Project Overview
This project aims to create a novel financial fraud detection system that leverages Generative Adversarial Networks (GANs), XGBoost, and the SMOTE (Synthetic Minority Over-sampling Technique) algorithm. By synthesizing new examples and effectively classifying transactions, we enhance the detection capabilities while minimizing false positives.

## Objectives
- Develop a robust financial fraud detection system using state-of-the-art machine learning techniques.
- Evaluate the performance of GANs in generating synthetic data for training.
- Implement XGBoost for effective classification of financial transactions.
- Assess the impact of SMOTE in improving detection rates of minority class instances (fraudulent transactions).

## Architecture
The architecture of the system comprises three major components:
1. **Data Preprocessing**: Clean and prepare the dataset for modeling, including handling missing values and scaling features.
2. **GAN Implementation**: Utilize GANs to generate synthetic fraudulent transactions to balance the dataset.
3. **XGBoost Classification**: Train an XGBoost classifier on the original and synthetic data to predict fraudulent activities.

## Methods
- **Data Preprocessing**: This involves scaling numerical features and encoding categorical variables.
- **Generative Adversarial Networks (GANs)**: These networks consist of two models, a generator that creates synthetic instances and a discriminator that evaluates their authenticity.
- **XGBoost**: A powerful gradient boosting framework that integrates various techniques to optimize classification tasks.
- **SMOTE**: An oversampling technique that helps in countering class imbalance by creating synthetic samples of the minority class.

## Dataset Information
The dataset contains financial transaction records, where each record includes features such as transaction amount, type, time, and a label indicating whether the transaction is fraudulent or not. The dataset is divided into training and testing sets to evaluate model performance.

## Installation Instructions
To run the project, follow these instructions:
1. Clone the repository:
   ```bash
   git clone https://github.com/dhanushgoudra2003/Financial-Fraud-Detection-System-using-GAN-XGBoost-SMOTE.git
   cd Financial-Fraud-Detection-System-using-GAN-XGBoost-SMOTE
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main script:
   ```bash
   python main.py
   ```

## Usage
Upon executing the main script, the system will:
- Load the dataset and preprocess it.
- Generate synthetic fraudulent transactions using the GAN.
- Train the XGBoost model on the prepared dataset.
- Output the classification results, including precision, recall, and f1-score.

## Results
The system's performance can be evaluated based on various metrics: precision, recall, f1-score, and AUC-ROC curve. Detailed results will be logged after the execution of the main script.

## Technologies Used
- **Python**: The primary programming language used for this project.
- **TensorFlow/Keras**: For implementing GANs.
- **XGBoost**: To build the classification model.
- **Pandas, Numpy**: For data manipulation and analysis.
- **Matplotlib, Seaborn**: For visualizing results and performance metrics.

## Author
Dhanush Goudra | dhanushgoudra2003@github.com  
Date Updated: 2026-04-16 17:46:19 UTC