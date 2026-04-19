# 🌫️ India AQI Data Analysis

An end-to-end data analytics project analyzing **Air Quality Index (AQI)** across 25 Indian cities from 2015 to 2020, using Python, SQL, and an interactive web dashboard.

---

## 📌 Project Overview

Air pollution is one of India's most critical public health challenges. This project explores city-level AQI data to uncover seasonal patterns, identify the most polluted cities, and understand which pollutants drive poor air quality.

---

## 📂 Repository Structure

```
AQI-India-Analysis/
│
├── AQI_India_Project.ipynb     # Main analysis notebook (Python + SQL)
├── city_day.csv                # Raw dataset
├── AQI_India_Data.csv          # Cleaned & processed dataset
└── AQI_India_Dashboard.html    # Interactive dashboard (open in browser)
```

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|------|-------|
| Python | Data cleaning, EDA, visualization |
| pandas | Data manipulation |
| matplotlib / seaborn | Charts and heatmaps |
| SQLite (sqlite3) | SQL queries on processed data |
| HTML / JavaScript | Interactive dashboard |

---

## 📊 Key Analyses

- **Top 10 most polluted cities** — ranked by average AQI
- **Monthly AQI trend** — seasonal pattern across the year
- **Pollutant correlation** — which pollutants most impact AQI
- **AQI category distribution** — Good → Severe breakdown
- **SQL queries** — city-wise averages, monthly patterns, bucket counts

---

## 🔍 Key Findings

- 📈 **AQI peaks in winter months (Nov–Jan)** due to crop burning, low wind speeds, and temperature inversions
- 🏭 **PM2.5 has the highest correlation (0.92)** with AQI — the primary driver of poor air quality
- 🌧️ **Monsoon months (Jun–Aug)** provide the only consistent relief across all regions
- 🗺️ **North Indian cities** (Delhi, Patna, Gwalior) consistently show the highest pollution levels
- 🌴 **South Indian cities** (Kochi, Coimbatore, Bengaluru) maintain comparatively lower AQI

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/pratik-pawar11/AQI-India-Analysis.git
cd AQI-India-Analysis
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn
```

**3. Open the notebook**
```bash
jupyter notebook AQI_India_Project.ipynb
```

**4. View the dashboard**

Open `AQI_India_Dashboard.html` directly in any browser — no setup needed.

Or view it live: [**AQI India Dashboard →**](https://pratik-pawar11.github.io/AQI-India-Analysis/AQI_India_Dashboard.html)

---

## 📁 Dataset

The dataset (`city_day.csv`) contains daily AQI readings for Indian cities with the following columns:

| Column | Description |
|--------|-------------|
| `Date` | Date of reading |
| `City` | City name |
| `PM2.5` | Fine particulate matter (µg/m³) |
| `PM10` | Coarse particulate matter (µg/m³) |
| `NO2` | Nitrogen dioxide |
| `CO` | Carbon monoxide |
| `SO2` | Sulphur dioxide |
| `AQI` | Air Quality Index value |
| `AQI_Bucket` | Category (Good / Moderate / Poor / Very Poor / Severe) |

---

## 📬 Contact

**Pratik Pawar**
- GitHub: [@pratik-pawar11](https://github.com/pratik-pawar11)
- LinkedIn: [linkedin.com/in/pratikpawar14](https://www.linkedin.com/in/pratikpawar14/)
- Email: pratikpawar1250@gmail.com

---

*Made with Python, SQL, and curiosity about India's air quality 🇮🇳*
