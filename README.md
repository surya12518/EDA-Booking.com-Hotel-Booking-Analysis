EDA Hotel Booking Analysis
🏨 Hotel Booking Data Analysis (EDA)

This project focuses on Exploratory Data Analysis (EDA) of a hotel booking dataset from Booking.com, aiming to uncover actionable insights that can help:

• Optimize hotel revenue • Reduce booking cancellations • Improve overall customer satisfaction

📂 Dataset Overview

The dataset contains hotel booking records, including variables like:

• Reservation status • Lead time • Room type • Country • Booking source • Pricing and more

Initial steps include:

• Viewing column names and data types • Identifying and handling missing values and duplicate entries

🧹 Data Wrangling

We addressed the following issues:

• Missing Values: Imputed for columns such as children, country, agent, and company

• Outliers: Detected in lead_time and adr using boxplots and handled using the IQR method

• Duplicates: Removed to ensure data integrity

📊 Data Aggregation & Insight Extraction

Performed group-wise aggregations and transformations to uncover insights, such as:

• Average lead time per reserved room type • Top countries by booking volume • Cancellation rate by market segment • And much more...

All data manipulations and insights were documented step-by-step.

📈 Data Visualization

🔹 Univariate Analysis

• Visualized distributions of individual variables like room_type, lead_time, and customer_type

• Tools used: Bar charts, Pie charts, Histograms, Count plots, Word cloud

🔸 Bivariate Analysis • Explored relationships between two variables at a time

• Examples: o reserved_room_type vs. assigned_room_type

o lead_time vs. reservation_status

• Tools used: Box plots, Heatmaps, Bar plots

🔺 Multivariate Analysis • Analyzed the interaction between multiple variables

• Example: lead_time, adr, and days_in_waiting_list in relation to reservation_status

• Tool used: Pair plots

💡 Key Insights & Business Impact

• Identified patterns in cancellation rates linked to specific market segments • Highlighted how room upgrades or mismatches influence customer satisfaction • Showed impact of booking lead time on average daily rate (ADR) • Insights provided actionable recommendations for pricing strategies and customer engagement

✅ Conclusion & Business Solutions

The analysis concludes with:

• Data-driven solutions aligned with the business objectives • Strategies to improve booking retention • Ideas for dynamic pricing models based on customer behavior

🛠 Tools Used

• Python • Pandas, NumPy • Matplotlib, Seaborn • WordCloud • Colab Notebook
