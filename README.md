# 🇦🇩 andorra-demographic-analysis

A data analysis project exploring demographic trends in Andorra 
using official statistics from the Departament d'Estadística d'Andorra.

![Python](https://img.shields.io/badge/python-3.14%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-stable-brightgreen)
![Data](https://img.shields.io/badge/data-estadistica.ad-orange)

---

## 🔍 Key Findings

- **Andorrans are a minority in their own country** — only 44.7% of residents hold Andorran nationality
- **Population grew 27%** between 2011 and 2025, from 69,772 to 89,058 inhabitants
- **Portuguese community declining** — down 22% since 2010, from 10,832 to 8,428
- **Argentine community exploded** — grew 547% since 2010, accelerating sharply after 2022
- **Canillo is the fastest growing parish** — nearly doubled its population since 2009

---

## 📊 Visualizations

### Total Population Evolution (2009-2025)
![Total Population](output/total_population.png)

### Population by Nationality (2010-2025)
![Nationality Evolution](output/nationality_evolution.png)

### Argentine vs Portuguese Growth (Base 100)
![Relative Growth](output/relative_growth.png)

### Nationality Distribution in 2025
![Distribution 2025](output/distribution_2025.png)

### Population by Parish (2009-2025)
![Parish Evolution](output/parish_evolution.png)

---

## 📁 Project Structure
andorra-demographic-analysis/

├── analysis.ipynb          # Main Jupyter notebook with full analysis

├── data/

│   ├── POBLACIÓ_TOTAL.csv

│   ├── POBLACIÓ_PER_NACIONALITAT.csv

│   ├── POBLACIÓ_PER_PARRÒQUIA.csv

│   └── POBLACIÓ_REGISTRADA_TOTAL.csv

├── output/                 # Generated charts

└── README.md
---

## 🗃️ Data Source

All data sourced from the **Departament d'Estadística d'Andorra**:
- [estadistica.ad](https://www.estadistica.ad)
- Dataset series: 010101010001, 010101010007, 010101010002, 010101040001

---

## ⚙️ Installation

```bash
git clone https://github.com/david-deluca/andorra-demographic-analysis.git
cd andorra-demographic-analysis
pip install jupyter pandas matplotlib seaborn
jupyter notebook analysis.ipynb
```

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.