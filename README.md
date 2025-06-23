![Screenshot 2025-06-20 173623](https://github.com/user-attachments/assets/9f7d4427-b388-419b-94f5-c04d23af51be)


# 🎮 Video Game Sales Analysis using Microsoft Excel

> A technical report analyzing historical video game sales data to discover genre trends, platform dominance, and regional sales insights using Microsoft Excel.

---

## 📑 Table of Contents
1. [🎯 Introduction](#-introduction)  
2. [📚 Story of Data](#-story-of-data)  
3. [🧹 Data Splitting and Preprocessing](#-data-splitting-and-preprocessing)  
4. [📊 Pre-Analysis](#-pre-analysis)  
5. [📈 In-Analysis](#-in-analysis)  
6. [✅ Post-Analysis and Insights](#-post-analysis-and-insights)  
7. [📉 Data Visualizations & Charts](#-data-visualizations--charts)  
8. [💡 Recommendations and Observations](#-recommendations-and-observations)  
9. [🔚 Conclusion](#-conclusion)  
10. [📎 References & Appendices](#-references--appendices)  

---

## 🎯 Introduction

### 📝 Objective of the Project
Analyze video game sales data to:
- Identify sales trends
- Highlight regional performance
- Evaluate genre, publisher, and platform dynamics
- Deliver insights for marketing and strategic decisions

### ❓ Problem Being Addressed
- What are the most successful genres, platforms, and publishers globally and regionally?
- Are there consumer preference patterns over time?
- What characterizes top-selling games?

### 🧰 Tools and Methods
- **Microsoft Excel 365**: Pivot Tables, VLOOKUP, Charts, Filters, Slicers
- **Dataset**: Historical global video game sales records

---

## 📚 Story of Data

### 🔗 Data Source
- Sourced from Kaggle (public domain / aggregated from market data)

### 📁 Structure
- `vgsales.csv` — 11 columns: Rank, Name, Platform, Year, Genre, Publisher, NA_Sales, EU_Sales, JP_Sales, Other_Sales, Global_Sales

### 🌍 Key Features
- **Genre**: Consumer preference indicator
- **Platform**: Highlights dominant consoles
- **Publisher**: Shows market leaders
- **Regional Sales**: Tracks geographic differences

### ⚠️ Data Limitations
- Missing or zero values in “Year” and sales
- Publisher name inconsistencies
- Underreported Japan & “Other” regions

---

## 🧹 Data Splitting and Preprocessing

### 🧽 Cleaning Steps
- Removed incomplete or all-zero sales rows
- Normalized inconsistent publisher names
- Corrected typos

### 📉 Handling Missing Values
- Dropped rows with missing critical data

### ⚙️ Transformation
- No new features added; used existing columns

### 📊 Variable Split
- **Dependent**: Global Sales, Rank, Year, NA/EU/JP/Other Sales  
- **Independent**: Genre, Platform, Publisher, Region

### 🎮 Industry Context
- Sector: Entertainment & Gaming  
- Stakeholders: Marketers, Publishers, Developers, Retailers

---

## 📊 Pre-Analysis

### 🔎 Key Trends
- Action & Sports are top-selling genres
- PS2 leads platform-wise
- NA is the strongest sales region

### 🔗 Potential Correlations
- Platform ↔ Genre  
- Publisher ↔ Region (e.g., Nintendo in Japan)

### 💡 Early Insights
- Nintendo and EA have many top titles
- Peak sales occurred in mid-2000s

---

## 📈 In-Analysis

### 📌 Key Insights
1. Nintendo dominates top-sellers on its platforms (Wii, DS, GB)
2. **Wii Sports** leads with 82.74M global sales
3. The **Mario** & **Pokémon** franchises appear repeatedly
4. NA is the largest market, followed by EU and JP
5. GTA series (by Take-Two) breaks Nintendo’s streak
6. Regional leaders vary by title:
   - NA & EU: Wii Sports
   - JP: Pokémon
   - Other: GTA: San Andreas
7. Sports, Action, RPGs are common genres

### 📌 Excel Tools Used
- Pivot Tables  
- Region slicers  
- Filters & VLOOKUP  
- Consistency tools (Find & Replace)

---

## ✅ Post-Analysis and Insights

### ✔️ Key Findings
- Action and Sports genres lead globally
- PS2 is the top-selling platform
- Nintendo dominates unit sales
- NA is the highest sales region

### 🔄 Comparison to Expectations
- Most patterns aligned
- Greater regional differences than expected, especially in Japan

---

## 📉 Data Visualizations & Charts

### 📊 Charts Created
- 📊 Bar chart: Genre vs Global Sales  
- 🥧 Pie chart: Regional sales distribution  
- 🌲 Tree map: Global sales hierarchy  
- 📈 Line graph: Yearly sales trends  
- 🏢 Bar chart: Publisher count  
- 🎮 Bar chart: Platform sales totals

### 📊 Excel Dashboard

![Screenshot 2025-06-20 173623](https://github.com/user-attachments/assets/014c7ef8-a5f7-481e-a0fd-51dfaa715cd5)


Constructed using:
- Pivot Charts  
- Slicers  
- Shapes, Icons, Text Boxes

---

## 💡 Recommendations and Observations

### 🔧 Actionable Insights
1. **Target Action/Sports** genres for ROI (>$1.75B and $1.33B revenue)
2. **Region-specific content** (RPGs in JP, Sports in NA)
3. Build **long-term franchises** (Mario, Pokémon, GTA)
4. Explore **underperforming genres** like Strategy
5. Prioritize **offline capability** in low-infrastructure regions
6. Collaborate with **top platforms** for wider reach
7. Invest in **genre-platform aligned games** for sustained growth

### 🧠 Business Optimizations
- Budget allocation by platform/genre performance  
- Schedule releases around peak sales windows  
- Form partnerships with regional publisher leaders

### 🤯 Unexpected Outcome
- Global hits like Wii Sports underperformed in Japan → importance of cultural preferences in game design and marketing

---

## 🔚 Conclusion

### 📌 Key Learnings
- Genre-platform fit is crucial  
- Regional sales patterns shape global trends  
- A few publishers dominate industry output

### ⚠️ Limitations
- Missing or outdated sales/year info  
- No mobile or digital platform data (last update: 2011)

### 🔬 Future Exploration
- Include mobile & digital game data  
- Analyze user/critic ratings alongside sales

---

## 📎 References & Appendices

- 📄 Dataset: [Video Game Sales - Kaggle](https://www.kaggle.com/datasets/willianoliveiragibin/video-game-sales-analyze)  
- 💻 Tool: Microsoft Excel 365  
- 🛠️ Features: Pivot Tables, Charts, VLOOKUP, Filters, Slicers  

