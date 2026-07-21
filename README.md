# 🌦️ Smart Weather Prediction

An AI-powered Machine Learning application for predicting weather conditions using historical weather data and environmental parameters.

## 📌 Project Overview

Smart Weather Prediction is a Machine Learning-based project that analyzes historical weather data to predict future weather conditions. The project uses various environmental and atmospheric parameters such as precipitation, maximum temperature, minimum temperature, and wind speed to identify the expected weather condition.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, data visualization, feature engineering, model training, prediction, and model evaluation.

## 🚀 Features

* 🌦️ Predict weather conditions using Machine Learning
* 📊 Exploratory Data Analysis (EDA)
* 📈 Data visualization
* 🧹 Data preprocessing and cleaning
* 🔍 Feature engineering
* 🤖 Machine Learning model training
* 🎯 Weather condition classification
* 📊 Model performance evaluation
* 💾 Trained model saving using Joblib
* ☁️ Google Colab-based implementation

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib
* Google Colab

## 📂 Dataset

The project uses the **Seattle Weather Dataset** for training and testing the Machine Learning model.

### Dataset Features

| Feature         | Description                     |
| --------------- | ------------------------------- |
| `date`          | Date of the weather observation |
| `precipitation` | Amount of precipitation         |
| `temp_max`      | Maximum temperature             |
| `temp_min`      | Minimum temperature             |
| `wind`          | Wind speed                      |
| `year`          | Year extracted from the date    |
| `month`         | Month extracted from the date   |
| `day`           | Day extracted from the date     |

### 🎯 Target Variable

`weather`

The target variable represents the weather condition, such as:

* ☀️ Sun
* 🌧️ Rain
* 🌫️ Fog
* ❄️ Snow
* 🌦️ Drizzle

## 🔄 Machine Learning Workflow

```text
Dataset Collection
       ↓
Data Loading
       ↓
Data Cleaning
       ↓
Missing Value Handling
       ↓
Exploratory Data Analysis
       ↓
Data Visualization
       ↓
Feature Engineering
       ↓
Feature and Target Selection
       ↓
Label Encoding
       ↓
Train-Test Split
       ↓
Model Training
       ↓
Model Prediction
       ↓
Model Evaluation
       ↓
Save Trained Model
```

## 🤖 Machine Learning Model

The project uses the **Random Forest Classifier** for weather condition prediction.

Random Forest is an ensemble Machine Learning algorithm that combines multiple decision trees to improve prediction performance and reduce overfitting.

## 📊 Model Evaluation

The trained model is evaluated using the following performance metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

The model performance may vary depending on the dataset split and training configuration.

## 📈 Data Visualization

The project includes several visualizations to understand the weather dataset:

* Weather condition distribution
* Maximum and minimum temperature analysis
* Precipitation distribution
* Correlation heatmap
* Feature importance
* Confusion matrix

## 📓 Google Colab Notebook

The complete Machine Learning implementation is available in the Jupyter Notebook:

```text
weather_prediction.ipynb
```

The notebook contains the complete workflow from data preprocessing to weather prediction.

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Smart-Weather-Prediction.git
```

### 2. Navigate to the Project Folder

```bash
cd Smart-Weather-Prediction
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Open the Notebook

Open:

```text
weather_prediction.ipynb
```

You can run the notebook using:

* Google Colab
* Jupyter Notebook

### 5. Upload the Dataset

Make sure the following dataset is available:

```text
seattle-weather.csv
```

### 6. Run All Cells

Run all notebook cells sequentially to:

* Load the dataset
* Preprocess the data
* Perform EDA
* Train the Machine Learning model
* Evaluate the model
* Predict weather conditions

## 📁 Project Structure

```text
Smart-Weather-Prediction/
│
├── 📓 weather_prediction.ipynb
├── 📊 seattle-weather.csv
├── 🤖 weather_model.pkl
├── 🔤 weather_label_encoder.pkl
├── 📄 requirements.txt
└── 📖 README.md
```

## 🔮 Future Enhancements

* Develop an interactive Streamlit web application
* Deploy the application online
* Integrate real-time weather APIs
* Add advanced Machine Learning models
* Implement Deep Learning-based weather prediction
* Add real-time weather forecasting
* Improve prediction accuracy with larger datasets

## 🌐 Future Deployment

The project can be deployed as an interactive web application using:

* Streamlit
* Streamlit Community Cloud

Users can enter weather parameters and receive the predicted weather condition instantly.

## 👨‍💻 Developer

**Your Name**R.GokulRaaj

B.E computer science

Passionate about Artificial Intelligence, Machine Learning, Python, and Data Science.

## ⭐ Support

If you find this project useful or interesting, please consider giving this repository a ⭐ on GitHub.

Your support is greatly appreciated!

## 📜 License

This project is created for educational and learning purposes.
