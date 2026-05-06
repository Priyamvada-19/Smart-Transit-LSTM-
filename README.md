## **LSTM Time Series Prediction Project**
 
This project builds a Long Short-Term Memory (LSTM) model to predict public transport ridership using historical data.

The notebook:

Uploads and processes a CSV dataset (historical_ridership.csv)
Engineers time-based features
Trains an LSTM model
Evaluates performance
Forecasts future ridership (30 days)
Saves outputs (model + predictions)

## **Project Structure** 
```
├── LSTM.ipynb          # Main notebook with implementation
├── README.md           # Project documentation
(.csv file is being attached , upload it while running the code)

```

## **Technologies Used**
1) Python 
2) NumPy
3) Pandas
4) Matplotlib
5) Scikit-learn
6) TensorFlow / Keras

## **Workflow**
1. *Data Preprocessing* :
Load dataset
Normalize values using MinMaxScaler
Convert data into sequences for LSTM
2. *Model Building* :
LSTM layers
Dense output layer
Compile model with loss function and optimizer
3. *Training* : 
Train model on training dataset
Validate using test dataset
4. *Prediction* :
Predict future values
Compare predicted vs actual values
5. *Visualization* :
Plot training results
Plot predictions vs real data

## **How to Run**
Clone the repository:
```
git clone https://github.com/your-username/your-repo-name.git
```
Navigate to project folder:
```
cd your-repo-name
```
Install dependencies:
```
pip install -r requirements.txt
```
Run the notebook:
```
jupyter notebook
```
## **Requirements**

If you don’t have a requirements.txt, use:
numpy
pandas
matplotlib
scikit-learn
tensorflow

## **Future Improvements**

Add GRU model comparison
Deploy as a web app
Real-time data integration

##  Author

* Priyamvada Kumar
 
##  Acknowledgment

This project was built as part of learning Machine Learning.
