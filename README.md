# End-to-End-Heart-Disease-Prediction-Project
**Project Objective** : Cardiovascular diseases are the leading cause of death worldwide. Our objective was to build an automated machine learning pipeline to detect heart disease using clinical markers. In healthcare data science, our core focus isn't just absolute accuracy
**Key EDA Discoveries**: • Our Exploratory Data Analysis revealed three vital trends:
	1. Target Balance: The data is naturally well-balanced between disease and non-disease cases, meaning no artificial class weight fixing was required.
	2. MaxHR Trend: There is a clear clinical cluster showing that as patients age, a lower maximum heart rate achieved (MaxHR) correlates strongly with positive heart disease.
	3. Chest Pain Paradox: Counter-intuitively, patients flagged with completely 'Asymptomatic' chest pain (ASY) actually displayed the highest proportional rate of heart disease.  
**Project Limitations & Future Scope (The Conclusion)**:While our pipeline is highly effective, it has clear boundaries. The dataset is purely clinical and lacks modern lifestyle indicators like nutrition habits, sleep patterns, or smoking frequency. Moving forward, we intend to test gradient boosting frameworks like XGBoost across larger, multi-center hospital registries to improve generalization.
