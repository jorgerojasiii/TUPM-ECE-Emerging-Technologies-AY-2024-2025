# 📘 Capstone Project: Lifestyle and Learning – Predicting Student Performance

---

## 🎥 Project Demonstration

Watch our capstone project demonstration video here: 
🔗 [Watch the Demo](YOUR_YOUTUBE_LINK_HERE)

---

## 👨‍💻 Proponents
**Aaron Edcel Pasaporte**  
**Jorge R. Rojas III**  
Emerging Technologies – BSECE 4B

---

## 📌 Overview

This capstone project investigates the impact of student lifestyle habits on academic performance. As education becomes more data-driven, understanding how factors like sleep, screen time, study routines, diet, and mental wellness influence performance can guide better learning strategies and institutional policies.

We developed a data science pipeline to analyze these relationships, uncover hidden patterns among students, and build predictive models that estimate final exam scores based on lifestyle indicators.

---

## 🎯 Objectives

1. **Determine** statistical relationships between student lifestyle habits and academic outcomes.
2. **Group** students into clusters based on similar lifestyle characteristics using unsupervised learning.
3. **Develop predictive models** using machine learning to forecast final exam performance from lifestyle data.
4. **Extract actionable insights** that can be used by students, teachers, and administrators to enhance educational outcomes.

---

## 🧠 Research Questions

- Which lifestyle factors have the most significant influence on academic performance?
- Can students be meaningfully grouped based on lifestyle patterns?
- How accurately can machine learning models predict a student's final score based on their lifestyle?

---

## 🛠️ Methodology

### 📊 Data Collection & Preprocessing
- A structured dataset was used containing student lifestyle features (e.g., study hours, sleep time, mental health indicators) and corresponding final exam scores.
- Missing data handling, normalization, and feature encoding were performed for clean analysis.

### 🔍 Exploratory Data Analysis (EDA)
- Visualizations such as histograms, pair plots, and heatmaps helped uncover trends and correlations.
- Insights such as the positive influence of consistent study habits and sleep routines were observed.

### 🧪 Clustering (Unsupervised Learning)
- **KMeans Clustering** was applied to segment students into distinct behavioral groups.
- **PCA (Principal Component Analysis)** was used to reduce dimensionality for better cluster visualization.
- Identified clusters revealed student archetypes (e.g., "High Achiever with Healthy Habits", "Low Performer with High Screen Time").

### 🤖 Predictive Modeling (Supervised Learning)
- Multiple regression models were trained and evaluated, including:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Support Vector Machine (SVM)
- **Model Evaluation Metrics**:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score (coefficient of determination)

---

## 📈 Results

### 📌 Clustering Output
Using KMeans and PCA visualization, students were segmented into 3 primary clusters:
1. **Cluster 0**: Students with balanced lifestyles and consistent study habits – highest average scores.
2. **Cluster 1**: Students with erratic schedules and low physical activity – lowest performance.
3. **Cluster 2**: Moderate performers with high screen time but above-average study time.

This segmentation provided valuable insight into how lifestyle patterns group together and influence academic results.

### 📌 Model Performance Summary

| Model                 | MAE     | RMSE    | R² Score |
|----------------------|---------|---------|----------|
| **Linear Regression** | 7.03    | 9.13    | 0.42     |
| **Decision Tree**     | 3.66    | 5.28    | 0.78     |
| **Random Forest**     | 2.84    | 4.27    | **0.86** |
| **SVM**               | 6.43    | 8.67    | 0.48     |

- **Best Performer**: Random Forest Regressor achieved the highest accuracy with the lowest error rates and the highest R² score.
- Linear models performed decently but were outperformed by tree-based algorithms, which captured nonlinear interactions between lifestyle factors more effectively.

---

## 📊 Key Findings

- **Study Hours and Sleep** were positively correlated with higher final exam scores.
- **Excessive Screen Time** and poor dietary habits were associated with lower academic performance.
- Clustering revealed distinct student profiles, offering potential for targeted interventions.
- **Random Forest** achieved the highest accuracy and generalization in predicting scores.

---

## 📚 Conclusion

This project demonstrates that lifestyle choices significantly influence academic outcomes. By integrating data analysis and machine learning, we not only identified impactful habits but also created a predictive model capable of estimating performance with a high degree of accuracy.

These findings can empower:
- **Students** to self-reflect and adjust their habits.
- **Educators** to provide personalized guidance.
- **Institutions** to develop supportive policies and well-being programs.

---

## 📁 Repository Contents

- `Capstone2.ipynb` – Main Jupyter Notebook with complete analysis, modeling, and visualizations.
- `README.md` – Project summary and documentation.

---

## 🧰 Tools & Technologies Used

- **Programming Language**: Python
- **Libraries**:  
  - `pandas`, `numpy` – Data manipulation  
  - `matplotlib`, `seaborn` – Data visualization  
  - `scikit-learn` – Machine learning algorithms and evaluation  
- **Platform**: Jupyter Notebook

---

## 📅 Course Information

**Course**: Emerging Technologies  
**Program**: Bachelor of Science in Electronics Engineering – BSECE 4B  
**Institution**: Technological University of the Philippines - Manila  
**Academic Year**: 2024–2025  

---

## ✅ Future Work

- Collecting a larger and more diverse dataset for generalization.
- Including additional factors like socioeconomic status, extracurricular activities, and motivation scores.
- Deploying the model in an interactive dashboard for real-time lifestyle evaluation and performance prediction.

---

## 📬 Contact

For questions or collaboration inquiries:  
📧 Aaron Edcel Pasaporte – aaronedcel.pasaporte@tup.edu.ph  
📧 Jorge R. Rojas III – jorge.rojasiii@tup.edu.ph
