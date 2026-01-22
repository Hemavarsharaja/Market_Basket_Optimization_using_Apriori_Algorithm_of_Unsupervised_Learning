# Market_Basket_Optimization_using_Apriori_Algorithm_of_Unsupervised_Learning
📌 Project Overview

Market Basket Optimization is a data mining technique used to discover purchasing patterns by analyzing combinations of items frequently bought together.
This project applies the Apriori Algorithm, an unsupervised learning approach, to extract association rules from transaction data and uncover meaningful insights for business decision-making.

🎯 Objective

Identify frequent itemsets from transaction data

Generate association rules that show relationships between products

Help businesses improve:

Product placement

Cross-selling strategies

Recommendation systems

Promotional planning

🧠 Algorithm Used
Apriori Algorithm

Works on the principle:
“If an itemset is frequent, all of its subsets must also be frequent.”

Uses:

Support – frequency of itemset

Confidence – reliability of rule

Lift – strength of association

📂 Dataset Description

Dataset consists of customer transaction records

Each row represents a transaction

Each transaction contains a list of items purchased together

Suitable for association rule mining

🛠️ Tech Stack

Python

Jupyter Notebook

Libraries Used:

pandas

numpy

mlxtend

matplotlib / seaborn (for visualization)

⚙️ Installation & Setup

Clone the repository:

git clone https://github.com/Hemavarsharaja/Market_Basket_Optimization_using_Apriori_Algorithm.git


Install required libraries:

pip install pandas numpy mlxtend matplotlib seaborn


Open Jupyter Notebook:

jupyter notebook


Run the notebook file to see results.

🔍 Project Workflow

Data Loading

Data Preprocessing

Transaction Encoding

Frequent Itemset Generation

Association Rule Mining

Result Interpretation & Visualization

📊 Sample Output

Frequent itemsets with high support

Association rules with:

Support

Confidence

Lift

Insights on product combinations frequently purchased together
