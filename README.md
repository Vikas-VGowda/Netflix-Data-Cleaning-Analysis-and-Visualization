# Netflix Data Analysis & Content Classification

---

##  Project Overview

Netflix has a vast library of movies and TV shows from different countries, genres, and time periods. This project performs an end-to-end data analysis and machine learning workflow to understand content patterns and classify content types (Movies vs TV Shows).

The project combines data cleaning, exploratory data analysis (EDA), visualization, and machine learning to derive meaningful insights from Netflix data.

---

##  Objectives

- Understand the distribution of Netflix content (Movies vs TV Shows)  
- Perform exploratory data analysis (EDA) with insights  
- Analyze trends in genres, countries, and content growth over time  
- Build and evaluate a machine learning model to classify content  
- Extract meaningful business insights from the dataset  

---

## Dataset

- **Source:** Netflix Dataset  
- **Records:** ~8,000+ titles  
- **Features:** Title, type, genre, country, release year, duration, rating, date added  
- **Target Variable:** Type (Movie / TV Show)  

---

##  Exploratory Data Analysis (EDA)

### Key insights:

- Movies dominate the Netflix content library compared to TV Shows  
- The United States and India are among the top content-producing countries  
- Drama and Comedy are the most common genres  
- Content additions have increased significantly in recent years  
- Most content is targeted toward mature audiences (TV-MA, TV-14)  

EDA was supported with visualizations and business-focused interpretations.

---

##  Machine Learning Approach

###  Models Implemented

- Random Forest Classifier  
- Logistic Regression  

---

###  Key Techniques

- Handling missing values and data cleaning  
- Feature engineering:
  - `year_added`
  - `month_added`
  - `duration_num`
  - `main_genre`  
- Label encoding for categorical variables  
- Train-test split for evaluation  

---

###  Model Performance

- **Accuracy:** 99.5%  
- High precision and recall across both classes  
- Minimal misclassification observed  

---

##  Feature Importance

### Key factors influencing classification:

- **Duration** → Strong indicator of Movies vs TV Shows  
- **Genre** → Certain genres align with specific content types  
- **Year Added** → Reflects content trends  
- **Country** → Production patterns differ regionally  

These features play a crucial role in distinguishing content types.

---

##  Business Usage

This project can help streaming platforms to:

- Automatically classify content into Movies and TV Shows  
- Improve recommendation systems  
- Understand content trends and audience preferences  
- Support content acquisition and production strategies  

---

##  Limitations

- Based on a static dataset (not real-time updates)  
- Limited features (no user behavior or watch history)  
- High accuracy may indicate potential overfitting  
- Predictions should support decisions, not replace human judgment  

---

##  Tools & Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

##  Repository Contents

- `netflix.ipynb` → Complete analysis and ML model  
- `netflix.csv` → Dataset used  
- `README.md` → Project documentation  

---

## Author

**Vikas Gowda V**  
Aspiring Data Analyst / Data Scientist  

---

##  Conclusion

 
This project demonstrates a complete data analysis and machine learning workflow on Netflix data. By combining EDA with a highly accurate classification model, the project provides valuable insights into content trends and supports data-driven decision-making for content platforms.
