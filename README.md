# 🎮 Predicting Game Success: Global Video Game Sales & Market Trends

## 📌 Introduction
This project explores **historical video game sales data** to uncover patterns that determine whether a game succeeds or fails.  
The dataset includes global sales, genres, platforms, user & critic reviews, and ESRB ratings.  

We analyze industry trends and create actionable insights that could guide **marketing strategy, platform investment, and campaign planning** for upcoming releases.  

---

## 📂 Dataset
**Cloud Services:** AWS S3 (data hosting and retrieval).
Source: `games.csv`  [Download](https://practicum-content.s3.us-west-1.amazonaws.com/datasets/games.csv)

https://practicum-content.s3.us-west-1.amazonaws.com/datasets/games.csv
Main fields:
- **Name** – game title  
- **Platform** – release platform (e.g., Xbox, PlayStation)  
- **Year_of_Release** – release year  
- **Genre** – game genre  
- **NA_sales, EU_sales, JP_sales, Other_sales** – sales by region (millions of USD)  
- **Critic_Score** – critic reviews (0–100)  
- **User_Score** – user reviews (0–10)  
- **Rating** – ESRB classification (e.g., Teen, Mature)  

---

## ⚙️ Methodology
The project follows six structured steps:

1. **Data Exploration**  
   - Reviewed dataset structure and missing values  
   - Standardized column names and datatypes  

2. **Data Preprocessing**  
   - Treated missing values (`NaN`, `TBD`)  
   - Converted data types (years, scores, sales)  
   - Created total sales column per game  

3. **Exploratory Data Analysis (EDA)**  
   - Trends in game releases over time  
   - Platform lifecycle (growth vs decline)  
   - Genre popularity and profitability  
   - Correlation of critic/user reviews with sales  

4. **Regional Profiles**  
   - Top 5 platforms by region (NA, EU, JP)  
   - Top 5 genres by region  
   - Impact of ESRB ratings on regional sales  

5. **Hypothesis Testing**  
   - H₀: Average user scores for Xbox One vs PC are equal  
   - H₀: Average user scores for Action vs Sports are equal  
   - Applied statistical tests with chosen α  

6. **Conclusion**  
   - Summarized market insights and practical implications for 2017 campaign planning  

---

## 📊 Key Analyses
- Sales evolution of top platforms (PlayStation, Xbox, Nintendo)  
- Distribution of sales by genre and region  
- Relationship between **reviews** (user & critic) and commercial success  
- Regional differences in preferences (NA, EU, JP)  
- Hypothesis tests validating significant differences in ratings & genres  

---

## ✅ Conclusion
This project demonstrates skills in:  
- **Python (pandas, matplotlib, seaborn, scipy)**  
- **Data cleaning & feature engineering**  
- **EDA & data visualization**  
- **Statistical hypothesis testing**  
- **Market-oriented data storytelling**  

The insights highlight how **platform lifecycle, genre, and reviews drive sales**, providing value for **strategic marketing and publishing decisions**.  

---

## 💻 Tech Stack
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- SciPy  
- Jupyter Notebook  

---

## 📈 Sample Visualization
- Sales lifecycle of platforms (PlayStation vs Xbox)  
- Boxplots of sales distributions by genre  
- Correlation scatterplots (Critic/User scores vs Sales)  
- Regional breakdowns of top platforms and genres  

---

## 🤝 Contact
Created by **[Your Name]**  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile) | [Portfolio](https://yourportfolio.com)
