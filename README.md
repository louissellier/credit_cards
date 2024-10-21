![Columbia University Logo]([https://upload.wikimedia.org/wikipedia/en/thumb/4/44/Columbia_University_seal.svg/1200px-Columbia_University_seal.svg.png](https://en.wikipedia.org/wiki/Columbia_University#/media/File:Columbia_University_1754.svg))

# Credit Card Default Prediction Using AI

## Project Overview

Managing credit card defaults is a critical focus area for the financial industry. Defaulting on credit card payments can negatively impact both individuals and financial institutions. From the consumer side, defaults harm credit scores, limiting future borrowing options. From the institution's perspective, unchecked defaults can lead to substantial financial losses and broader economic instability. 

To address these challenges, Artificial Intelligence (AI) provides a powerful solution by predicting the likelihood of default. Accurate prediction models allow financial institutions to take preemptive actions, such as offering flexible payment plans or prioritizing high-risk customers for early intervention. AI's ability to analyze large datasets and identify patterns enables it to model credit risk with greater precision than traditional methods, facilitating data-driven decisions, minimizing human error, and enhancing transparency.

## Dataset Overview

For this project, we have utilized the "Default of Credit Card Clients" dataset, which was added to the [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients) on January 25th, 2016. The dataset originally stems from research conducted in Taiwan and is published in [ScienceDirect](https://www-sciencedirect-com.ezproxy.cul.columbia.edu/science/article/pii/S0957417407006719?fr=RR-2&ref=pdf_download&rr=8d17e87ebd42c33d).

### Key Details:
- **Dataset Size**: 30,000 credit card holders
- **Number of Features**: 23 (including demographics, credit limits, payment history, etc.)
- **Target Variable**: Binary classification (1 = Default, 0 = No Default)

### Features:
- **Demographics**: Age, gender, marital status, and educational level.
- **Credit Info**: Credit limit, previous payment history, and bill amounts.
- **Behavioral Patterns**: Payment consistency and delinquency records.

This dataset is well-suited for a binary classification problem, where the goal is to predict whether a client will default on their credit card payment in the following month.

## Project Objectives

The goal of this project is to build a predictive model that:
1. **Predicts Default Risk**: Accurately forecasts the likelihood of a customer defaulting on their credit card payment.
2. **Improves Decision-Making**: Helps financial institutions make informed, data-driven decisions regarding credit risk management.
3. **Enables Preemptive Action**: Supports the early identification of high-risk customers, enabling timely interventions like payment restructuring.
4. **Reduces Default Rates**: Ultimately contributes to reducing the default rate and improving the overall financial health of both individuals and institutions.

## Methodology

1. **Data Preprocessing**: We clean and preprocess the dataset, handling missing values and standardizing the data.
2. **Exploratory Data Analysis (EDA)**: We explore relationships between the features and the target variable to gain deeper insights into default patterns.
3. **Modeling**: We employ machine learning algorithms such as Logistic Regression, Random Forest, and Gradient Boosting to build and evaluate classification models.
4. **Evaluation Metrics**: Our models are assessed using accuracy, precision, recall, and F1-score to ensure robustness and reliability.
5. **Hyperparameter Tuning**: We optimize model performance using techniques like GridSearch and Cross-Validation.

## Technologies Used

- **Python**: Data analysis and model development using libraries such as pandas, NumPy, scikit-learn, and Matplotlib.
- **Machine Learning Models**: Logistic Regression, Random Forest, Gradient Boosting, and others.
- **Data Visualization**: Matplotlib and Seaborn for exploring and visualizing the data.

## Conclusion

This project demonstrates the potential of AI in mitigating credit card default risk. By leveraging advanced machine learning techniques, financial institutions can shift towards proactive risk management, reduce default rates, and offer tailored services to customers at risk of delinquency. This not only ensures better financial health for institutions but also empowers consumers to manage their credit responsibly.

## References

- Yeh, I. C., & Lien, C. H. (2009). The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients. *Expert Systems with Applications, 36*(2), 2473-2480. [Link to publication](https://www-sciencedirect-com.ezproxy.cul.columbia.edu/science/article/pii/S0957417407006719?fr=RR-2&ref=pdf_download&rr=8d17e87ebd42c33d)
- UCI Machine Learning Repository - [Default of Credit Card Clients Dataset](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)
