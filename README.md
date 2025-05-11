# Global COVID-19 Data Analysis & Reporting

---

## 📖 About

This repository contains a comprehensive Jupyter Notebook that tracks and visualizes global COVID-19 trends—including cases, deaths, recoveries, and vaccinations. It guides you through data loading, cleaning, exploratory analysis, and interactive visualizations, culminating in actionable insights.

---

## 🎯 Objectives

* **Data Acquisition & Cleaning**: Fetch and preprocess data from Our World in Data.
* **Exploratory Data Analysis**: Perform EDA to uncover patterns and correlations.
* **Visualization**: Create line charts, bar plots, heatmaps, and choropleth maps.
* **Insight Generation**: Summarize key trends, anomalies, and actionable takeaways.
* **Documentation**: Provide clear narrative and code comments for reproducibility.

---

## 🛠️ Tech Stack

* **Language**: Python 3.x
* **Notebook**: Google Colab Notebook
* **Libraries**:

  * pandas
  * matplotlib
  * seaborn
  * plotly.express

---

## 📋 Project Structure

```
├── README.md
├── requirements.txt
├── COVID19_Data_Analysis.ipynb
├── data/
│   └── owid-covid-data.csv  
└── visuals/  
    ├── charts/  
    └── maps/    
```

---

## 🚀 Getting Started

### Prerequisites

* Python 3.x
* pip (package manager)

### Installation

```bash
# Clone the repo
git clone <repository_url>
cd <repository_folder>

# Install dependencies
pip install -r requirements.txt
```

### Running the Notebook

1. Launch Google Colaboratory:

   ```bash
   googe colab notebook
   ```
2. Open `COVID19_Data_Analysis.ipynb`.
3. Run cells in order to reproduce the analysis and visualizations.

---

## 💡 Key Insights

1. **Early Epicenters**: Initial outbreaks in China, Italy, and the USA, shifting later to India and Brazil.
2. **Death Rate Variances**: Marked differences across countries reflect healthcare capacity and reporting.
3. **Vaccine Impact**: Strong negative correlation between vaccination rates and new cases highlights effectiveness.
4. **Data Artifacts**: Sudden spikes often indicate reporting backfills rather than epidemiological spikes.
5. **Regional Recovery Trends**: Later waves peaked faster but declined more rapidly due to improved responses.

---

## 📄 License

This is a Practice project with no licences

