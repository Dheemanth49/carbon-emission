# Carbon Emission Data Analysis

A comprehensive data preprocessing and exploratory data analysis project for carbon emission monitoring using energy consumption data.

## Dataset Overview

- **Size**: ~14.7M rows of energy consumption data
- **Time Range**: May 2019 - October 2021
- **Features**: Timestamp, kWh consumption, voltage, current, frequency, meter ID
- **Meters**: Multiple energy meters (BR02, etc.)

## Project Structure

```
carbon-emission/
├── data_preprocessing_eda.ipynb    # Main analysis notebook
├── carbon_emmsion.ipynb           # Alternative analysis notebook
├── requirements.txt               # Python dependencies
├── README.md                     # Project documentation
└── .gitignore                    # Git ignore rules
```

## Features

### Data Preprocessing
- Chunked data loading for large datasets
- Missing value analysis
- Duplicate detection and removal
- Outlier detection using IQR method
- Data type optimization

### Exploratory Data Analysis
- **Temporal Analysis**: Hourly, daily, and monthly consumption patterns
- **Correlation Analysis**: Relationships between variables
- **Meter Analysis**: Performance comparison across different meters
- **Distribution Analysis**: Statistical distributions of key variables
- **Data Quality Checks**: Comprehensive data validation

### Visualizations
- Time series plots
- Correlation heatmaps
- Distribution histograms
- Box plots for outlier detection
- Consumption patterns by meter and time

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd carbon-emission
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Add your dataset:
   - Place `total_dataset.csv` in the project root
   - The dataset should contain columns: timestamp, kWh, voltage, current, frequency, meter

## Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook data_preprocessing_eda.ipynb
```

2. Run cells sequentially to:
   - Load and preprocess the data
   - Perform data quality checks
   - Generate visualizations
   - Export cleaned dataset

## Key Insights

- Energy consumption patterns vary significantly by hour and day of week
- Strong correlation between current and kWh consumption
- Multiple meters show different consumption characteristics
- Data spans 2+ years with consistent 3-minute intervals

## Dependencies

- pandas >= 1.5.0
- numpy >= 1.21.0
- matplotlib >= 3.5.0
- seaborn >= 0.11.0

## Output

- `cleaned_dataset.csv`: Preprocessed and cleaned data
- Various visualization plots (PNG format)
- Comprehensive data quality report

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the MIT License.