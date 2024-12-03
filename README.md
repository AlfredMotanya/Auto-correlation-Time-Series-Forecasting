# Airline Passengers Time Series Analysis

This project involves analyzing the monthly airline passenger data from 1949 to 1960 to explore trends, seasonality, and patterns using time series analysis. Below is an overview of the project and its components.

## Project Structure

### 1. Data Import and Preprocessing
- **Dataset:** The dataset is downloaded dynamically from Kaggle.
- **Code to Access Data:**
  ```python
  import kagglehub

  # Download latest version
  path = kagglehub.dataset_download("rakannimer/air-passengers")

  print("Path to dataset files:", path)

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
- `kagglehub` – Kaggle dataset downloader.
- `dateutil` – Date parsing utilities.

### Installation
Install the required libraries using pip:
```bash
pip install numpy pandas matplotlib seaborn statsmodels scikit-learn
```

Running the Project
Ensure you have an active Kaggle API token configured for kagglehub.
Execute the script in a Python environment (e.g., Jupyter Notebook, PyCharm).
Review the visualizations and analysis outputs.
Key Visuals and Outputs
Trends and Patterns: Visualized through line plots.
Decomposition: Highlights trend and seasonal components.
Autocorrelation and PACF: Provide insights into seasonality and lag effects.
Insights and Applications
Identify and analyze trends and seasonal variations in airline passenger data.
Form the basis for predictive modeling and forecasting.
Acknowledgments
Dataset Source: Air Passengers Dataset on Kaggle