# Trading-Performance-Analysis

# 📊 Trading Performance Analysis (BSE/NSE)

This project performs in-depth analysis of historical trading data (equity & options), identifying profitable and loss-making strike prices, summarizing performance, and visualizing key metrics.

---

## 🔍 Features

- ✅ Sorts trades by realized profit/loss
- 📈 Aggregates performance by symbol
- 📊 Generates visualizations for:
  - Profitable strikes
  - Loss-making strikes
  - Profit/loss threshold probabilities
- 📁 Outputs: Excel reports, PNG charts, and summaries

---

## 🗂 Project Structure

├── data/ # Raw input data (CSV)
│ └── 30th jun nse bse.csv
├── notebooks/ # Jupyter Notebook with full analysis
│ └── analysis300625.ipynb
├── output/ # Processed Excel output
│ └── modified_data.xlsx
├── images/ # Plots and graphs
│ ├── ALLprofitablestrikes.png
│ ├── alllosingstrikes.png
│ └── top3lossesprofitprobability.png
├── requirements.txt # Python package requirements
└── README.md # Project documentation


---

## 📈 Sample Visuals

### 🔼 Profitable Strikes
![Profitable Strikes](main/ALLprofitablestrikes.png)

### 🔽 Losing Strikes
![Losing Strikes](main/alllosingstrikes.png)

### 🎯 Top 3 Profit vs Loss Probability
![Top 3 Probabilities](main/top3lossesprofitprobability.png)


## 🧪 How to Run

### 1. Clone the Repository
bash
git clone https://github.com/BhavneshMehra/Trading-Performance-Analysis.git
cd Trading-Performance-Analysis

### 2. Install Dependencies
pip install -r requirements.txt

### 3. Run the Notebook
jupyter notebook notebooks/analysis300625.ipynb

📚 Technologies Used
Python 3.13
pandas, numpy, matplotlib

Jupyter Notebook

Excel (XLSX output)

📁 Dataset
File: 30th jun nse bse.csv
Columns include:

Symbol, Buy/Sell Qty & Price

Realized Profit

Net Position

User ID, Exchange Info

👨‍💻 Author
Bhavnesh Mehra
🔗 GitHub Profile
