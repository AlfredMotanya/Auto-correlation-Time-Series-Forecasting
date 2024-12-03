# Airline Passengers Time Series Analysis

This project involves analyzing the monthly airline passenger data from 1949 to 1960 to explore trends, seasonality, and patterns using time series analysis. Below is an overview of the project and its components.

## Project Structure

### 1. Data Import and Preprocessing
- **Dataset:** The dataset is read from `AirPassengers.csv`.
- **Columns:**
  - `Date`: Date of observation (monthly data).
  - `Number of Passengers`: Total passengers for the corresponding month.
- **Preprocessing Steps:**
  - Renamed columns for clarity.
  - Converted the `Date` column to a datetime format for easier analysis.

### 2. Data Visualization
- **Line Plot:**
  - Displays the number of passengers over time.
  - Highlights overall trends.
- **Two-Sided View Plot:**
  - Illustrates data symmetry around a baseline for visual insight.
- **Trend and Seasonality Plot:**
  - Focuses on recurring patterns in the data.

### 3. Time Series Decomposition
- **Purpose:** To break down the time series into trend, seasonality, and residuals.
- **Methods:**
  - Multiplicative Decomposition.
  - Additive Decomposition.
- **Visualization:** Separate plots for multiplicative and additive components.

### 4. Seasonality and Autocorrelation Analysis
- **Autocorrelation Plot:** 
  - Visual representation of how the data relates to its past values.
- **ACF and PACF Plots:**
  - **Autocorrelation Function (ACF):** Measures correlation between observations.
  - **Partial Autocorrelation Function (PACF):** Shows direct relationships with lagged values.

---

## Installation and Requirements

### Libraries Used
- `numpy` – Numerical computations.
- `pandas` – Data manipulation and processing.
- `datetime` – Handling date-time data.
- `matplotlib` – Data visualization.
- `seaborn` – Enhanced data visualization.
- `statsmodels` – Statistical models and time series analysis.
- `sklearn` – Machine learning (linear regression).
- `dateutil` – Date parsing utilities.

### Installation
Install the required libraries using pip:
```bash
pip install numpy pandas matplotlib seaborn statsmodels scikit-learn
