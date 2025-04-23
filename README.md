# **Gold Price Prediction Web App**

## **Overview**

This project is a **Gold Price Prediction Web App** that allows users to predict future gold prices using machine learning models. The app leverages historical gold price data and an API to make predictions. It uses **Prophet**, a forecasting tool developed by Facebook, to generate accurate price predictions. The app is built using **Streamlit**, **Plotly**, and **Matplotlib** to create an interactive and user-friendly web interface for visualization.

### **Key Features:**
- **Data Source Options**: 
  - Upload your own **CSV file** with historical gold price data.
  - Fetch live gold price data via an API.
  
- **Data Preprocessing**: 
  - Calculate the **Volume Weighted Typical Price (VWTP)** for gold prices and convert it to INR per 10 grams.
  
- **Prediction**: 
  - Uses the **Prophet** model for forecasting future gold prices based on historical data.

- **Visualization**: 
  - Interactive charts to visualize gold price trends and forecasted prices.
  - Displays actual and forecasted prices with confidence intervals.
  
- **User Input**: 
  - Allows the user to specify how many days into the future they want to forecast.

- **CSV Download**: 
  - Option to download the forecasted gold prices as a CSV file.

## **Requirements**

To run this app, you'll need Python installed along with the following libraries:

- Streamlit
- Pandas
- Matplotlib
- Plotly
- Prophet

### **Installation**

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/gold-price-prediction.git
    cd gold-price-prediction
    ```

2. Install the required dependencies from the `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

## **How to Use**

1. **Run the Streamlit App**:

    After installing the dependencies, you can start the app with:

    ```bash
    streamlit run app.py
    ```

    This will start the app and open a browser window at `http://localhost:8501`.

2. **Choose Data Source**:
   - You can either upload your own **CSV file** containing historical gold price data or fetch **live data** using an API.

3. **Forecast Gold Prices**:
   - After loading the data, specify the number of days you want to forecast ahead.
   - Click the **"Train and Predict"** button to start the prediction.
   
4. **Download the Forecast**:
   - After the prediction is complete, you can download the forecasted gold prices as a CSV file by clicking the **"Download Forecast as CSV"** button.
