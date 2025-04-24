# Loan Status Prediction

A machine learning project to predict loan approvals based on applicant data.

## Table of Contents

- [Purpose](#purpose)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Steps](#steps)
- [Challenges](#challenges)
- [Future Improvements](#future-improvements)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [License](#license)

## Purpose

The goal of this project is to automate the loan approval process, making it faster and reducing human bias.

## Technologies Used

- Python
- pandas
- scikit-learn
- seaborn
- matplotlib

## Dataset

The dataset used is a public dataset containing information about loan applicants. It includes features such as gender, marital status, education, income, and more. The dataset is included in the `dataset` folder.

## Steps

1. **Data Collection and Preprocessing**: Loaded the dataset, handled missing values by dropping rows, and encoded categorical variables.
2. **Data Visualization**: Used seaborn and matplotlib to visualize the relationship between features and the target variable.
3. **Model Training**: Trained an SVM classifier on the preprocessed data.
4. **Model Evaluation**: Evaluated the model using accuracy score on both training and test data. The model achieved an accuracy of 83% on the test data.

## Challenges

- **Handling Missing Data**: Decided to drop rows with missing values due to the large size of the dataset.
- **Model Selection and Tuning**: Experimented with different classifiers and used cross-validation to optimize the SVM model.

## Future Improvements

- Experiment with other machine learning algorithms like Random Forest or Gradient Boosting.
- Implement feature engineering to create new features that might improve model performance.
- Use techniques like imputation instead of dropping missing values to retain more data.

## How to Run

1. Clone the repository.
2. Install the required dependencies: `pip install pandas scikit-learn seaborn matplotlib jupyter`
3. Open the notebook: `jupyter notebook loan_prediction.ipynb`
4. Run the cells in the notebook.

## Contributing

If you want to contribute, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.
