# Aviator Data Analysis
This repository contains an exploratory data analysis (EDA) of the Aviator dataset using **python jupyter notebook**, focusing on payout data from various betting apps. The goal of this analysis is to uncover patterns, trends, and insights related to payouts, app performance, and user engagement.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Analysis](#analysis)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
  
## Introduction
The Aviator Data Analysis project explores payout data from multiple betting apps, including BETGR8, BETIKA, ODIBETS, and WINPESA. This analysis aims to provide insights into payout distributions, app performance, and potential trends over time.

## Dataset
The dataset (`aviator_dataset.csv`) includes the following columns:

- `id`: Unique identifier for each payout record.
- `created_at`: Timestamp when the payout record was created.
- `updated_at`: Timestamp when the payout record was last updated.
- `app`: The name of the betting app.
- `payout`: The payout amount.

## Analysis

The analysis includes the following key components:

1. **General Statistics**: Calculation of summary statistics for the payout data.
2. **App-wise Analysis**: Exploration of payout distributions and average payouts for each app.
3. **Time Analysis**: Examination of payout patterns and trends over time.
4. **Outlier Detection**: Identification and analysis of anomalies and outliers in the payout data.
5. **Statistical Tests**: Application of ANOVA to determine if there are significant differences in payouts between apps.

## Installation

To run this analysis, you'll need to set up the environment with the necessary dependencies.

### Clone the Repository

```bash
git clone https://github.com/yourusername/aviator-data-analysis.git
cd aviator-data-analysis
```

### Install Dependencies

Make sure you have Python installed. Then, install the required Python packages:

```bash
pip install -r requirements.txt
```

## Usage

### Running the Analysis

You can run the analysis using a Jupyter notebook or directly through Python scripts.

1. **Using Jupyter Notebook**: Open the notebook `aviator_data_analysis.ipynb` in Jupyter and run the cells sequentially to perform the analysis.
   
   ```bash
   jupyter notebook aviator_data_analysis.ipynb
   ```

2. **Using Python Script**: Execute the Python script to perform the analysis.

   ```bash
   python aviator_data_analysis.py
   ```

### Visualization

The analysis includes various plots such as histograms, box plots, and line charts to visualize the distribution of payouts, app-wise performance, and trends over time.

## Results
The analysis reveals several key insights, including:

- **App-wise Differences**: WINPESA and ODIBETS have higher average payouts compared to BETGR8 and BETIKA.
- **Temporal Trends**: Identification of any significant trends or patterns in payouts over time.
- **Outliers**: Detection of anomalies that may indicate special cases or errors in the data.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request. You can also open an issue for any bugs or feature requests.
