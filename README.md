# ⚡ Electric Vehicle (EV) Charge Demand Prediction

AICTE Internship Project

This repository presents a complete data science and machine learning solution to forecast Electric Vehicle (EV) adoption trends over time. The project aims to support policy makers, infrastructure planners, and clean energy stakeholders with data-driven insights.

---

## 🚀 Project Overview

With the rapid global shift toward sustainable transportation, accurate EV adoption forecasting is crucial for planning charging infrastructure and policy frameworks.

This project:
- Analyzes historical EV registration data  
- Identifies growth trends and seasonal patterns  
- Builds machine learning models for EV adoption prediction  
- Forecasts future EV demand using time-aware features  
- Provides an **interactive Streamlit dashboard** for decision-making  

---

## 🧠 Technologies & Tools Used

| Category | Tools |
|--------|------|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Plotly |
| Machine Learning | Scikit-learn, XGBoost, Prophet |
| Dashboard | Streamlit |
| Environment | Jupyter Notebook |


---

## 📊 Key Features

- ✔ Data Cleaning & Preprocessing  
- ✔ Exploratory Trend Analysis  
- ✔ Feature Engineering (lag features, rolling averages)  
- ✔ Random Forest–based Forecasting Model  
- ✔ Model Evaluation (MAE, MSE, R²)  
- ✔ Interactive Web Dashboard 

---

### 📁 Project Structure

```
AICTE_Internship/
│
├── EV_Adoption_Forcasting.ipynb                             # Main Jupyter notebook
├── Electric_Vehicle_Population_Size_History_By_County_.csv  # Raw dataset
├── preprocessed_ev_data.csv                                 # Cleaned & preprocessed data
├── forecasting_ev_model.pkl                                 # Trained ML model (saved)
├── RF_Tree.png                                              # Visualization of Random Forest tree
├── README.md                                                # Project documentation
├── desktop.ini                                              # System-generated file
└── requirements.txt                                         # Python dependencies

```
## 📊 Model Performance

The Random Forest Regressor model provides:
- Feature importance analysis
- Time series validation
- Multiple evaluation metrics (MAE, MSE, R²)
- Prediction confidence intervals

## 🔧 Usage

1. **Run the Jupyter Notebook**:
```
jupyter notebook EV_Adoption_Forcasting.ipynb
```

2. **Or run as Python script**:
```
The notebook can be converted to a Python script for automated forecasting.
```

Project Link: [https://github.com/yourusername/ev-adoption-forecasting](https://github.com/yourusername/ev-adoption-forecasting)

## 🙏 Acknowledgments

- Washington State Department of Licensing for providing the dataset
- Kaggle community for data sharing
- Open source contributors of the used libraries

---
## OUTPUT:
<img width="1436" height="441" alt="image" src="https://github.com/user-attachments/assets/e66ba9d0-beec-4068-8c69-30d881b34244" />

Main Dashboard Homepage Overview
- The homepage features a sleek, modern design with a dark theme background and EV charger imagery.
- Displays project title: "EV Adoption Forecast Dashboard" with a subtitle highlighting AI-driven sustainable transportation planning.
- Includes a dropdown to select a county and instantly view forecast results.
- Brief description provided to explain the dashboard’s purpose in supporting policymakers and planners.

<img width="1436" height="441" alt="image" src="https://github.com/user-attachments/assets/b838a017-58d5-446e-b8a4-a4375dfa8eb8" />

Forecast Output: Cumulative EV Trend (Ada County)
- The graph displays historical vs. forecasted cumulative EV registrations for Ada County from 2018 to 2027.
- Orange line represents actual past EV adoption, while the blue line projects the next 3 years using ML predictions.
- A strong upward trend is visible, indicating an expected increase of 80% in EV adoption over the forecast period.
- This visualization helps stakeholders make informed decisions about charging infrastructure and policy planning.

<img width="1176" height="171" alt="image" src="https://github.com/user-attachments/assets/77862cc4-61d3-4a3a-97f9-1be09a069ca4" />
<img width="1176" height="596" alt="image" src="https://github.com/user-attachments/assets/40c99dc1-4410-4ced-a8d5-637b419fc782" />

---
🎓 Internship Context

This project was developed as part of the AICTE Internship Program to demonstrate practical application of:
- Data analytics
- Machine learning
- Time-series forecasting
- Real-world policy-driven problem solving

---
🔮 Future Scope:
- Integrate real-time EV registration APIs
- Predict charging station demand
- Extend forecasting to national-level datasets
- Implement deep learning models (LSTM, Temporal CNN)

---
🙏 Acknowledgments:
- Washington State Department of Licensing
- Kaggle Community
- Open-source contributors

---
## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Note**: This project is for educational and research purposes. For production use in urban planning, additional validation and domain expert consultation is recommended.
