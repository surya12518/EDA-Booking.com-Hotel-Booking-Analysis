# 🏨 Hotel Booking Data Analysis (EDA)

This project focuses on **Exploratory Data Analysis (EDA)** of a hotel booking dataset sourced from **Booking.com**, with the goal of uncovering **actionable insights** to:

- 📈 Optimize hotel revenue  
- ❌ Reduce booking cancellations  
- 😀 Improve customer satisfaction  

---

## 📂 Dataset Overview

The dataset contains detailed hotel booking records, with variables such as:

- Reservation status  
- Lead time  
- Room type  
- Country  
- Booking source  
- Pricing  
- And more...

### 🔍 Initial Steps:
- Viewed column names and checked data types  
- Handled missing values and removed duplicate entries  

---

## 🧹 Data Wrangling

We cleaned and transformed the dataset by addressing the following:

### 🔧 Missing Values
- Imputed missing values for `children`, `country`, `agent`, and `company`

### 🚨 Outlier Treatment
- Identified outliers in `lead_time` and `adr` using boxplots  
- Treated them using the **Interquartile Range (IQR)** method  

### 🧽 Duplicates
- Removed duplicate records to ensure data integrity

---

## 📊 Data Aggregation & Insight Extraction

Grouped and analyzed data to extract key insights:

- 📅 Average lead time by reserved room type  
- 🌍 Top countries by booking volume  
- 💼 Cancellation rate by market segment  
- 💸 ADR trends across distribution channels  

All steps were documented clearly with corresponding code and outputs.

---

## 📈 Data Visualization

### 🔹 Univariate Analysis
- Examined individual feature distributions  
- Tools used: **Bar charts**, **Histograms**, **Pie charts**, **Count plots**, **WordCloud**

### 🔸 Bivariate Analysis
- Explored pairwise relationships  
- Examples:
  - `reserved_room_type` vs `assigned_room_type`  
  - `lead_time` vs `reservation_status`  
- Tools used: **Box plots**, **Heatmaps**, **Bar plots**

### 🔺 Multivariate Analysis
- Analyzed interactions between multiple variables  
- Example: `lead_time`, `adr`, and `days_in_waiting_list` in relation to `reservation_status`  
- Tool used: **Pair plots**

---

## 💡 Key Insights & Business Impact

- 📉 Higher cancellation rates linked to specific market segments (e.g., online bookings without deposits)  
- 🛏️ Room type mismatches can impact guest satisfaction and loyalty  
- ⏱️ Longer lead times often correlate with lower ADR, indicating potential for early bird pricing models  
- 📊 Booking source and country trends suggest targeted marketing opportunities  

---

## ✅ Conclusion & Business Recommendations

- ✳️ Implement **targeted retention strategies** for high-risk segments  
- 🏷️ Develop **dynamic pricing models** based on booking behavior  
- 📞 Encourage direct bookings to lower cancellation rates and increase margins  
- 📢 Use insights for **personalized marketing** and upselling opportunities  

---

## 🛠 Tools & Technologies

- **Python**  
- **Pandas**, **NumPy**  
- **Matplotlib**, **Seaborn**  
- **Google Colab Notebook**

---

## 📌 Status

✅ Completed EDA  
🧠 Insights documented  
📦 Ready for integration into reporting pipelines or dashboard solutions

---

