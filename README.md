# 🎓 Student Satisfaction Survey Analysis

This project analyzes **student feedback data** collected through a survey (Google Forms export).  
The aim is to understand **satisfaction trends**, map **ratings to sentiment categories** and generate **actionable recommendations** for improving campus events and learning experiences.



##  Project Objectives
1. **Data Cleaning & Preparation**  
   - Import CSV, handle duplicates, missing values, and formatting.  
   - Generate an overview: shape, data types, metadata, and statistical summary.  

2. **Quantitative Feedback Analysis (Ratings)**  
   - Study distribution of ratings (1–5 scale).  
   - Compare responses across departments and courses.  

3. **Sentiment Analysis (Ratings-Based)**  
   - Map ratings to sentiment categories:  
     - Positive → Ratings of 4 and 5  
     - Neutral → Rating of 3  
     - Negative → Ratings of 1 and 2  
   - Calculate sentiment distribution overall and by department.  

4. **Visualization of Satisfaction Trends**  
   - Bar charts, pie charts, and heatmaps using **Matplotlib** and **Seaborn**.  
   - Visualize rating distribution, average scores per question, and sentiment breakdowns.  

5. **Actionable Recommendations**  
   - Highlight areas of improvement based on feedback patterns.  
   - Support decision-making for better student engagement and academic delivery.  



##  Tools & Libraries
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Data Cleaning:** Handling duplicates, formatting, missing values  
- **Visualization:** Bar plots, heatmaps, pie charts, line plots  
- **Sentiment Mapping:** Ratings → Sentiment (Positive, Neutral, Negative)  
- **Power BI** for interactive dashboarding  



##  Key Insights
- **Most feedback is Positive** (70% of responses).  
- **Neutral responses are very low** (0.18%).  
- **Negative feedback is minimal** (0.12%).  
- Average student satisfaction score: **3.89 / 5**.  



## Visual Highlights

###  Python Visualizations
- Overall rating distribution  
- Sentiment distribution by department  
- Average score per question  
- Trends of average scores across questions  

### Power BI Dashboard
Below is a sample **dashboard** built in Power BI to present insights interactively:  

![Student Satisfaction Dashboard]([https://raw.githubusercontent.com/Harriet-ngomo/FUTURE_DS_03/5e3b018cb5b0df3da7fef5adc93f2a38b46ae289/images/Screenshot%202025-09-03%20153002.png](https://github.com/Harriet-ngomo/FUTURE_DS_03/blob/90259f2fe3c3216c77dfe169b673493e4553b688/images/Screenshot%202025-09-03%20161717.png)

![Student Satisfaction Dashboard](https://github.com/Harriet-ngomo/FUTURE_DS_03/blob/cf076c87e36f30ae949c0c348cbd33538d9ac336/images/Screenshot%202025-09-02%20223354.png)


## 📂 Dataset Overview
- **Shape:** 580 rows × 12 columns  
- **Key Columns:**  
  - `Questions` → Survey questions  
  - `Weightage 1–5` → Counts of ratings  
  - `Average/ Percentage` → Average rating per question  
  - `Basic Course` → Department/Program name  

---

##   Future Improvements
- Incorporate **open-text comment sentiment analysis** (TextBlob/VADER).  
- Apply **clustering** to group similar student feedback patterns.  
- Automate **dashboard creation** in Power BI/Tableau.  

---

## Author
 **Harriet Ngomo**  
- Data Analyst | Data Scientist | Economic Analyst  
-  [GitHub](https://github.com/Harriet-ngomo)  

✨ *Transforming raw student feedback into actionable insights for better learning outcomes.*  
