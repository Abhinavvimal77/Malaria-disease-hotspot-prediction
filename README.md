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

⚙️ Repository Structure
Malaria_Hotspot_Predictor/
├── cases.csv                                                 # Input CSV file of cases(cleaned)
├── features.csv                                              # Input CSV file of features related to malaria cases(cleaned)
├── Pakistan_malaria_prediction _project-checkpoint.ipynb     # Main training/prediction scripts
└── README.md                                                 


🏃 Getting Started
--> Clone the Repository: git clone [[Your Repo URL](https://github.com/Abhinavvimal77/Malaria-disease-hotspot-prediction)]

--> Install Dependencies: pip install -r requirements.txt

--> Run: Execute the primary script (e.g., python src/train_model.py) to reproduce the model and generate the forecast report.


