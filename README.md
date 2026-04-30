# 🧾 Food Delivery Order Behavior Analysis (Zomato Dataset)

An analytical project focused on understanding customer order behavior, delivery performance, and restaurant trends using real-world food delivery data to derive actionable business insights.

---

# 🎯 Problem Statement

Food delivery platforms face challenges in maintaining high customer satisfaction while ensuring efficient delivery operations. Delays in delivery, unclear demand patterns, and ineffective pricing strategies can negatively impact user experience and overall business performance.

---

# 🎯 Objective

To analyze customer order behavior, delivery performance, and restaurant trends in order to:

* Improve delivery efficiency
* Enhance customer satisfaction
* Identify high-performing cuisines and locations
* Enable data-driven business decisions

---

# 🛠️ Tools & Technologies

* **Python (Pandas, NumPy)** → Data cleaning and exploratory analysis
* **Power BI** → Interactive dashboard and visualization
* **Kaggle (Zomato Dataset)** → Real-world dataset

---

# 📊 Key Business Questions

* When are peak order periods?
* Which cuisines are most popular vs highest rated?
* Which locations generate the highest demand?
* What factors impact delivery time?
* How does delivery time affect customer ratings?
* Does pricing influence customer satisfaction?
* What improvements can be recommended?

---

# 📊 Business Questions & Answers

### 1. When are peak order periods?

* Not analyzed due to lack of time-based data in the dataset

---

### 2. Which cuisines are most popular vs highest rated?

* **Most popular:** North Indian, Fast Food, Chinese
* **Highest rated:** Mithai, Ice Cream, Healthy Food

👉 Popular cuisines do not necessarily provide the best customer experience

---

### 3. Which locations generate the highest demand?

* Kolkata, NCR, Hyderabad, Lucknow, Kanpur

👉 These regions represent high-demand operational zones

---

### 4. What factors impact delivery time?

* Direct factors such as traffic and distance are not available

👉 However, variation in delivery time suggests differences in operational efficiency

---

### 5. How does delivery time affect ratings?

* Faster delivery (<20 minutes) → higher ratings (~4.0+)
* Ratings decrease as delivery time increases

👉 There is a strong negative relationship between delivery time and customer satisfaction

---

### 6. Does pricing influence customer satisfaction?

* Ratings remain approximately constant across price ranges

👉 Pricing has minimal impact on customer satisfaction

---

### 7. What improvements can be recommended?

* Optimize delivery speed
* Focus on high-demand locations
* Promote high-rated niche cuisines
* Improve operational efficiency

---

# ⚙️ Approach

### 1. Data Cleaning (Python)

* Removed missing values
* Converted data types (rating, price, delivery time)
* Created price categories
* Split and normalized the **cuisine column** (critical preprocessing step)

---

### 2. Data Analysis

* Grouped delivery time into bins
* Analyzed relationship between delivery time and ratings
* Identified top cuisines and high-demand locations
* Compared pricing against customer satisfaction

---

### 3. Visualization (Power BI)

Developed an interactive dashboard featuring:

* KPI Cards (Average Rating, Price, Delivery Time)
* Top cuisines analysis
* Location-based demand insights
* Delivery Time vs Rating trends
* Price vs Rating comparison
* Key insights section

---

# 📈 Key Insights

✔ **Insight 1: Delivery Speed Matters Most**

* Clear negative relationship between delivery time and ratings
* Deliveries under 20 minutes achieve highest ratings (~4.0+)
* Ratings decline as delivery time increases

👉 Faster delivery significantly improves customer satisfaction

---

✔ **Insight 2: Price Has Minimal Impact**

* Ratings remain nearly constant across all price categories

👉 Customers prioritize service quality over pricing

---

✔ **Insight 3: Popular ≠ High Quality**

* North Indian & Fast Food dominate in availability
* However, niche cuisines such as:

  * Mithai
  * Ice Cream
  * Healthy Food

  achieve higher average ratings

👉 Less saturated categories tend to deliver better customer experiences

---

# 🧠 Root Cause Interpretation & Recommendations

This section focuses on identifying underlying causes behind observed patterns and proposing actionable improvements.

---

## 🔻 Problem 1: Low Ratings for Slower Deliveries

### 📉 Possible Causes:

* Inefficient delivery routing
* Poor order batching or allocation
* Lack of real-time tracking optimization
* Operational delays during peak demand

### 💡 Recommendations:

* Optimize delivery logistics using route optimization algorithms
* Improve order allocation systems
* Introduce real-time tracking and dynamic routing
* Increase delivery capacity during peak hours

---

## 🔻 Problem 2: Underutilization of High-Quality Cuisines

### 📉 Possible Causes:

* Low visibility of niche cuisines
* Marketing bias toward popular categories
* Limited discovery for users

### 💡 Recommendations:

* Promote high-rated niche cuisines on platform homepage
* Use recommendation systems to highlight quality over popularity
* Offer incentives for users to explore new cuisines

---

## 🔻 Problem 3: High Demand Concentration in Specific Locations

### 📉 Possible Causes:

* Uneven distribution of restaurants
* Infrastructure and urban demand concentration
* Limited service expansion

### 💡 Recommendations:

* Allocate more delivery resources in high-demand areas
* Expand restaurant partnerships in growing regions
* Use demand forecasting for better resource planning

---

## 🔻 Problem 4: Pricing Not Driving Satisfaction

### 📉 Possible Causes:

* Customers prioritize service quality over cost
* Price differences not significant enough to impact perception

### 💡 Recommendations:

* Focus on improving delivery speed and service reliability
* Avoid unnecessary price-based competition
* Invest more in experience rather than discounts

---

# 📈 Analytical Features Implemented

* Delivery time vs rating analysis
* Cuisine popularity vs satisfaction comparison
* Location-based demand analysis
* Price vs customer satisfaction evaluation
* Interactive dashboard with dynamic filtering

---

# 🧠 What This Project Demonstrates

* Strong understanding of **customer behavior analytics**
* Ability to derive **actionable insights from real-world data**
* Data-driven problem-solving mindset
* Proficiency in **Python and Power BI integration**
* Effective business-oriented storytelling

---

# 🚀 Project Outcome

The analysis highlights that **delivery speed is the most critical factor influencing customer satisfaction**, while pricing has minimal impact.

By improving delivery efficiency and promoting high-quality offerings, businesses can significantly enhance user experience and retention.

---
