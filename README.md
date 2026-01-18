# WAL Pipeline - DWA Analysis

Analysis pipeline for Detailed Work Activities (DWA) exposure and automation scenarios for Apple (AAPL).

## Features

- **DWA Exposure Analysis**: Interactive bubble charts showing AI augmentation potential vs wagebill
- **Automation Scenarios**: Analysis of potential savings across different automation rates (5%, 15%, 25%)
- **Employee Drill-Down**: Detailed employee statistics and demographics by DWA
- **Demographics Dashboard**: McKinsey-style visualizations for gender, ethnicity, salary, and location

## Notebooks

- `DWA_Drill_Down.ipynb` - Main analysis notebook with interactive Plotly visualizations

## Setup

1. Create a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install pandas plotly jupyter
   ```

## Data

Data files are stored in `output/Tables/` (not included in git):
- `AAPL_dwa_clustered.parquet`
- `AAPL_employees_with_DWAs.parquet`

## Usage

Open the Jupyter notebook and run the cells sequentially to generate the analysis and visualizations.
