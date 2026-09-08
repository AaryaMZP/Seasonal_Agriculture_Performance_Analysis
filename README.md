# Seasonal Agriculture Performance Analysis 🌾

**Major Project — VOIS AICTE DATA ANALYTICS INTERNSHIP**

Analysis of agricultural performance across different seasons, regions, and farming conditions to uncover meaningful patterns, trends, and relationships in crop production, resource usage, and economic outcomes.

## 📌 Overview

Agricultural activities are influenced by seasonal variations in environmental conditions, farming practices, resource availability, and market conditions — causing performance to differ from one season to another. This project analyzes a seasonal agricultural dataset to investigate these differences by identifying patterns, trends, relationships, and variations across seasons, crops, and regions.

## 🎯 Objectives

* Explore and understand the dataset
* Clean and prepare the data for analysis
* Examine how agricultural performance varies across seasons
* Identify important seasonal patterns and trends
* Investigate relationships between seasonal conditions and agricultural outcomes
* Compare relevant groups (crops, states, irrigation methods) across seasons
* Identify significant differences or unusual patterns
* Apply appropriate statistical and visualization techniques
* Develop evidence-based conclusions and recommendations

## 📂 Dataset

**File:** `seasonal_agriculture_performance_dataset.csv`

Each row represents a farm's performance for a given season.

### Key Columns

**Location & Crop:**

* `Farm_ID`
* `State`
* `District`
* `Crop`
* `Season`
* `Farm_Area_Hectares`

**Environmental Conditions:**

* `Rainfall_mm`
* `Avg_Temperature_C`
* `Humidity_pct`
* `Sunlight_Hours_Day`
* `Soil_pH`
* `Soil_Moisture_pct`

**Resource Usage:**

* `Nitrogen_kg_ha`
* `Phosphorus_kg_ha`
* `Potassium_kg_ha`
* `Irrigation_Method`
* `Fertilizer_kg_ha`
* `Pesticide_Litre_ha`
* `Water_Used_m3`
* `Water_Efficiency_t_per_1000m3`

**Production:**

* `Seed_Quality_Score`
* `Yield_Tonnes_Ha`
* `Production_Tonnes`
* `Disease_Pest_Risk_pct`

**Economics:**

* `Market_Price_INR_Tonne`
* `Total_Cost_INR`
* `Revenue_INR`
* `Profit_INR`

## 🛠️ Tech Stack

* Python
* Pandas / NumPy
* Matplotlib / Seaborn
* Jupyter Notebook

## 📁 Project Structure

```text
Seasonal_Agriculture_Performance_Analysis/
│
├── seasonal.ipynb
├── seasonal_agriculture_performance_dataset.csv
├── Major_Project_Seasonal_Agriculture_Performance_Analysis.pdf
├── Aarya_Dubey_Seasonal_DA.pptx
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Make sure Python and Jupyter Notebook are installed on your system.

The required Python libraries can be installed using:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Usage

```bash
git clone https://github.com/your-username/Seasonal_Agriculture_Performance_Analysis.git
cd Seasonal_Agriculture_Performance_Analysis
jupyter notebook seasonal.ipynb
```

## 🔑 Key Questions Explored

* How does agricultural performance vary across seasons?
* What major seasonal patterns can be observed?
* Which characteristics change between seasons (yield, cost, resource usage)?
* Are there noticeable variations in resource usage (water, fertilizer) across seasons?
* Are there relationships between seasonal environmental conditions and performance?
* How do economic outcomes (revenue, profit) vary across seasons?
* Are some seasonal patterns consistent across different states or crops?
* What insights and recommendations can support better seasonal agricultural planning?

## 📊 Key Findings

* Kharif is the strongest season overall — highest average yield (5.64 t/ha) and profit (₹1,78,915), driven by higher rainfall (852 mm avg) and
  warmer temperatures (28.5°C avg).
* Zaid is the weakest season — lowest average yield (4.67 t/ha), and the only season with a negative average profit (-₹24,805), largely due to higher   costs against lower revenue.
* Loss-making farms increase sharply by season: 42.2% of Kharif farms run at a loss vs. 51.1% in Rabi and 64.5% in Zaid.
* Sugarcane consistently gives the highest yield across all three seasons (38–53 t/ha), far ahead of other crops.
* Irrigation method strongly affects water efficiency: Rainfed (7.56 t/1000m³) and Drip (6.27) are far more water-efficient than Sprinkler (4.67) and   Flood (3.44).
* Rainfall and fertilizer usage show almost no correlation with yield (r ≈ 0.03 and 0.001), suggesting yield is driven more by crop type, irrigation    method, and soil/seed quality than by these two factors alone.
* Higher temperature is linked to higher disease/pest risk (r ≈ 0.25), consistent with hotter seasons like Kharif and Zaid.
* Punjab and Maharashtra are the most profitable states (avg profit ~₹1,35,000–1,36,000/farm), while Andhra Pradesh is the least profitable
  (~₹73,500/farm).


## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to open a pull request.



## 📬 Author

**Aarya Dubey**


