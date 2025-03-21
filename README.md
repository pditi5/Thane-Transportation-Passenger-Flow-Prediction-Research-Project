# Thane Municipal Transportation Passenger Flow Prediction Research Project

This research project focuses on forecasting **passenger counts** for the **Thane Municipal Transportation** system using various **machine learning models**. The project explores different time-series forecasting techniques to predict future passenger flow based on historical data.

## **Project Overview**

The goal of this project is to improve the prediction of passenger counts across different **station pairs** within the Thane Municipal Transportation system. Key techniques explored include:

- **LSTM (Long Short-Term Memory)**: A deep learning model for sequential data.
- **Transformer Models**: Advanced models using attention mechanisms to capture long-range dependencies.
- **VAR (Vector Autoregression)**: A statistical model to capture relationships between time series.
- **LightGBM**: A gradient boosting machine for efficient forecasting.
- **STL-LSTM (Seasonal-Trend decomposition with LSTM)**: A hybrid approach combining STL decomposition and LSTM.
- **Other Techniques**: Exploration of Exploratory Data Analysis (EDA) and data preprocessing to enhance model performance.

## 📊 **Key Findings**

- **LSTM-based Models**: Outperformed other models in terms of accuracy by capturing sequential patterns.
- **Transformer Models**: Showed promise in handling complex dependencies and performed well in many cases.
- **VAR Models**: Good for understanding interdependencies between station pairs but less accurate in forecasting.
- **STL Decomposition**: Boosted the prediction accuracy by decomposing data into seasonal, trend, and residual components.

## 🔧 **Data Preprocessing & Feature Engineering**

Data preprocessing was crucial for improving model accuracy. The key steps included:

- **Handling Missing Values & Outliers**: Ensured cleaner and more reliable data.
- **Scaling Data**: Normalized features for better model convergence.
- **Feature Engineering**: Created **lag-based features** to capture temporal dependencies and enhance forecasting accuracy.
- **Station Pair Translation**: Improved alignment and prediction quality for station-related data.

## 📈 **Evaluation Metrics**

The performance of each model was evaluated using the following metrics:

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

These metrics helped in comparing different models and selecting the best-performing approach for future passenger flow predictions.

## ⚠️ **Limitations of the Study**

Despite the promising results, there were several limitations:

- **Data Quality**: Missing values and outliers affected model performance.
- **Computational Complexity**: Deep learning models like LSTM and Transformers required substantial computational resources.
- **Dataset Scope**: The dataset was specific to Thane, which may limit the generalizability to other locations or transportation systems.

##  **Suggestions for Future Research**

- **Hybrid Models**: Explore combining LSTM, Transformer, and VAR models for more accurate predictions.
- **Unsupervised Learning**: Investigate clustering and anomaly detection to discover hidden patterns in the data.
- **Model Optimization**: Experiment with hybrid architectures like CNN-LSTM or Attention-based mechanisms.
- **External Data**: Incorporate external factors (e.g., weather, economic indicators) to improve model robustness.
- **Real-Time Forecasting**: Develop online learning algorithms for continuous updates in real-time prediction systems.

## 📑 **Project Report**

This project report is submitted in partial fulfillment for the degree of **B.Tech in Technology and Development** at **Lalbhai Dalpatbhai College of Engineering, Ahmedabad** under the guidance of **Prof. Madhuri Patel**, Gujarat Technological University (GTU), 2021-2025.

### **Project Documentation**

- [Thane Municipal Transportation Project Report - Diti Patel.pdf](TMT_Research_Project/Thane Muncipal Transportation Project Report - Diti Patel.pdf)

## 🛠️ **Technologies Used**

- **Python**
- **LSTM** (Long Short-Term Memory)
- **Transformers**
- **VAR** (Vector Autoregression)
- **LightGBM**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn** (for data analysis and visualization)
- **SciKit-Learn**, **TensorFlow**, **Keras**

Feel free to reach out if you have any questions or feedback!

🔗 [LinkedIn](https://www.linkedin.com/in/ditishaileshpatel/) | [GitHub](https://github.com/pditi5)

