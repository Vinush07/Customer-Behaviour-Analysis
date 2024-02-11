Customer Behavior Analysis using Transactional Data

Overview:
This repository contains Python code for analyzing customer behavior based on transactional data. The code covers various steps including data collection, cleaning, exploratory data analysis (EDA), customer segmentation, association analysis, and generating insights and recommendations.

Dataset:
The code expects a CSV dataset containing transactional data with the following columns:
- Invoice: Unique identifier for each transaction.
- StockCode: Unique identifier for each product.
- Description: Description of each product.
- Quantity: Number of items purchased in each transaction.
- InvoiceDate: Date and time of each transaction.
- Price: Price per unit of each item.
- CustomerID: Unique identifier for each customer.
- Country: Country where the customer is located.

Ensure that the dataset is correctly formatted and accessible before running the code.

Usage:
1. Clone the repository to your local machine.
2. Replace 'path_to_your_dataset.csv' in the code with the actual file path of your dataset.
3. Install the required dependencies using pip:
4. Run each step of the code sequentially to perform data cleaning, EDA, customer segmentation, association analysis, and generate insights.
5. Review the outputs such as visualizations, customer segments, and association rules to understand customer behavior and derive insights.
6. Modify the code as needed based on specific analysis goals and dataset characteristics.

Dependencies:
- pandas
- matplotlib
- seaborn
- scikit-learn
- mlxtend

Author:
Vinush B M


