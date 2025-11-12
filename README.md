# 🛍 CUSTOMER SHOPPING BEHAVIOR ANALYSIS PROJECT

*EDA using Python*

---

## 🧠 Project Overview

 **Exploratory Data Analysis (EDA) using Python**

This project explores customer shopping behavior to understand *spending patterns, **product preferences, **seasonal trends, and **purchase frequency*.


🎯 *The Goal:*
To identify the key factors that influence how, when, and what customers purchase — helping businesses improve product offerings, marketing strategies, and sales performance.

---

## 🧾 Dataset Description

*Source:* Kaggle
*Rows:* 3,900
*Columns:* 18

### *Key Columns Used:*

| Column                 | Description                                       |
| ---------------------- | ------------------------------------------------- |
| Customer ID            | Unique identifier for each customer               |
| Age                    | Customer’s age                                    |
| Gender                 | Male or Female                                    |
| Item Purchased         | Specific product bought                           |
| Category               | Product type (Clothing, Accessories, etc.)        |
| Purchase Amount (USD)  | Amount spent by the customer                      |
| Location               | Customer’s state or region                        |
| Size                   | Purchased size (S, M, L, XL)                      |
| Color                  | Product color                                     |
| Season                 | Season of purchase (Winter, Spring, Summer, Fall) |
| Review Rating          | Customer rating (out of 5)                        |
| Subscription Status    | Whether customer is subscribed                    |
| Shipping Type          | Mode of delivery                                  |
| Discount Applied       | Whether discount was used                         |
| Promo Code Used        | Whether a promo code was applied                  |
| Previous Purchases     | Number of past purchases                          |
| Payment Method         | Mode of payment                                   |
| Frequency of Purchases | How often the customer shops                      |

---

## 🧮 Exploratory Data Analysis (EDA) — Python

### 🔹 Tools Used

| Tool                     | Purpose                                  |
| ------------------------ | ---------------------------------------- |
| *Python*               | Data analysis and cleaning               |
| *Pandas*               | Data manipulation and summary statistics |
| *NumPy*                | Numerical operations                     |
| *Matplotlib & Seaborn* | Visualizations                           |
| *Jupyter Notebook*     | Running and visualizing analysis         |

---

### 🔹 EDA Steps Performed

#### *1. Data Cleaning*

* Checked data types and structure
* Found and filled 37 missing values in Review Rating using the mean
* Removed all duplicates (none found)

#### *2. Data Exploration*

* Identified numeric and categorical columns
* Explored basic statistics like mean, median, and standard deviation
* Found data distribution and outliers using boxplots
* Analyzed top categories, locations, and items
* Explored gender, season, and discount-based patterns
* Histograms for age, review rating, and purchase amount

#### *4. Correlation & Patterns*

* Checked numeric relationships using a correlation heatmap
* Found weak correlations between numeric variables (age, purchases, rating, amount)
* Added grouped visualizations for age group vs purchase amount, category vs season, and subscription vs frequency

---

## 📊 Key Findings from EDA

| Category                    | Insights                                                                                                                                      |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| *Customer Demographics*   | Customers aged 26–45 form the largest buyer group. Both genders spend nearly the same, with females slightly higher average purchases.        |
| *Top Locations*           | Montana, California, and Idaho have the highest shopping activity.                                                                            |
| *Product Preferences*     | Clothing and Accessories dominate purchases. Most popular items include Blouse, Pants, and Jewelry.                                     |
| *Sizes & Colors*          | Size *M* is most preferred, followed by *L. Popular colors are *Olive, Yellow, and Silver.                                          |
| *Spending Pattern*        | The average purchase amount per customer is *$59.76*. Spending is evenly distributed across age groups.                                     |
| *Seasonal Trends*         | *Spring* has the highest number of purchases, followed by Fall and Winter. Summer shows slightly lower engagement.                          |
| *Discount & Promo Impact* | Both discount and promo code usage show very small differences in average spending — indicating they don’t majorly influence purchase amount. |
| *Subscription Behavior*   | Non-subscribed customers buy more frequently (Every 3 Months, Quarterly) compared to subscribed ones.                                         |
| *Shipping Preferences*    | *Free Shipping* is the most used delivery option, followed by *Standard* and *Store Pickup*.                                            |
| *Customer Satisfaction*   | Average review rating across all categories is around *3.7–3.8, with **Footwear* and *Accessories* receiving slightly better feedback.  |
| *Correlations*            | No strong correlations found between review rating, age, and purchase amount — implying diverse buying behavior.                              |

---

## 🧩 Visualization Highlights

| Visualization           | Purpose                                            |
| ----------------------- | -------------------------------------------------- |
| Histograms & KDE Plots  | Understand purchase and rating distributions       |
| Bar Charts              | Show frequency by category, gender, and season     |
| Boxplots & Violin Plots | Compare effects of discounts, promos, and shipping |
| Heatmap                 | Visualize correlations among numeric variables     |
| Treemap                 | Show product category share in total sales         |
| Pie Chart               | Show gender-based purchase share                   |
| Countplots              | Show subscription status and frequency relations   |

All visualizations were designed using *modern professional color palettes* — like mako, rocket, crest, and icefire — ensuring:

* No repeated colors
* Distinct monochromatic shading
* Clear, premium, presentation-ready visuals

---

## 📈 Insights Summary

| Focus Area                | Findings                                 |
| ------------------------- | ---------------------------------------- |
| *Top Performers*        | Clothing category, Size M, Olive color   |
| *Customer Type*         | Balanced male-female shoppers aged 26–45 |
| *High Sales Season*     | Spring                                   |
| *Popular Shipping*      | Free Shipping                            |
| *Average Spending*      | ~$60 per customer                        |
| *Average Review Rating* | 3.7 / 5                                  |
| *Top Locations*         | Montana, California, Idaho               |

---

## 🎯 Business Impact

These insights help businesses:

* Spend more on ads in the states where you have the most buyers, like Montana, California, and Idaho.

* Keep extra clothes and accessories in stock, and offer more deals on them, since these bring in the most money.

* Start Spring sales and special customer rewards early.

* Make subscriptions better by giving more rewards or offers that match what each person likes.

* Always offer free shipping — it’s a big reason why people buy.

* Use the shopping data to send marketing emails that show items and deals in the colors or sizes people want.

---

## ✨ Final Conclusion

This project shows how *EDA using Python* can reveal hidden insights into customer behavior and preferences.
By analyzing spending, reviews, and seasonal trends, we can identify what drives sales and where improvement is needed.


---