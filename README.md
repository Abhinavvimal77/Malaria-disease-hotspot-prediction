🦟 Malaria Hotspot Prediction: An Early Warning System. 

This project implements a time-series machine learning model to predict daily malaria outbreak hotspots up to six months in advance for districts in Pakistan. By leveraging historical case data and critical climatic factors, this system identifies high-risk areas, allowing public health officials to target interventions (like spraying and net distribution) before a major outbreak occurs.

🛠️ Technology Stack.

--> Python (Pandas, NumPy) for Data Processing.

--> Scikit-learn (Random Forest) for Modeling and Prediction.

--> Seaborn & Matplotlib for Visualization.

--> Joblib for model persistence.

🔬 Top 3 Predictive Factors
The model's strong performance is driven by the delayed effect of weather:

--> Rainfall 30 Days Ago: The most crucial predictor, aligning with the mosquito breeding cycle.

--> Humidity 30 Days Ago: High past humidity supports mosquito survival.

--> Rainfall 7 Days Ago: Recent rain helps sustain existing breeding grounds.


