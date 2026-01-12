# AICTE_Internships
# ⚡ Electric Vehicle (EV) Charge Demand Prediction

This repository contains a comprehensive analysis and machine learning model to forecast the adoption rate of Electric Vehicles (EVs) over time. The goal is to use historical data and predictive modeling to provide actionable insights for policymakers, automakers, and clean energy advocates.

---

## 🚀 Project Overview

With the global push toward sustainable transportation, predicting EV adoption trends is critical. This project leverages Python, data science techniques, and machine learning models to:

- Clean and analyze EV-related datasets
- Visualize EV growth patterns
- Build predictive models for EV adoption
- Forecast future trends and growth rate

---

## 🧠 Technologies & Tools Used

| Category            | Tools / Libraries                          |
|---------------------|---------------------------------------------|
| Programming         | Python                                      |
| Data Manipulation   | Pandas, NumPy                               |
| Visualization       | Matplotlib, Seaborn, Plotly                 |
| Machine Learning    | Scikit-learn, XGBoost, Prophet              |
| Jupyter Notebook    | For development and visualization           |

---

## 📊 Features

- 📌 Data Cleaning & Preprocessing
- 📈 Trend Analysis & Visualization
- 🤖 Predictive Modeling with ML Algorithms
- 🔮 Forecasting Future EV Adoption
- 📉 Model Evaluation Metrics

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
## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

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

## Conclusion:  

The project successfully:
- Forecasted EV trends with high interpretability.
- Integrated intelligent features like lagged inputs, moving averages, and trend analysis.
- Created a web-based tool using Streamlit for interactive visual decision-making.

Value to stakeholders:
- Proactive infrastructure and budget planning
- Data-backed regional EV adoption insights

Future scope:
- Integrate real-time EV registration APIs
- Add predictive insights on charging demand

**Note**: This project is for educational and research purposes. For production use in urban planning, additional validation and domain expert consultation is recommended.
