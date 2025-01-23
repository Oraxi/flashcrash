# Flash Crash Detection Project

## Overview
This project aims to detect flash crashes in financial markets using tick-by-tick Best Bid and Offer (BBO) and trade data for S&P 500 stocks during May 2010. The analysis includes data loading, exploration, preprocessing, and detection of flash crashes using various methodologies.

## Repository Structure
The project consists of the following Jupyter Notebooks:

1. **`data_loading.ipynb`**  
   - Loads raw tick-by-tick data from available sources.
   - Parses and organizes data into a structured format.
   - Handles missing values and performs initial data quality checks.

2. **`data_preprocessing.ipynb`**  
   - Cleans and prepares the data for modeling.
   - Feature engineering and normalization.
   - Removes outliers and transforms the data for analysis.

3. **`data_exploration.ipynb`**  
   - Provides visual and statistical analysis of the dataset.
   - Examines key market patterns, anomalies, and trends.
   - Includes descriptive statistics and exploratory plots.

4. **`flash_crash_detection.ipynb`**  
   - Implements detection algorithms to identify flash crashes.
   - Uses techniques such as statistical thresholds, machine learning models, and anomaly detection.
   - Evaluates model performance and visualizes detected crashes.


## Data Availability
The dataset used in this project can be found at the following link:  
[Download Data](https://drive.switch.ch/index.php/s/0X3Je6DauQRzD2r)


## Prerequisites
Before running the notebooks, ensure you have the following dependencies installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage
Follow these steps to execute the project:

1. **Load the data:**  
   Run `data_loading.ipynb` to import and structure the dataset.

2. **Preprocess the data:**  
   Use `data_preprocessing.ipynb` to clean and prepare the data.

3. **Explore the data:**  
   Execute `data_exploration.ipynb` to understand the dataset characteristics.

4. **Detect flash crashes:**  
   Run `flash_crash_detection.ipynb` to identify and analyze flash crashes.

## Expected Output
- Summary statistics and visualizations of market data.
- Processed datasets ready for analysis.
- Detected flash crash events with timestamps and visual representations.




