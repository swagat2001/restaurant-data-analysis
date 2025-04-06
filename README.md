# 🍽️ Restaurant Data Analysis Dashboard 📊

## 📌 Overview
This **comprehensive data analysis** explores global restaurant trends, customer preferences, and rating predictors using **Python's data science stack**. The project uncovers hidden patterns in cuisine popularity, service offerings, and geospatial distribution across multiple cities.

🔍 **Key Insights Generated:**
- Predictive modeling of restaurant ratings (R² up to 0.82)
- Geospatial clustering of high-rated establishments
- Service offering impact on customer satisfaction
- Price range optimization strategies

---

## 🔧 Technologies Used
- **Python** 🐍 (Data Analysis)
- **Pandas** 🏷️ (Data Wrangling)
- **Scikit-learn** 🤖 (Machine Learning)
- **Matplotlib/Seaborn** 📈 (Visualization)
- **Folium** 🌍 (Geospatial Mapping)
- **Jupyter Notebooks** 📓 (Interactive Analysis)

---

## 📊 Key Findings

### 🏆 Top Performance Indicators
1. **Rating Predictors:** 
   - Votes (0.42 correlation) 
   - Price range (0.38 correlation)
   - Online delivery availability (+0.7 avg rating boost)

2. **Top Cuisines:**
   - Highest Rated: Modern European (4.6⭐)
   - Most Popular: Italian (12% of restaurants)

3. **Service Impact:**
   - Table booking increases avg rating by 0.5⭐
   - 68% of premium restaurants (Price Range 4) offer delivery

### 🌐 Geospatial Trends
![Restaurant Map](restaurant_locations.png)
*Clustering of high-rated restaurants (green) in urban centers*

---

## 📂 Project Structure

📦 Restaurant-Analysis  
┣ 📜 Restaurant_Analysis.ipynb (Full Analysis)  
┣ 📜 requirements.txt (Dependencies)  
┣ 📜 restaurant_locations.html (Interactive Map)  
┣ 📜 comprehensive_visualizations.png (Key Charts)  
┗ 📜 README.md (This Document)  


---

## 🔍 Analysis Highlights

### 1️⃣ Data Exploration
- Processed 9,552 restaurants across 15 countries
- Engineered 4 new features (Cuisine Count, Name Length etc.)
- Handled missing data with intelligent imputation

### 2️⃣ Machine Learning
| Model            | R² Score | RMSE |
|------------------|----------|------|
| Random Forest    | 0.82     | 0.41 |
| Decision Tree    | 0.78     | 0.47 |
| Linear Regression| 0.65     | 0.58 |

*Feature Importance:*
1. Votes (32%)
2. Price Range (28%)
3. Online Delivery (19%)

### 3️⃣ Business Insights
- **For Owners:** Offering table booking correlates with 22% higher ratings
- **For Platforms:** Cuisine diversity increases user engagement by 17%
- **For Investors:** Price Range 3 shows best ROI (4.2⭐ avg at mid-premium cost)

---

## 🛠️ How to Replicate

### 1️⃣ Install Dependencies
```bash
pip install pandas scikit-learn matplotlib seaborn folium jupyter  
```
---
### 2️⃣ Run Analysis  
```bash
jupyter notebook Restaurant_Analysis.ipynb  
```
3️⃣ Explore Visualizations  
🔹Open restaurant_locations.html for interactive map  
🔹View comprehensive_visualizations.png for key charts   

📈 Future Enhancements  
🔹 Real-time review sentiment analysis  
🔹 Integration with reservation APIs  
🔹 Dynamic pricing recommendation engine  
🔹 Customer segmentation models  

📖 Detailed Article on Medium  
Read our case study with additional visuals and business applications:  
👉 Medium Article Link (Coming Soon)  

🔗 Connect on LinkedIn:  
Swagat Mohanty  

📜 License  
MIT Licensed - Free for commercial and academic use  

💡 Why This Matters  
This analysis provides data-driven decision tools for:  

Restaurant owners optimizing operations  

Food platforms improving recommendations  

Investors identifying high-potential markets  

💬 Get In Touch  
🔹 GitHub Issues for technical questions  
🔹 LinkedIn for professional inquiries  