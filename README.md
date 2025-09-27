Airbnb NYC Data Analysis

 Project Overview

This project is a comprehensive data analysis of the Airbnb Open Data dataset for New York City. The goal is to perform data wrangling, cleaning, and exploratory data analysis (EDA) to uncover key insights. The analysis answers specific questions about Airbnb listings, such as pricing trends, neighborhood popularity, and the relationship between various features like price and service fees. The project also includes a linear regression analysis and a correlation heatmap to identify relationships between numerical variables.

 Key Features

  * Data Cleaning: Handles missing values, cleans and converts data types for columns like 'price' and 'service\_fee', and removes duplicates and outliers.
  * Exploratory Data Analysis (EDA): Visualizes and answers key business questions, including:
      * Distribution of property types.
      * The neighborhood group with the most listings.
      * The relationship between price and service fees.
      * The impact of host identity verification on reviews.
  * Statistical Analysis: Calculates descriptive statistics for numerical and categorical features.
  * Linear Regression: Models the relationship between a host's number of listings and their property's availability.
  * Correlation Analysis: Uses a heatmap to visualize the correlation between all numerical features.

Getting Started

 Prerequisites

You need to have Python and the following libraries installed:

  * `pandas`
  * `numpy`
  * `matplotlib`
  * `seaborn`
  * `scikit-learn` (`sklearn`)

You can install these libraries using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Dataset

The dataset used in this analysis is named `1730285881-Airbnb_Open_Data.xlsx`. This file is not included in the repository and must be downloaded separately.

1.  Download the file:The dataset is publicly available on Kaggle. Search for "Airbnb Open Data" to find and download it.
2.  Upload to Colab: If you're using Google Colab, upload the downloaded `1730285881-Airbnb_Open_Data.xlsx` file to your Colab environment. Make sure the file name matches the one specified in the script.

 Running the Script

1.  Place the `airbnb_analysis.py` script and the downloaded `1730285881-Airbnb_Open_Data.xlsx` file in the same directory (or upload to Colab).

2.  Run the script from your terminal or a Jupyter/Colab notebook:

    bash
    python airbnb_analysis.py
  

The script will print the analysis results to the console and display the generated plots.

 Project Structure

.
├── airbnb_analysis.py       # Main Python script for data analysis
├── README.md                # This file
└── 1730285881-Airbnb_Open_Data.xlsx # The dataset (to be downloaded separately)

 Insights & Conclusions

Upon running the script, you will find several key insights from the data, including:

  * Brooklyn and Manhattan have the highest number of Airbnb listings.
  * Manhattan and Brooklyn have the highest average listing prices.
  * There is a strong positive correlation between a listing's price and its service_fee.
  * Hosts with a higher number of listings tend to have lower availability, suggesting that popular hosts are often fully booked.
  * `Entire home/apt` properties are, on average, more expensive than `Private room` or `Shared room` listings.
 Author

AI Assistant
