# Streamlit Data Visualization

This project is a simple Streamlit application for performing Exploratory Data Analysis (EDA) on CSV files. It allows users to upload a CSV file and provides:

- Data preview (first few rows)
- Summary statistics (mean, median, std, quartiles)
- Data info (types, non-nulls, memory usage)
- Missing values analysis
- Data visualization (histograms, boxplots, correlation heatmaps, etc.)

## How to Run

1. Install dependencies:
   ```bash
   pip install streamlit pandas numpy matplotlib seaborn scipy
   ```
2. Start the app:
   ```bash
   streamlit run src/main.py
   ```

## Project Structure

- `src/main.py`: Main Streamlit app
- `src/lib/`: Library code (extend as needed)
- `data/`: Place your CSV files here (optional)

## Requirements
- Python 3.7+
- Streamlit
- pandas, numpy, matplotlib, seaborn, scipy
