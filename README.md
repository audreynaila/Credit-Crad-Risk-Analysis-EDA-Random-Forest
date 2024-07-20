# Credit Card Risk Analysis: EDA & Random Forest

This project aims to analyze and predict credit card risk using Exploratory Data Analysis (EDA) and a Random Forest classification model. The primary objective is to understand the factors influencing credit card risk and build a model to classify the risk levels.

## Dataset
The dataset includes information on credit card customers and their financial behavior, such as:
- Customer demographics (age, gender, etc.)
- Credit card usage patterns
- Payment history
- Credit limits

## Exploratory Data Analysis (EDA)
EDA involves examining the dataset to identify patterns, detect anomalies, and test hypotheses. Key steps include:
- Data cleaning and preprocessing
- Statistical summary and visualization of features
- Identifying correlations and significant features

## Modeling with Random Forest
After EDA, a Random Forest classifier is used to predict credit card risk. Steps include:
- Splitting the data into training and testing sets
- Training the Random Forest model
- Evaluating model performance using metrics such as accuracy, precision, recall, and F1 score

## Results
The Random Forest model provides insights into the most significant factors affecting credit card risk and achieves a satisfactory level of accuracy in risk classification.

## Installation
To run this project locally, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/audreynaila/Credit-Card-Risk-Analysis-EDA-Random-Forest.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Credit-Card-Risk-Analysis-EDA-Random-Forest
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To perform EDA and train the Random Forest model, run the following command:
```bash
python main.py
