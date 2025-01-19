# Multi-Time Scale Solar Radiation Prediction Technology  Based on Neural Network

## Project Overview
This project focuses on building, improving, and analyzing machine learning models for solar radiation prediction and hybrid energy systems optimization. It includes neural network implementations, dataset processing, and hybrid model design for renewable energy solutions.

## Files Overview

### 1. **Models**
   - `solar_radiation_model.keras`: Contains the initial trained Keras model for solar radiation prediction.
   - `improved_solar_radiation_model.keras`: Includes the improved version of the solar radiation prediction model.

### 2. **Datasets**
   - `X_train.csv`, `X_val.csv`, `X_test.csv`: Input datasets for training, validation, and testing the models.
   - `y_train.csv`, `y_val.csv`, `y_test.csv`: Corresponding output labels for the input datasets.
   - `SolarPrediction.csv`: The raw dataset used for initial data analysis.
   - `SolarPrediction_Cleaned.csv`: The cleaned and preprocessed dataset ready for machine learning models.

### 3. **Jupyter Notebooks**
   - `Feedforward_neural_network_regression.ipynb`: Notebook implementing a feedforward neural network for regression tasks.
   - `LSTM_GRU_Hybrid.ipynb`: Explores a hybrid model using LSTM and GRU architectures for time-series analysis.
   - `DataAnalysis.ipynb`: Contains exploratory data analysis and feature engineering for solar radiation prediction.

### 4. **Project Details**
   - `README.md`: Project documentation (current file).

## Key Features

### Solar Radiation Prediction Models
- **Feedforward Neural Network**: Implemented for solar radiation regression tasks.
- **LSTM-GRU Hybrid Model**: Combines Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) architectures for improved performance on time-series data.

### Data Preprocessing
- **Feature Engineering**: Datasets include engineered features optimized for model input.
- **Data Cleaning**: Removal of outliers and missing values.

### Hybrid Model Design
- Incorporates AI techniques for optimizing power sharing in hybrid AC/DC microgrids with hybrid energy storage systems.

## Usage

### Prerequisites
- Python 3.x
- TensorFlow/Keras
- Pandas, NumPy, Matplotlib

### Steps to Run
1. **Setup Environment**
   Install the required libraries using:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run Models**
   - Open and run `Feedforward_neural_network_regression.ipynb` for initial model exploration.
   - Execute `LSTM_GRU_Hybrid.ipynb` to experiment with advanced hybrid models.

3. **Analyze Results**
   - Evaluate model performance using the test datasets (`X_test.csv`, `y_test.csv`).
   - Visualize results with built-in Matplotlib plots.

## Future Enhancements
- Integration of additional hybrid energy storage systems.
- Deployment of optimized models for real-time solar radiation prediction.
- Extending the dataset with additional regional and weather-specific data.

## Contributors
- [Your Name]
- [Your Contact Information]

## License
This project is licensed under the [MIT License](LICENSE).
