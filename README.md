---

# Bank Customer Segmentation Project

## Overview
This project segments bank customers based on their spending patterns and interaction history. Using machine learning techniques, specifically Hierarchical Clustering Analysis (HCA) and K-Means Clustering, we identify distinct customer segments to help the bank better understand and serve its customer base.

## Table of Contents
1. [Project Objective](#project-objective)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
4. [Requirements](#requirements)
5. [Setup and Installation](#setup-and-installation)
6. [Usage](#usage)
7. [Results and Insights](#results-and-insights)
8. [Recommendations](#recommendations)
9. [Contributing](#contributing)


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

## Results and Insights

Our analysis using Hierarchical Clustering Analysis (HCA) and K-Means Clustering revealed three distinct customer segments:

### Segment 1: Low Credit Limit Customers
- **Average Credit Limit:** ~12,000
- **Average Number of Credit Cards:** 2-3
- **Preferred Interaction:** Phone calls (6-7 calls per year on average)
- **Insights:** 
  - This segment represents price-sensitive customers who may be new to credit or have lower incomes.
  - They rely heavily on phone support, suggesting a need for personal assistance.

### Segment 2: Mid-Range Credit Limit Customers
- **Average Credit Limit:** ~34,000
- **Average Number of Credit Cards:** 5-6
- **Preferred Interaction:** In-person visits (3-4 visits per year on average)
- **Insights:** 
  - These customers prefer face-to-face interactions, possibly due to complex queries or a desire for personalized service.
  - They represent a growth opportunity, as they use multiple credit cards but have moderate credit limits.

### Segment 3: High Credit Limit Customers
- **Average Credit Limit:** ~142,000
- **Average Number of Credit Cards:** 8-9
- **Preferred Interaction:** Online banking (10-11 online logins per year on average)
- **Insights:** 
  - This segment represents the bank's most valuable customers in terms of credit usage.
  - They are tech-savvy and prefer self-service options through online banking.

### Key Findings
1. There's a clear correlation between credit limit, number of credit cards, and preferred interaction method.
2. Customer service preferences vary significantly across segments, highlighting the need for a multi-channel approach.
3. The mid-range segment's preference for in-person visits presents an opportunity for efficiency improvements.

## Recommendations

Based on our analysis, we recommend the following strategies:

1. **Enhance Digital Services:** 
   - Invest in improving the online banking platform to better serve high-value customers and encourage adoption among other segments.
   - Develop educational resources to help low-limit customers become more comfortable with digital banking.

2. **Optimize In-Branch Experience:** 
   - Train staff to efficiently handle complex queries from mid-range customers.
   - Implement appointment scheduling to reduce wait times and improve the in-person experience.

3. **Improve Phone Banking:**
   - Enhance the phone banking system to handle common queries more efficiently.
   - Provide specialized training to phone banking staff to better assist low-limit customers.

4. **Tailored Marketing Strategies:**
   - Develop targeted credit limit increase offers for the mid-range segment.
   - Create loyalty programs that align with each segment's preferences (e.g., cashback for low-limit, travel rewards for high-limit).

5. **Cross-Selling Opportunities:**
   - Identify products that complement each segment's needs (e.g., basic savings accounts for low-limit, investment products for high-limit).

6. **Continuous Monitoring:**
   - Implement a system to track customer segment migrations over time.
   - Regularly update the segmentation model to capture evolving customer behaviors.

By implementing these recommendations, the bank can improve customer satisfaction, increase product adoption, and potentially grow its credit card business across all segments.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

---