# Amazon-sales-Project
📊 Amazon Product Reviews Analysis - Power BI Project
Project Overview:
This project aims to analyze customer reviews and product data from Amazon to derive actionable insights into product performance, customer satisfaction, pricing strategies, and category-level trends. The analysis follows the Data Analysis Life Cycle and is visualized through an interactive Power BI dashboard.
🧭 Data Analysis Life Cycle:
1. Data Collection
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

We collected raw product data directly from Amazon, including product details, pricing, discount information, customer reviews, ratings, and associated metadata.
Key columns included:

product_id, product_name

Category hierarchy (Category.L1 to Category.L5)

Prices (discounted and actual)

rating, rating_count

user_id, user_name, review_title, review_content

2. Data Cleaning (Done in Python)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Using Python, we cleaned and transformed the dataset by:

Merging and flattening category columns into one hierarchical string (category)

Standardizing price fields and converting to numeric

Removing unnecessary columns (like excessive review info)

Ensuring consistency in format and encoding

You can find the full cleaning process in the accompanying Jupyter Notebook Cleaning.ipynb.

3. Data Exploration
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Initial insights include:

Distribution of ratings across products

Most reviewed and highest-rated products

Correlation between discount and review count

Categories with the highest customer interest

4. Data Analysis & Visualization (in Power BI)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
A Power BI dashboard was built to visualize:

Product rating trends

Top-rated vs most-reviewed products

Category-wise distribution

Pricing vs rating analysis

Word clouds or summaries of review sentiments (if included)

5. Insights & Recommendations
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The dashboard enables stakeholders to:

Identify top-performing products

Understand customer preferences by category

Adjust pricing strategies based on review/ratings

Detect products with high engagement but poor reviews (action needed)

🧰 Tools Used
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Python (for cleaning and preprocessing)
Power BI (for interactive dashboard visualization)
Amazon Data (as source)

📬 Contact
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

For inquiries, feedback, or collaboration opportunities, feel free to reach out:
Abdelrahman Abdelfattah
Email: abdoabdelfattah243@gmail.com
Location: obour city, Egypt
Open to freelance opportunities and collaborations!📬 Contact


