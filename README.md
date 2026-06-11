# 📊 Data Analysis Portfolio — Akash Mathiyazhagan

A collection of data analysis projects built with Python, covering real-world datasets across crime records and retail business performance.

---

## 📁 Projects

| # | Project | Domain | Dataset |
|---|---------|--------|---------|
| 1 | [National Crime Data Analysis](#1-national-crime-data-analysis) | Crime & Law Enforcement | NCRB India |
| 2 | [Super Store Data Analysis](#2-super-store-data-analysis) | Retail & Business | Sample Superstore |

---

## 1. 🔍 National Crime Data Analysis

### Overview
Analysis of India's national property crime records — stolen and recovered cases — sourced from the **National Crime Records Bureau (NCRB)**. The project identifies trends, highlights recovery rates, and assesses the effectiveness of investigative efforts across different states and years.

### 📂 File
`National_Crime_Data_Analyse.ipynb`

### 🎯 Key Objectives
- Identify state-wise and year-wise crime trends
- Analyze property stolen vs. recovered cases and values
- Visualize recovery rates across regions
- Understand how effectively police resolve property crimes annually

### 📊 Analysis Highlights
- **State-wise comparison** of cases and value of property stolen vs. recovered
- **Year-wise trend** of property crimes and recovery over time
- **Group-wise** breakdown of crime categories
- Recovery rate insights across states

### 🧰 Libraries Used
`numpy` · `pandas` · `matplotlib`

### 📁 Dataset
- **Source:** National Crime Records Bureau (NCRB), Government of India
- **File:** `10_Property_stolen_and_recovered.csv`
- **Encoding:** `latin1`

---

## 2. 🏪 Super Store Data Analysis

### Overview
Exploratory data analysis of a sample retail Superstore dataset. The project uncovers sales and profit patterns across categories, regions, and time periods — helping understand business performance and support data-driven decisions.

### 📂 File
`Super_Store_Data_Analyse.ipynb`

### 🎯 Key Objectives
- Understand sales and profit trends across categories and sub-categories
- Identify top-performing and loss-making segments
- Explore how discounts affect profitability
- Analyze regional and state-level business performance

### 📊 Analysis Highlights
- **Category-wise** sales & profit — Technology leads; Furniture has high sales but low profit
- **Sub-category-wise** breakdown — Copiers yield highest profit; Tables and Bookcases show losses
- **Monthly trends** — Sales peak in November; profits generally increase year over year
- **State-wise** analysis — California & New York top in sales; Texas leads in profit loss despite high sales
- **Segment-wise** — Consumer > Corporate > Home Office in both sales and profit
- **Region-wise** — West region leads; Central region has lower profit despite higher sales than South
- **Discount vs Profit** correlation — Higher discounts negatively impact profit margins

### 🧰 Libraries Used
`numpy` · `pandas` · `matplotlib`

### 📁 Dataset
- **File:** `Sample - Superstore.csv`
- **Encoding:** `latin1`

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/akashmathiyazhagan/curly-bassoon.git
cd curly-bassoon
```

### 2. Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Launch a Notebook
```bash
# For Crime Analysis
jupyter notebook National_Crime_Data_Analyse.ipynb

# For Super Store Analysis
jupyter notebook Super_Store_Data_Analyse.ipynb
```

> **Note:** Update the CSV file paths in the notebooks to match your local directory before running.

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| Pandas | Data loading, cleaning, aggregation |
| NumPy | Numerical operations |
| Matplotlib | Charts and visualizations |
| Jupyter Notebook | Interactive analysis environment |

---

## 👤 Author

**Akash Mathiyazhagan**
- GitHub: [@akashmathiyazhagan](https://github.com/akashmathiyazhagan)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
