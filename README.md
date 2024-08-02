# Data_exploration_using_python_powebi
# Global Superstore Data Analysis

## Introduction

This repository contains a comprehensive analysis of the Global Superstore dataset, leveraging both Python and PowerBI for data exploration and visualization. The analysis aims to uncover insights into sales, profit, shipping costs, and order priorities across different regions and product categories.

## Repository Structure

- `data/`: Contains the dataset used for the analysis.
- `python/`: Contains Python scripts for data exploration and visualization.
- `powerbi/`: Contains PowerBI reports and visualizations.

## Python Analysis

### Scripts

1. **Data Exploration and Visualization**
    - **Description**: This script performs basic data exploration and visualization using matplotlib and seaborn.
    - **File**: `python/data_exploration.ipynb`
    - **Key Visualizations**:
      - Count of Orders by Order Priority
      - Count of Orders by Country
      - Sales Distribution by Sub-Category
      - Profit Distribution by Sub-Category

### Inferences from Python Visualizations

1. **Count of Orders by Order Priority**
    - Insight: The majority of orders are of critical priority, indicating a high demand for expedited shipping.
    - Action: Enhance logistics to ensure timely delivery for high-priority orders.

2. **Count of Orders by Country**
    - Insight: The United States has the highest number of orders, suggesting a strong customer base.
    - Action: Focus marketing efforts and inventory management on high-order regions.

3. **Sales Distribution by Sub-Category**
    - Insight: Technology and Office Supplies categories have the highest sales.
    - Action: Prioritize these categories for promotions and inventory restocking.

4. **Profit Distribution by Sub-Category**
    - Insight: Certain sub-categories like Phones and Chairs have high profits.
    - Action: Increase focus on high-profit sub-categories to boost overall profitability.

## PowerBI Analysis

### Visualizations

1. **Global Summary**
    - Description: Provides a summary of the total quantity, sales, and profit.
    - Inferences:
      - The business has a substantial volume of sales and profits, indicating healthy operations.

2. **Stacked Column Chart: Count of Orders by Order Priority**
    - Description: Displays the count of orders segmented by order priority.
    - Inferences:
      - High count of critical orders necessitates efficient logistics for timely delivery.
      - Medium and low priority orders suggest a steady demand for standard shipping options.

3. **Donut Chart: Discount by Different Category**
    - Description: Shows the distribution of discounts across product categories.
    - Inferences:
      - Technology and Furniture categories receive higher discounts, possibly due to competitive pricing.
      - Office Supplies have lower discounts, indicating stable demand without heavy promotions.

4. **Tree Map: Quantity, Shipping Cost, Profit by Category**
    - Description: Visualizes the quantity sold, shipping cost, and profit by product category.
    - Inferences:
      - High quantity categories need effective inventory management.
      - Categories with high shipping costs require optimization to improve profitability.
      - High profit categories should be prioritized for sales and marketing efforts.

5. **Multi-Row Card: Shipping Cost and Quantity**
    - Description: Displays key metrics related to shipping costs and quantity.
    - Inferences:
      - Helps track and manage shipping expenses relative to the quantity sold.

### Q&A Visualization

- **Description**: Enables users to ask natural language questions and receive interactive answers.
- **Inferences**:
  - Enhances data accessibility and user engagement.
  - Supports real-time decision-making by providing instant insights.

## How to Use

### Python

1. **Setup Environment**:
   - Ensure you have Python installed.
   - Install the required libraries: `pandas`, `matplotlib`, `seaborn`.

2. **Run Scripts**:
   - Navigate to the `python/` directory.
   - Execute the scripts using the command:
     ```sh
     python data_exploration.py
     ```

### PowerBI

1. **Open PowerBI Desktop**:
   - Download and install PowerBI Desktop if you haven't already.

2. **Load the Report**:
   - Navigate to the `powerbi/` directory.
   - Open the PowerBI report file (`Global_Superstore.pbix`).

3. **Interact with Visualizations**:
   - Use the interactive features to explore different visualizations and gain insights.

## Conclusion

This analysis provides valuable insights into the Global Superstore dataset, leveraging the strengths of both Python and PowerBI. The combination of detailed data exploration and interactive visualizations supports informed decision-making and strategic planning.

