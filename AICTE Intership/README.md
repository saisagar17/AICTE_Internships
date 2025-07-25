# ⚡ EV Adoption Forecasting using Machine Learning

Based on your EV Adoption Forecasting project, I'll create a comprehensive README file for you:

```markdown
# EV Adoption Forecasting

A machine learning project that forecasts electric vehicle (EV) adoption to help urban planners anticipate infrastructure needs, particularly charging stations.

## 🚗 Project Overview

As electric vehicle adoption surges globally, urban planners need accurate forecasting models to anticipate infrastructure requirements. This project builds a regression model to predict future EV adoption based on historical trends, vehicle types, and regional data.

## 📊 Dataset

The project uses electric vehicle registration data from Washington State Department of Licensing (DOL), containing monthly vehicle registration counts separated by county for passenger vehicles and trucks.

### Dataset Features:
- **Date**: Monthly registration counts (2017-01-31 to 2024-02-29)
- **County**: Geographic region where vehicle owner resides
- **State**: Geographic region of the country
- **Vehicle Primary Use**: Passenger (83%) or Truck (17%)
- **Battery Electric Vehicles (BEVs)**: Count of fully electric vehicles
- **Plug-In Hybrid Electric Vehicles (PHEVs)**: Count of hybrid electric vehicles
- **Electric Vehicle (EV) Total**: Sum of BEVs and PHEVs
- **Non-Electric Vehicle Total**: Count of non-electric vehicles
- **Total Vehicles**: All registered vehicles in the county
- **Percent Electric Vehicles**: EV adoption percentage

**Data Source**: [Kaggle - Electric Vehicle Population Size 2024](https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population-size-2024)

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization
- **scikit-learn** - Machine learning algorithms
- **joblib** - Model serialization

## 🚀 Installation

1. Clone the repository:
```
git clone https://github.com/yourusername/ev-adoption-forecasting.git
cd ev-adoption-forecasting
```

2. Install required packages:
```
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

3. Download the dataset:
   - Place `Electric_Vehicle_Population_Size_History_By_County_.csv` in the project directory

## 📈 Model Features

The forecasting model includes sophisticated feature engineering:

- **Time-based features**: Months since start, seasonal patterns
- **Lag features**: Previous 1-3 months EV totals
- **Rolling statistics**: 3-month moving averages
- **Growth metrics**: Percentage changes and growth slopes
- **Cumulative metrics**: Total EV adoption over time
- **Categorical encoding**: County and state information

## 🔧 Usage

1. **Run the Jupyter Notebook**:
```
jupyter notebook EV_Adoption_Forcasting.ipynb
```

2. **Or run as Python script**:
The notebook can be converted to a Python script for automated forecasting.

## 📊 Model Performance

The Random Forest Regressor model provides:
- Feature importance analysis
- Time series validation
- Multiple evaluation metrics (MAE, MSE, R²)
- Prediction confidence intervals

## 🎯 Key Features

- **Data Preprocessing**: Handles missing values, date parsing, and feature scaling
- **Feature Engineering**: Creates lag features, rolling statistics, and growth metrics
- **Model Training**: Random Forest with hyperparameter tuning
- **Evaluation**: Comprehensive model performance metrics
- **Visualization**: Charts showing trends, predictions, and feature importance
- **Forecasting**: Ability to predict future EV adoption rates

## 📁 Project Structure

```
ev-adoption-forecasting/
│
├── EV_Adoption_Forcasting.ipynb    # Main Jupyter notebook
├── Electric_Vehicle_Population_Size_History_By_County_.csv  # Dataset
├── README.md                       # Project documentation
└── requirements.txt               # Python dependencies
```

## 🔮 Future Enhancements

- [ ] Integration with real-time data sources
- [ ] Geographic visualization using mapping libraries
- [ ] Deep learning models (LSTM, GRU) for time series
- [ ] API development for real-time predictions
- [ ] Dashboard creation for stakeholders
- [ ] Integration with charging station location data
- [ ] Economic impact analysis

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

Your Name - your.email@example.com

Project Link: [https://github.com/yourusername/ev-adoption-forecasting](https://github.com/yourusername/ev-adoption-forecasting)

## 🙏 Acknowledgments

- Washington State Department of Licensing for providing the dataset
- Kaggle community for data sharing
- Open source contributors of the used libraries

---

**Note**: This project is for educational and research purposes. For production use in urban planning, additional validation and domain expert consultation is recommended.
```

This README file provides a comprehensive overview of your EV adoption forecasting project, including:

1. **Clear project description** with context and goals
2. **Dataset explanation** with all features described
3. **Installation instructions** for easy setup
4. **Technology stack** used in the project
5. **Model features** and capabilities
6. **Usage instructions** for running the code
7. **Project structure** for easy navigation
8. **Future enhancement ideas** for continued development
9. **Contributing guidelines** for collaboration
10. **Professional formatting** with emojis and clear sections

You can customize the contact information, repository links, and any specific details to match your actual project setup.

[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/83099091/6e8bd18a-0c77-4cc6-80e5-74d478e3b089/EV_Adoption_Forcasting.ipynb
