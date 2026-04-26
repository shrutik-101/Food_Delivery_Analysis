🧾 Food Delivery Order Behavior Analysis (Zomato Dataset)

🎯 Problem Statement

Food delivery platforms face challenges in maintaining high customer satisfaction while ensuring efficient delivery operations. Delays in delivery, unclear demand patterns, and ineffective pricing strategies can negatively impact user experience and business performance.

🎯 Objective

To analyze customer order behavior, delivery performance, and restaurant trends to:

Improve delivery efficiency
Enhance customer satisfaction
Identify high-performing cuisines and locations
Support data-driven decision-making

🛠️ Tools & Technologies
Python (Pandas, NumPy) → Data cleaning & analysis
Power BI → Dashboard & visualization
Kaggle Dataset (Zomato) → Real-world data

📊 Key Business Questions
When are peak order periods?
Which cuisines are most popular vs highest rated?
Which locations generate the highest demand?
What factors impact delivery time?
How does delivery time affect customer ratings?
Does pricing influence customer satisfaction?
What improvements can be recommended?

📊 Business Questions & Answers
1. When are peak order periods?
Not analyzed (dataset lacks time-based data)
2. Which cuisines are most popular vs highest rated?
Most popular: North Indian, Fast Food, Chinese
Highest rated: Mithai, Ice Cream, Healthy Food
👉 Popular ≠ highest satisfaction
3. Which locations generate the highest demand?
Kolkata, NCR, Hyderabad, Lucknow, Kanpur
👉 High-demand operational zones
4. What factors impact delivery time?
Direct factors (traffic, distance) not available
👉 Variation suggests operational efficiency differences
5. How does delivery time affect ratings?
Faster delivery (<20 mins) → higher ratings (~4.0+)
Ratings decrease as delivery time increases
👉 Strong negative relationship
6. Does pricing influence customer satisfaction?
Ratings remain ~constant across price ranges
👉 Minimal impact of price on satisfaction
7. What improvements can be recommended?
Optimize delivery speed
Focus on high-demand locations
Promote high-rated niche cuisines
Improve operational efficiency

⚙️ Approach
1. Data Cleaning (Python)
Removed missing values
Converted data types (rating, price, delivery time)
Created Price Categories
Split and normalized Cuisine column (important step)
2. Data Analysis
Grouped delivery time into bins
Analyzed rating vs delivery time
Identified top cuisines and locations
Compared price vs customer satisfaction
3. Visualization (Power BI)
Built interactive dashboard including:
KPI Cards (Avg Rating, Price, Delivery Time)
Top Cuisines
Top Locations
Delivery Time vs Rating trend
Price vs Rating analysis
Key Insights section

📈 Key Insights
✔ Insight 1: Delivery Speed Matters Most

There is a clear negative relationship between delivery time and customer ratings.

Deliveries under 20 minutes → highest ratings (~4.0+)
Ratings decline as delivery time increases

👉 Conclusion: Faster delivery significantly improves customer satisfaction

✔ Insight 2: Price Has Minimal Impact

Average ratings remain almost constant across all price categories

👉 Conclusion: Customers value service quality over pricing

✔ Insight 3: Popular ≠ High Quality
North Indian & Fast Food dominate in availability
But niche cuisines like:
Mithai
Ice Cream
Healthy Food
have higher average ratings

👉 Conclusion: Less crowded categories often deliver better experiences

💡 Business Recommendations
🚀 Optimize delivery logistics to reduce delivery time
📍 Focus on high-demand locations (Kolkata, NCR, etc.)
🍽️ Promote high-rated niche cuisines
📊 Use demand insights for better resource allocation
⚡ Improve operational efficiency during peak hours

📌 Final Conclusion

Customer satisfaction in food delivery is primarily driven by speed and service quality, not pricing. Businesses that optimize delivery time and focus on high-quality offerings can significantly improve user experience and retention.



