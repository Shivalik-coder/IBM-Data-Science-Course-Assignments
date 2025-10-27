# SpaceX Falcon 9 Landing Prediction

This project is the capstone of the **IBM Data Science Professional Certificate** on Coursera.  
It applies the full data science methodology to predict the success of SpaceX Falcon 9 rocket landings using historical launch data.

---

## Project Overview

The goal of this project is to build a predictive model that can estimate whether a Falcon 9 first stage will land successfully.  
SpaceX’s ability to reuse rockets significantly reduces launch costs, so predicting successful landings has real-world value.

---

## Key Steps

1. **Data Collection:**
   - Collected launch data using the SpaceX REST API and web scraping.

2. **Data Wrangling:**  
   - Cleaned and structured data using 'pandas' and 'numpy'.  
   - Extracted relevant features such as payload mass, orbit type, and launch site.

3. **Exploratory Data Analysis (EDA):**  
   - Visualized relationships between launch features and landing outcomes using 'matplotlib', 'seaborn', and 'plotly'.

4. **Interactive Visualizations:**  
   - Created geographical maps using 'folium'.  
   - Built interactive dashboards with 'plotly dash' to analyze success rates by site and orbit.

5. **Model Development:**  
   - Implemented classification models (Logistic Regression, Decision Tree, KNN, SVM).  
   - Tuned hyperparameters and compared performance using accuracy and confusion matrices.

---

## Results

- **Best Model:** Support Vector Machine(SVM)  
- **Accuracy:** 83%  
- **Key Insights:**  
  - Launch site and payload mass have a strong correlation with landing success.  
  - The model can reasonably predict future landing outcomes given similar conditions.

---

## Tools & Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly, Folium  
- Scikit-learn  
- Dash (for dashboard creation)  
- Jupyter Notebook

---
## 📁 Repository Structure
