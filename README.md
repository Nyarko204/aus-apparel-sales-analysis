# 🛍️ Australian Apparel Sales Analysis — Q4 2020

A Python-based exploratory data analysis (EDA) of Australian Apparel Limited (AAL) sales data for the fourth quarter of 2020. This project covers data cleaning, statistical analysis, and visualisation to uncover revenue trends across states, demographic groups, and time periods.

---

## 📁 Project Structure

```
├── Sales_Analysis.ipynb        # Main Jupyter notebook
├── AusApparalSales4thQrt2020.csv  # Source dataset
└── README.md
```

---

## 📌 Objectives

- Inspect and clean the dataset
- Normalise sales and unit data using Min-Max scaling
- Perform descriptive statistical analysis
- Identify top and bottom performing states and demographic groups
- Generate monthly and weekly revenue reports
- Visualise trends using Seaborn and Matplotlib

---

## 🔍 Key Findings

| Insight | Detail |
|--------|--------|
| 📈 **Highest Revenue State** | Victoria (VIC) |
| 📉 **Lowest Revenue State** | Western Australia (WA) |
| 👗 **Best Performing Group** | Identified via GroupBy analysis |
| 👴 **Lowest Performing Group** | Seniors |

---

## 📊 Visualisations

The notebook generates the following charts:

- **Bar Chart** — State-wise sales by demographic group
- **Bar Chart** — Group-wise sales across states
- **Line Chart** — Peak vs off-peak sales periods by time of day
- **Box Plot** — Sales distribution and outlier detection
- **Histogram + KDE** — Overall sales density

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| `pandas` | Data loading, cleaning, and aggregation |
| `numpy` | Numerical operations and normalisation |
| `seaborn` | Statistical visualisations |
| `matplotlib` | Plot rendering |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install dependencies
```bash
pip install pandas numpy seaborn matplotlib jupyter
```

### 3. Launch the notebook
```bash
jupyter notebook Sales_Analysis.ipynb
```

> Make sure `AusApparalSales4thQrt2020.csv` is in the same directory as the notebook before running.

---

## 💡 Recommendations

1. **Maintain VIC dominance** — Victoria is the highest revenue generator; continue focused marketing spend here.
2. **Revitalise WA** — Introduce state-specific discount programmes to improve penetration in Western Australia.
3. **Target Seniors** — Launch a loyalty programme or a comfort-focused clothing line to boost sales in this demographic.
4. **Flash Sales strategy** — Use the time-of-day analysis to schedule promotions during off-peak hours to normalise store traffic.

---

## 📄 License

This project is for educational and analytical purposes.
