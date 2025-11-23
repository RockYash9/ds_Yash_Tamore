Data Science Assignment - Yash Tamore

Project Overview

This project analyzes the relationship between historical trader behavior (Hyperliquid data) and market sentiment (Bitcoin Fear & Greed Index). The objective is to identify how profitability (PnL) and trading volume correlate with market emotions.

Repository Structure

The project follows the required directory structure:

ds_Yash_Tamore/
├── notebooks/
│   └── notebook_1.ipynb       # Main analysis code (Jupyter Notebook)
├── csv_files/
│   ├── historical_data.csv    # Raw trader data
│   ├── fear_greed_index.csv   # Sentiment data
│   └── merged_data.csv        # (Generated) Processed dataset
├── outputs/
│   ├── sentiment_analysis_summary.png  # Generated visualization
│   ds_report.pdf          # Final summary report
└── README.md


Prerequisites

To run the analysis locally, you need Python installed with the following libraries:

pandas

matplotlib

seaborn

You can install them via pip:

pip install pandas matplotlib seaborn


How to Run

Clone the repository (or download the folder).

Verify Data: Ensure historical_data.csv and fear_greed_index.csv are located inside the csv_files/ folder.

Launch Google colab:


Run All Cells: Execute the cells sequentially. The script will:

Load and clean the datasets.

Merge trade data with sentiment data based on dates.

Generate visualization charts in the outputs/ folder.

Key Insights

Profitability: Traders showed higher average PnL during "Extreme Greed" periods, suggesting momentum strategies were effective.

Volume: Trade size was largest during "Fear" periods, indicating a tendency to buy the dip with high conviction.

**Google Colab Link:** [Click Here to View Notebook](https://colab.research.google.com/drive/1kL1ptjLYPNlyTtFicXp63_vtCWNjoImZ?usp=sharing)

Author

Yash Tamore