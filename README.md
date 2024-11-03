# BigMart Sales Prediction

This project aims to predict the sales of products in BigMart stores using machine learning.

## Dataset

The dataset used in this project is the BigMart Sales dataset, which contains information about various products sold in different BigMart stores. It includes features such as item weight, fat content, item type, outlet size, location type, and outlet type.

## Methodology

The project follows these steps:

1. **Data Loading and Preprocessing:**
    - Loading the train and test datasets using pandas.
    - Handling missing values by imputation.
    - Encoding categorical features using Label Encoding.
2. **Exploratory Data Analysis:**
    - Analyzing the distribution of features.
    - Identifying correlations between features.
3. **Model Building:**
    - Using RandomForestRegressor to build a predictive model.
    - Training the model on the training data.
4. **Model Evaluation:**
    - Evaluating the model's performance using metrics such as R-squared, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
5. **Prediction and Submission:**
    - Predicting sales for the test dataset.
    - Saving the predictions in a CSV file for submission.

## Dependencies

The following libraries are required to run this project:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install them using pip:

## Usage

1. Download the train and test datasets and place them in the same directory as the code.
2. Run the code in a Jupyter Notebook or Google Colab environment.
3. The predictions for the test dataset will be saved in a file named `Test_New.csv`.

## Results

The model achieves a high R-squared value on the training data, indicating good performance. The predicted sales for the test dataset are saved in the `Test_New.csv` file.

## Conclusion

This project demonstrates how machine learning can be used to predict sales in the retail industry. The RandomForestRegressor model provides accurate predictions, which can be valuable for businesses in making informed decisions.
