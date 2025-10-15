# 📊 Movies Project

## 🔎 Project Overview
This project explores a movie dataset using **Python**.  
The main goal is to analyze relationships between features such as **budget, gross revenue, votes, and ratings**, and identify the factors that influence a movie’s financial success.

---

## 🛠️ Tools & Libraries
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**

---

## 📂 Dataset
The dataset contains movie-related information such as:
- Movie title  
- Release year  
- Budget  
- Gross revenue  
- Votes  
- Genre, Company, and other metadata  

---

## 🔑 Steps in Analysis
1. **Data Import & Exploration**
   - Load dataset with Pandas  
   - Inspect missing values, datatypes, duplicates  

2. **Data Cleaning**
   - Handle null values (median for numeric, "Unknown" for categorical)  
   - Convert columns to correct types (e.g., `budget`, `gross`, `votes` → int)  
   - Remove duplicates  

3. **Data Visualization**
   - Scatter plots (`budget` vs `gross`)  
   - Regression plots (Seaborn)  
   - Correlation heatmaps  

4. **Feature Encoding**
   - Convert categorical data to numeric codes  

5. **Correlation Analysis**
   - Pearson correlation between features  
   - Identify strongest relationships  

---

## 📈 Key Insights
- **Budget** has the strongest positive correlation with **gross revenue** (~74.6%).  
- **Votes** also strongly correlate with **gross revenue** (~63.2%).  
- Other features (genre, runtime, etc.) show weaker correlations.  

---

## 📌 How to Run
1. Clone this repository:
   ```bash
   git clone <git@github.com:mohamed-ali-505/movies-project.git>
   pip install numpy pandas matplotlib seaborn
   jupyter notebook



