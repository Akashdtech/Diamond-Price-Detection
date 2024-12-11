# Diamond-Price-Detection
This project demonstrates an exploratory data analysis (EDA) and modeling process using the diamonds.csv dataset, focusing on predicting diamond prices using machine learning.

    Data Exploration:
        The dataset is loaded and various summary statistics are displayed, including general information about the dataset (info), statistical description (describe), shape of the dataset (shape), and first/last 10 rows (head, tail).
        Unique values for categorical features (cut, color, clarity) are printed.

    Visualizations:
        Bar Plots: Relationship between diamond features (cut, clarity) and diamond price is shown using bar plots with hue-based grouping.
        Scatter Plot: A scatter plot visualizing the correlation between carat and price, with hues based on cut.
        Box Plots: Distribution of price across different categories of cut and clarity.

    Preprocessing:
        Categorical variables (cut, color, clarity) are encoded using LabelEncoder to convert them into numerical values suitable for modeling.

    Data Splitting:
        The features (X) and target (y) are separated, and the data is split into training and testing sets using an 80-20 split.

    Modeling:
        A Random Forest Regressor is trained on the training data to predict diamond prices. The model is evaluated using the R² score to measure its performance on the test data.

Key Output:

    Visualizations provide insight into the relationships between categorical features and the price of diamonds.
    The model's performance is evaluated using the R² score, which is printed at the end.

This code provides a basic yet comprehensive approach for preparing data, exploring relationships, and applying machine learning to predict diamond prices.
