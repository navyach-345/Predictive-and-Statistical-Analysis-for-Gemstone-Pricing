# Predictive-and-Statistical-Analysis-for-Gemstone-Pricing
Analyzed a dataset of 27,000 records to explore the relationship between gemstone attributes (carat, cut, color, clarity) and pricing. Implemented data cleaning, EDA, feature engineering, and advanced statistical methods such as ANOVA, hypothesis testing, and GLM.

# Dataset
The dataset used in this project has been downloaded from Kaggle: [Gemstone Price Prediction Dataset](https://www.kaggle.com/datasets/colearninglounge/gemstone-price-prediction)

## Features: 
* **Carat**: The gem's carat weight.
* **Cut**: Describes the gem's cut quality. The order of the quality ranges from Fair, Good, Very Good, Premium, and Ideal.
* **Color**: Represents the color of the stone. With D being the best and J the worst.
* **Clarity**: This refers to the absence of defects and inclusions in the gemstone, which affects its transparency and purity. It is rated from FL (flawless) to I3 (level 3 inclusions).
* **Depth**: The height of a cubic zirconia divided by its average Girdle Diameter, as measured from the culet to the table.
* **Table**: It is the width of the gem whic is represented as a percentage of the average
diameter.
* **X**: The cubic zirconia's length in millimeters.
* **Y**: The cubic zirconia's width in millimeters.
* **Z**: The cubic zirconia's height in millimeters.
* **Price**: The cubic zirconia's price.


# Key Features
- **Data Cleaning and Preprocessing**:
  - Handled missing values, duplicates, and outliers.
  - Normalized numerical features and performed one-hot encoding for categorical variables.
  - Scaled data for consistent ranges across features.
  
- **Exploratory Data Analysis (EDA)**:
  - Analyzed distributions of attributes using histograms, density plots, and boxplots.
  - Studied relationships between attributes and pricing using visualizations.

- **Statistical Analysis**:
  - Linear Regression: Measured the impact of predictors like carat, cut, color, and clarity on price.
  - Generalized Linear Model (GLM): Used a Gamma distribution to handle skewed pricing data.
  - ANOVA: Assessed interactions between attributes (e.g., cut and color) on pricing.
  - Hypothesis Testing: Compared variances in prices for different color grades using F-tests.
  - Confidence Intervals: Estimated average gemstone prices for each cut category.

- **Model Selection**:
  - Evaluated models using metrics like Adjusted R², AIC, BIC, and MSPE.
  - Selected the best model with 23 predictors, achieving strong predictive performance.

# Tools and Technologies
- **Programming**: R
- **Libraries**: ggplot2, dplyr, MASS, caret, leaps
- **Visualization**: Power BI
- **Statistical Methods**: Linear Regression, GLM, ANOVA, Hypothesis Testing

# Installation
1. Clone the repository:
   ```bash 
   git clone https://github.com/navyach-345/Predictive-and-Statistical-Analysis-for-Gemstone-Pricing.git

2. Install the required packages:
   ```bash
   install.packages(c("ggplot2", "dplyr", "caret", "MASS", "leaps"))

# Usage
Run the R scripts to replicate data cleaning, EDA, and statistical modeling steps.
