# Expresso Churn Prediction

## Introduction

This project involves working on the 'Expresso Churn' dataset provided as part of the Expresso Churn Prediction Challenge hosted by the Zindi platform. Expresso is an African telecommunications services company operating in Mauritania and Senegal. The objective of this project is to predict the churn probability of Expresso clients based on various behavior variables.

## Problem Statement

The main goal of this project is to develop a machine learning model to predict the likelihood of client churn for Expresso, utilizing the provided dataset which includes over 2.5 million clients and more than 15 behavioral variables.

## Dataset Description

The dataset contains information about Expresso's clients, including various behavior metrics that could influence churn. The columns in the dataset are as follows:

- **user_id**: Unique identifier for each client.
- **REGION**: Region where the client is located.
- **TENURE**: Duration of time the client has been with Expresso.
- **MONTANT**: Total amount spent by the client.
- **FREQUENCE_RECH**: Frequency of recharges made by the client.
- **REVENUE**: Total revenue generated from the client.
- **ARPU_SEGMENT**: Average Revenue Per User segment.
- **FREQUENCE**: Frequency of interactions or transactions.
- **DATA_VOLUME**: Volume of data used by the client.
- **ON_NET**: Usage within the Expresso network.
- **ORANGE**: Interactions with the Orange network.
- **TIGO**: Interactions with the Tigo network.
- **ZONE1**: Usage in Zone 1 areas.
- **ZONE2**: Usage in Zone 2 areas.
- **MRG**: Margin or profitability metric.
- **REGULARITY**: Regularity of the client's interactions or usage.
- **TOP_PACK**: Top pack or plan subscribed by the client.
- **FREQ_TOP_PACK**: Frequency of top pack usage.
- **CHURN**: Target variable indicating whether the client churned (1 = yes, 0 = no).

## Objectives

1. **Predict Client Churn**: Develop a machine learning model to accurately predict the likelihood of a client churning.
2. **Identify Key Factors**: Analyze the dataset to identify key factors that contribute to client churn.
3. **Provide Recommendations**: Suggest actionable insights and strategies for reducing churn based on model predictions and analysis.

## Tools and Libraries

This project utilizes the following tools and libraries:
- **Python**: Programming language for data analysis and modeling.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For machine learning modeling.
- **Matplotlib/Seaborn**: For data visualization.

## Installation

To get started with the project, you need to have Python installed. Install the necessary libraries using pip:

```sh
pip install pandas scikit-learn matplotlib seaborn
```

## Usage

1. **Clone the repository:**

```sh
git clone https://github.com/Oluwaseun/Expresso_Churn.git
cd Expresso_Churn
```

2. **Run the analysis script:**

The main analysis and modeling are contained in the `analysis.py` script. Run this script to perform the data analysis and train the machine learning model:

```sh
python analysis.py
```

## Analysis and Model Development

### Data Preprocessing

- **Cleaning**: Handle missing values and correct any inconsistencies in the dataset.
- **Encoding**: Convert categorical variables into numerical values.
- **Scaling**: Standardize the numerical features to improve model performance.

### Model Training

- **Feature Selection**: Identify and select the most relevant features for the model.
- **Model Selection**: Evaluate different machine learning algorithms (e.g., logistic regression, decision trees, random forest) to select the best-performing model.
- **Model Training**: Train the selected model on the training data and evaluate its performance on the validation set.

### Results and Insights

- **Feature Importance**: Analyze which features have the most significant impact on churn prediction.
- **Predictive Accuracy**: Assess the accuracy and reliability of the model in predicting client churn.

## Recommendations

- **Targeted Retention Strategies**: Develop targeted retention strategies for clients at high risk of churning based on model predictions.
- **Enhance Client Engagement**: Implement measures to enhance client engagement and satisfaction, particularly for those identified as high-risk.
- **Monitor Key Metrics**: Continuously monitor key metrics and update the model with new data to improve prediction accuracy and responsiveness to changing trends.

## Conclusion

By developing a robust machine learning model and analyzing key client behavior variables, this project aims to provide valuable insights into factors contributing to client churn for Expresso, enabling better retention strategies and improved customer satisfaction.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

We thank Zindi for hosting the challenge and providing the dataset. We also appreciate the open-source community for the tools and libraries used in this project.
