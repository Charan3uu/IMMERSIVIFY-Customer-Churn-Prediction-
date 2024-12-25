# IMMERSIVIFY - Customer Churn Prediction

## Overview
This project involves predicting customer churn using a dataset of customer details and transactional information. Customer churn refers to the loss of clients or customers, and predicting it can help businesses improve customer retention strategies.

## Dataset
The dataset contains the following key features:

- **Customer Information**: Gender, Age, Tenure, etc.
- **Geography**: The country of the customer.
- **Account Balance**: The customer’s bank account balance.
- **Credit Score**: The customer's credit score.
- **Product Information**: Number of products used by the customer.
- **Activity Information**: Estimated salary, active status, and transactional details.
- **Target Variable**: `Exited` (1 if the customer churned, 0 otherwise).

The dataset file is named `churn_modelling.csv`.

## Workflow
1. **Exploratory Data Analysis (EDA)**:
   - Analyze data distributions.
   - Visualize features against the target variable.

2. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical variables (One-Hot Encoding).
   - Scale numerical variables using `StandardScaler`.
   - Split the data into training and testing sets.

3. **Model Building**:
   - Use `Logistic Regression` for initial modeling.
   - Perform `GridSearchCV` to tune hyperparameters.
   - Train the model on the processed data.

4. **Evaluation**:
   - Assess the model’s performance using accuracy, precision, recall, F1-score, and a confusion matrix.
   - Visualize results using matplotlib.

## Installation
To run this project, install the required Python libraries:

```bash
pip install pandas numpy scikit-learn matplotlib
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Charan3uu/IMMERSIVIFY-Customer-Churn-Prediction-
   ```
2. Navigate to the project folder:
   ```bash
   cd IMMERSIVIFY-Customer-Churn-Prediction-
   ```
3. Run the Python script:
   ```bash
   python CHURN-MODELLING.py
   ```

## Results
- **Model Performance**: The model achieved an accuracy of over 80% on the test data.
- **Insights**: Key features influencing churn include customer age, balance, and number of products.

## Files
- `CHURN-MODELLING.py`: Main script for data preprocessing, modeling, and evaluation.
- `churn_modelling.csv`: Dataset file.
- `README.md`: Documentation for the project.
- `random_forest_model.pkl`: Trained model file (if exported).

## Visualization
Key visualizations include:
- Bar plots of churn vs. age, balance, and tenure.
- Confusion matrix showcasing model performance.

## Contributing
Feel free to fork this repository and submit pull requests for any improvements or suggestions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thanks to the open-source datasets and the machine learning community for resources and inspiration.
