# 🛒 Amazon Product Data Analysis (EDA Project)

This project performs **Exploratory Data Analysis (EDA)** on the **Amazon dataset** to uncover insights about product pricing, ratings, discounts, and customer preferences.  
The goal is to identify patterns in customer behavior, analyze rating distributions, and explore how pricing and discounts vary across product categories.

---

## 📁 Dataset / Files
- **amazon.csv** – Main dataset containing Amazon product details.
- **amazon_eda.py** / **amazon_analysis.ipynb** – Python or Jupyter Notebook script containing the full EDA workflow.

---

## 📊 Dataset Columns
| Column Name | Description |
|--------------|-------------|
| `product_name` | Name of the product |
| `category` | Category of the product |
| `actual_price` | Original listed price |
| `discounted_price` | Price after discount |
| `rating` | Average customer rating |
| `rating_count` | Number of customer ratings |
| `review_title` | Title of the customer review |
| `review_content` | Detailed customer review |
| `discount_percentage` | Discount offered on product |

# Objectives

- Analyze customer ratings and reviews

- Explore relationships between actual and discounted prices

- Identify top product categories based on ratings

- Examine pricing and discount patterns across categories

- Detect products with highest rating counts

# Tools & Libraries Used

- Python

- Pandas – Data cleaning and manipulation

- Matplotlib / Seaborn – Data visualization

- Jupyter Notebook / VS Code – Interactive development environment

# Insights

- Significant discounts were observed across most product categories.

- Higher discounts didn’t always correlate with higher ratings.

- Some categories (like electronics) received the most customer reviews.

- Products with mid-range prices tended to have the highest ratings.

# Conclusion

The Amazon dataset provides valuable insights into customer preferences, pricing strategies, and review patterns.
Through EDA, we can better understand which factors influence product popularity and customer satisfaction, helping improve e-commerce strategies.
