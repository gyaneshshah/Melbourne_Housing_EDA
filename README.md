# Melbourne Housing Price Prediction

This repository contains the code and documentation for a machine learning project completed as part of Kaggle's Machine Learning course. The project focuses on predicting house prices in Melbourne based on a dataset obtained from Kaggle. The project involves exploratory data analysis (EDA), feature engineering, and the development of a predictive model.

## Dataset

The dataset used for this project is the Melbourne housing dataset, which can be found on Kaggle [here](https://www.kaggle.com/dansbecker/melbourne-housing-snapshot). It includes various features such as the number of rooms, land size, location, type of property, etc., along with the target variable, which is the price of the house.

## Tools and Libraries

The project primarily utilizes Python and several libraries for data manipulation, analysis, and modeling:

- [pandas](https://pandas.pydata.org/docs/) - For data manipulation and analysis.
- [scikit-learn](https://scikit-learn.org/stable/documentation.html) - For building predictive models.

## Methodology

1. **Exploratory Data Analysis (EDA)**:
   - Understand the structure of the dataset.
   - Visualize relationships between different features and the target variable.

2. **Feature Engineering**:
   - Handle missing values.
   - Scale numerical features if necessary.

3. **Model Development**:
   - Initially, Decision Trees were employed for modeling.
   - Random Forest was ultimately chosen for its superior performance in reducing Mean Absolute Error (MAE).

## Model Evaluation

The performance of the predictive model was evaluated using Mean Absolute Error (MAE) as the metric. Random Forest showed better performance compared to Decision Trees.

## Repository Structure

- `data/`: Contains the dataset used for the project.
- `notebooks/`: Jupyter notebooks containing the code for EDA, feature engineering, and modeling.
- `README.md`: This README file providing an overview of the project.

## License

This project is licensed under the terms of the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was completed as part of Kaggle's Machine Learning course.
