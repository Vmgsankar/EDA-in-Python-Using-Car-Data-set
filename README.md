# Exploratory Data Analysis (EDA) of Vehicle Dataset

This project focuses on conducting **Exploratory Data Analysis (EDA)** on a dataset of vehicles. The analysis aims to uncover insights about the relationship between various car features, such as horsepower, cylinders, price, fuel efficiency, and more.

## Project Overview

The goal of this project is to:
- Clean and preprocess the dataset (handling missing values and duplicates).
- Perform univariate, bivariate, and multivariate analyses.
- Visualize the relationships between various features like Horsepower (HP), Price, Cylinders, and Fuel Efficiency (MPG).
- Identify trends, correlations, and potential outliers in the dataset.

## Dataset

The dataset used for this analysis contains various features about vehicles, such as:
- **Make**: Brand of the car.
- **Horsepower (HP)**: Engine power.
- **Cylinders**: Number of engine cylinders.
- **Price**: MSRP (manufacturer's suggested retail price) of the car.
- **Fuel Efficiency (MPG)**: City and highway miles per gallon.
- **Drive Mode**: Type of drive (AWD, FWD, RWD).
- **Transmission**: Type of transmission (Automatic/Manual).

## Analysis Steps

1. **Data Cleaning**:
   - Removed irrelevant columns.
   - Dropped duplicate rows.
   - Handled missing values.

2. **Univariate Analysis**:
   - Distribution of key numerical variables such as HP, Price, Cylinders, etc.
   - Summary statistics like mean, median, standard deviation.

3. **Bivariate Analysis**:
   - Relationships between variables like Horsepower vs. Price, Cylinders vs. Price.
   - Scatter plots and correlation matrices to visualize trends.

4. **Multivariate Analysis**:
   - Correlation matrix to analyze relationships between multiple numerical variables.
   - Insights into how different features affect each other.

5. **Categorical Analysis**:
   - Distribution of vehicles by Make, Drive Mode, and Transmission.
   - Analyzing the impact of categorical variables on pricing and performance.

## Key Insights

- **Horsepower and Price**: Strong positive correlation—higher horsepower generally leads to higher prices.
- **Price and Cylinders**: More cylinders tend to correspond to higher prices.
- **Fuel Efficiency**: Higher horsepower vehicles tend to have lower fuel efficiency.
- **Brand Bias**: The dataset is skewed towards certain popular brands like Ford, Chevrolet, and Toyota.

## Visualizations

- **Distribution of Horsepower**: A histogram with KDE plot to visualize the spread of horsepower across vehicles.
- **Scatter Plots**: Visualizing relationships between features such as Horsepower vs. Price.
- **Box Plots**: Understanding the distribution of prices across different levels of horsepower.
- **Correlation Heatmap**: Displaying correlations between numerical features.
- **Bar Plots**: Analyzing the distribution of vehicles by make and other categorical variables.

## Recommendations

1. **Handle Outliers**: Outliers in price and horsepower should be addressed for more accurate modeling and analysis.
2. **Market Segmentation**: Segment vehicles into categories (e.g., low, medium, high horsepower) for more targeted insights.
3. **Balanced Analysis**: Consider the skewness towards certain brands when generalizing insights.

## Technologies Used

- **Python**: For data manipulation, cleaning, and analysis.
- **Pandas**: For handling and processing the dataset.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
- **Jupyter Notebook**: For interactive data analysis.

## Conclusion

This project provides a detailed exploration of the vehicle dataset, uncovering key insights into the relationships between vehicle features like horsepower, price, and cylinders. The analysis helps in understanding trends and patterns in vehicle performance and pricing, which can be valuable for market analysis, pricing strategies, and more.

