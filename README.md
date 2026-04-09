# 🌧️ RainCast - Rain Forecast Prediction System

A machine learning-based rain forecasting application that predicts whether it will rain tomorrow based on current weather conditions.

## 🚀 Live Demo

Deployed on Streamlit Community Cloud: [https://harshilpatel-15-weather-prediction-app.streamlit.app/](https://harshilpatel-15-weather-prediction-app.streamlit.app/)

## 📋 Project Overview

RainCast is an end-to-end machine learning project that analyzes historical weather data to predict next-day rainfall. The system uses multiple weather parameters to generate accurate rain forecasts with probability scores and risk assessments.

### 🎯 Key Features

- **Real-time Prediction**: Enter current weather conditions and get instant rain forecasts
- **Probability Scoring**: Get confidence levels with percentage-based predictions
- **Risk Assessment**: Categorized risk levels (Very Low to Very High)
- **Professional UI**: Modern, responsive Streamlit interface
- **Multiple Input Parameters**: Temperature, humidity, pressure, wind speed, and more

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Machine Learning**: Scikit-learn
- **Data Processing**: Pandas, NumPy
- **Model Persistence**: Joblib
- **Deployment**: Streamlit Community Cloud

## 📊 Machine Learning Models

The project implements and compares multiple classification algorithms:

1. **Logistic Regression** - Baseline model
2. **Decision Tree Classifier** - Interpretable decision rules
3. **Random Forest Classifier** - Ensemble method for better accuracy
4. **K-Nearest Neighbors (KNN)** - Distance-based classification
5. **Gradient Boosting** - Advanced ensemble technique

## 🌤️ Input Features

- **Location**: Weather station location
- **Temperature**: Min/Max temperature (°C)
- **Humidity**: Morning and afternoon humidity (%)
- **Pressure**: Atmospheric pressure (hPa)
- **Wind Speed**: Morning and afternoon wind speed (km/h)
- **Current Rain**: Whether it's raining today

## 🚀 Installation & Local Setup

### Prerequisites

- Python 3.8 or higher
- Git

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/HarshilPatel-15/weather_prediction.git
   cd weather_prediction
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   streamlit run app.py
   ```

4. **Open your browser**
   Navigate to `http://localhost:8501`

## 📁 Project Structure

```
weather_prediction/
├── app.py                          # Main Streamlit application
├── project.ipynb                   # Jupyter notebook with ML pipeline
├── rain_forecasting.csv            # Historical weather dataset
├── best_raincast_model.pkl         # Trained ML model
├── raincast_scaler.pkl             # Feature scaler
├── raincast_feature_columns.pkl    # Feature column names
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation
```

## 🎯 How to Use

1. **Open the application** in your web browser
2. **Enter weather parameters** in the input form:
   - Select location
   - Input temperature readings
   - Add humidity levels
   - Enter pressure values
   - Provide wind speed data
   - Indicate current rain status
3. **Click "Predict Rain Forecast"** to get results
4. **View predictions** including:
   - Rain/No Rain prediction
   - Probability percentage
   - Risk level assessment
   - Personalized recommendations

## 📈 Model Performance

The system evaluates models using:
- **Accuracy**: Overall prediction correctness
- **Precision**: True positive prediction rate
- **Recall**: Actual positive detection rate
- **F1-Score**: Harmonic mean of precision and recall
- **Confusion Matrix**: Detailed classification results

## 🔧 Model Training Pipeline

1. **Data Collection**: Historical weather data gathering
2. **Data Cleaning**: Missing value handling and preprocessing
3. **Feature Engineering**: Date extraction and categorical encoding
4. **Model Training**: Multiple algorithm implementation
5. **Model Evaluation**: Performance comparison and selection
6. **Model Deployment**: Saving best model for predictions

## 🌟 Deployment

The application is deployed on Streamlit Community Cloud and can be accessed at:
[https://harshilpatel-15-weather-prediction-app.streamlit.app/](https://harshilpatel-15-weather-prediction-app.streamlit.app/)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Harshil Patel**
- GitHub: [@HarshilPatel-15](https://github.com/HarshilPatel-15)
- Project: RainCast - Rain Forecast Prediction System

## 🙏 Acknowledgments

- Brainybeam Info-Tech PVT LTD. for internship opportunity
- Streamlit team for the amazing framework
- Scikit-learn community for excellent ML tools

---

**Note**: This project was developed as part of an internship program focusing on Data Science & Machine Learning with Data Analytics.
