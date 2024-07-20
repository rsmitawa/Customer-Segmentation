# Bank Customer Segmentation Project

## Overview
This project aims to segment bank customers based on their spending patterns and interaction history. Using machine learning techniques, specifically Hierarchical Clustering Analysis (HCA) and K-Means Clustering, we identify distinct customer segments to help the bank better understand and serve its customer base.

## Table of Contents
1. [Project Objective](#project-objective)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
4. [Requirements](#requirements)
5. [Setup and Installation](#setup-and-installation)
6. [Usage](#usage)
7. [Results](#results)
8. [Contributing](#contributing)
9. [License](#license)

## Project Objective
The main goal of this analysis is to identify different segments in the existing customer base based on their spending patterns and past interactions with the bank. This segmentation will provide insights to help the bank improve its marketing strategies and customer service.

## Dataset
The project uses the "Credit Card Customer Data" dataset, which includes information about customers' credit limits, number of credit cards, bank visits, online logins, and customer service calls.

## Methodology
The project follows these main steps:
1. Data Preparation and Exploration
2. Exploratory Data Analysis (EDA)
3. Machine Learning
   - Hierarchical Clustering Analysis (HCA)
   - K-Means Clustering
4. Comparison of Clustering Results
5. Insights and Recommendations

## Requirements
This project requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn
- yellowbrick

## Setup and Installation
1. Clone this repository:
   ```
   git clone https://github.com/your-username/bank-customer-segmentation.git
   ```
2. Navigate to the project directory:
   ```
   cd bank-customer-segmentation
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```
   jupyter notebook Bank_Customer_Segmentation.ipynb
   ```
2. Run the cells in order to perform the analysis.

## Results
The analysis identifies three main customer segments:
1. Low credit limit customers who prefer phone banking
2. Mid-range credit limit customers who make frequent in-person visits
3. High credit limit customers who prefer online banking

Detailed insights and recommendations are provided in the notebook.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.