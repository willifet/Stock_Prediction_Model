### Can deep learning capture patterns in stock price movements?

I recently built a stock price prediction model using an LSTM neural network, designed to learn temporal dependencies in historical market data.


#### 🎯 Project Objective

To forecast future stock prices by modelling long-term trends and short-term volatility in time-series data.


#### 📊 Data & Features

       ✅ Historical stock prices (Open, High, Low, Close, Volume)

       ✅ Time-windowed sequences to preserve temporal structure

       ✅ Normalised inputs to stabilise training.


#### 🧠 Model Architecture & Training

      1️⃣ LSTM network for sequential learning

      2️⃣ Use the ReLU activation function to improve non-linear

         representation

      3️⃣ Adam optimizer with learning rate 0.0015

      4️⃣ Trained for 50 epochs with loss monitoring to reduce overfitting


#### 📈 Results & Observations

     👉 The model successfully captured price trends and momentum

        patterns

     👉 Prediction accuracy improved steadily across epochs

     👉 LSTM outperformed traditional regression baselines on sequential

        data


#### 💡 Key Takeaways

     🔷 Time-series models benefit significantly from memory-based

        architectures

     🔷 Hyperparameter tuning (learning rate, epochs) played a major role in

        convergence

     🔷 Deep learning provides a strong foundation for market forecasting

        and risk analysis


#### 🛠 Tools & Stack

Python | TensorFlow / Keras | NumPy | Pandas | Matplotlib | Streamlit | yfinance


#### ✨ Knowledge gain

This project strengthened my understanding of deep learning for financial time series and the practical trade-offs involved in model tuning.

