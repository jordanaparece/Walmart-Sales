# Walmart-Sales
Exploratory Data Analysis on Walmart Sales, exploring the business question: What factors influence customer purchasing behavior the most, and how do these patterns vary by demographics and location?


Used SQL for querying and Tableau to visualize trends and drive business insights.

---

## 🧾 Project Overview

This project explores a large dataset of Walmart customer transactions, including user demographics, product categories, and purchase history. Using SQL (PostgreSQL) for data cleaning and analysis, and Tableau for visual storytelling, the objective was to uncover which factors most influence purchase behavior and how these patterns vary across segments such as age, city, and marital status.

The final output is a Tableau dashboard that allows stakeholders to visually explore customer profiles, top-performing products, and demographic-driven purchasing insights.

---

## 🎯 Background and Purpose

In the retail industry, understanding customer behavior is critical for optimizing marketing, improving inventory management, and increasing profitability. This project answers key business questions like:

- Who are Walmart's highest spending customers?
- Which product categories perform best across demographics?
- How do location and city tenure affect spending?

These insights are valuable for:

- Marketing teams targeting high-value customers
- Merchandisers aligning inventory with demand
- Executives making data-driven decisions to grow sales

---

## 📊 Data Overview

The dataset contains over 550,000 Walmart transactions with the following fields:

- `User_ID`, `Product_ID`
- `Gender`, `Age`, `Marital_Status`
- `Occupation`, `City_Category`, `Stay_In_Current_City_Years`
- `Product_Category`, `Purchase`

---

## ⚙️ Methods and Tech Stack

- **SQL (PostgreSQL)**: Used for data cleaning, aggregation, CTEs, window functions, and EDA
- **Tableau**: Used for visualizing SQL results and building dashboards
- **pgAdmin4**: Used to run and validate SQL queries

---

## 📈 Dashboard Features
  
> https://public.tableau.com/app/profile/jordan.aparece/viz/WalmartSales_17443494819710/Dashboard1

Key Queries and Visualizations:

🧑‍🤝‍🧑 Average & Total Purchase by Age and Gender  
🏙️ Revenue by City Category  
💼 Top Occupations by Average Spend  
🔁 Repeat Customer Rankings  
📊 Product Category Popularity by Gender  
📍 Impact of City Tenure on Average Spending  
🧮 High-Value Customers and Purchase Trends  
📦 Product Revenue Rankings

---

## 💡 Key Recommendations

🟢 **City Category B** is the top revenue driver and may benefit from targeted promotions or inventory expansion  
🔵 Customers aged **26–35** for both **men and women** consistently spend the most — key target segment  
🟡 **Occupations 14, 8, 15, 12, and 17** lead in **average** spending; segment by profession to enhance personalization  
🟣 Customers with **2 years in the same city** have the highest average purchase, signaling loyalty potential  
🛒 Product categories **1, 5, and 8** for both **men and women** are the most frequently purchased — optimize these for availability and upsell opportunities. **However**, the men spend have significantly more purchase than women

---

## ⚠️ Challenges Encountered

- **Missing and Inconsistent Data**: Required extensive cleaning to replace `NULL` values and standardize entries
- **Non-Numeric Tenure Field**: `Stay_In_Current_City_Years` contained entries like `'4+'` which had to be stripped and cast to integer for analysis
- **Skewed Product Categories**: Some categories had overwhelming purchase counts, requiring extra attention when visualizing popularity vs. revenue

---

## ✅ Conclusion

This project provided a clear picture of who Walmart’s key customers are, what they’re buying, and how location and tenure influence behavior. The Tableau dashboard can serve as a foundation for ongoing exploration and decision-making in customer segmentation, product optimization, and localized marketing strategies.

