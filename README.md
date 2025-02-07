
# 📈 Gold Price Prediction - Best Model Analysis  

## 📌 Overview  
This project aims to predict gold prices using different machine learning models. By analyzing historical gold price data, we compare various models to determine the best-performing one for accurate forecasting.  

## 📂 Dataset  
The dataset includes key financial indicators such as:  
- Date-wise gold prices  
- Crude oil prices  
- Stock market indices (e.g., S&P 500)  
- Exchange rates (USD-INR)  

## 🛠️ Technologies Used  
- **Python** for data analysis and model building  
- **Pandas & NumPy** for data preprocessing  
- **Matplotlib & Seaborn** for visualization  
- **Scikit-learn** for machine learning models  

## 🚀 Machine Learning Models Tested  
1. **Linear Regression** 📈  
2. **Random Forest Regressor** 🌲  
3. **XGBoost Regressor** ⚡  
4. **LSTM (Long Short-Term Memory)** 🧠 *(Deep Learning Approach)*  

## 📊 Performance Evaluation  
The models were compared using:  
- **Mean Absolute Error (MAE)**  
- **Root Mean Squared Error (RMSE)**  
- **R² Score**  

Among all models, **XGBoost and LSTM** showed the best accuracy for predicting future gold prices.  

## 🔧 How to Run the Project  
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-username/Gold-Price-Prediction.git
   cd Gold-Price-Prediction
   ```  
2. Install dependencies:  
   ```sh
   pip install -r requirements.txt
   ```  
3. Run the Jupyter Notebook:  
   ```sh
   jupyter notebook
   ```  
4. Open `Gold_Price_Prediction.ipynb` and execute the cells.  

## 📌 Future Improvements  
- Incorporating **macroeconomic indicators** like inflation & interest rates  
- Experimenting with **Transformer-based models** for better predictions  
- Building a **real-time dashboard** for price tracking  

