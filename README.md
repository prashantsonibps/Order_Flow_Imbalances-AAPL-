# Order Flow Imbalance (OFI) Analysis

Hey there! Welcome to my GitHub repo for my Order Flow Imbalance (OFI) Analysis project. I had a ton of fun diving into high-frequency trading data for AAPL and building features to explore market dynamics. This project features a Jupyter Notebook with OFI calculations, some awesome visualizations, and a LaTeX report tackling key conceptual questions. I’m stoked to share this work—it’s a deep dive into how order flow shapes financial markets, and I hope you find it as exciting as I do!

## What’s This Project About?
This project analyzes Order Flow Imbalance (OFI) using a high-frequency limit order book dataset for AAPL (`first_25000_rows.csv`). I implemented three OFI features—Best-Level, Multi-Level, and Integrated OFI—and used visualizations to uncover their relationship with price movements. I also explored three conceptual questions in a LaTeX report, explaining why multi-level OFI rocks, the power of Lasso regression, and how OFI outshines trade volume for predicting short-term returns. As a bonus, I studied the paper *"Optimal Order Placement in Limit Order Markets"* by Cont and Kukanov to deepen my understanding of smart order routing (no separate deliverables for that part).

## Repository Structure
Here’s how the repo is organized:
- `data/`: Holds the input dataset (`first_25000_rows.csv`).
- `src/`: Contains my Jupyter Notebook (`ofi_analysis.ipynb`), where all the OFI calculations and plots come to life.
- `output/`: Stores the computed OFI data (`ofi_features.csv`) and visualization files (PNG plots: `ofi_time_series.png`, `ofi_returns_scatter.png`, `ofi_distribution.png`).
- `doc/`: Includes my LaTeX report (`conceptual_answers.tex`) and the compiled PDF (`conceptual_answers.pdf`) for the conceptual questions.
- `README.md`: This file, giving you the full scoop on the project!


## How to Run the Code
Getting this project up and running is a breeze. Here’s what to do:

1. **Clone the Repository**:
   ```bash
   git clone gh repo clone prashantsonibps/Order_Flow_Imbalances-AAPL-
