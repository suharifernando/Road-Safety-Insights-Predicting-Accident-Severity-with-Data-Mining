# Road-Safety-Insights-Predicting-Accident-Severity-with-Data-Mining

 Overview
This project applies **data mining and machine learning techniques** to analyze road accident data from the UK Government Open Data portal.  
Our goal is to **predict accident severity** and **identify hidden casualty patterns** using clustering and classification models.  
The insights are adapted to inform **Sri Lanka’s public sector road safety policies**, making this project both technically rigorous and socially impactful.

---

 Objectives
- **Clustering (K-Means):** Identify high-risk groups and accident hotspots based on age, gender, casualty type, and socioeconomic background.  
- **Classification (Random Forest):** Predict accident severity using victim characteristics and environmental factors.  
- **Policy Impact:** Translate findings into actionable recommendations for Sri Lanka’s road safety planning.

---

 Dataset
- Source: [UK Government Road Safety Data 2023](https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-accidents-safety-data)  
- Key variables:
  - Age of casualty  
  - Gender  
  - Casualty type (pedestrian, cyclist, motorcyclist, car occupant, etc.)  
  - Home area type (urban/rural)  
  - IMD decile (socioeconomic status)  

---

 Methodology
1. **Data Preprocessing**
   - Handling missing values  
   - Feature selection (age, sex, casualty type, home area, IMD decile)  
   - Standardization for clustering  

2. **Clustering Analysis**
   - Elbow Method to determine optimal clusters  
   - K-Means clustering to group casualties  

3. **Classification Analysis**
   - Train/test split (80/20)  
   - Random Forest model with 100 trees  
   - Model evaluation via confusion matrix & accuracy  

---

 Results
- **Classification Accuracy:** ~78.3%  
- **Feature Importance:** Age and casualty type are the strongest predictors of accident severity.  
- **Clustering:** Revealed three distinct casualty groups (low, moderate, and high severity).  

---

 Impact on Sri Lanka
- Improved pedestrian safety in urban areas (crossings, speed limits, lighting).  
- Efficient resource allocation (ambulances in high-risk zones).  
- Data-driven policy recommendations for reducing fatalities and injuries.  

---

 Visualizations
- Boxplots of casualty age distribution  
- Feature importance plots (Random Forest)  
- Elbow Method curve for clustering  
- Cluster scatter plots (age vs casualty type, gender trends)  

---
