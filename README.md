# 🌾 Seasonal Agriculture Performance Analysis

## 📊 End-to-End Data Analytics & Power BI Project

**Domain:** Agriculture  
**Project Type:** Data Analytics  
**Student:** Raj Yadav  
**Course:** B.Tech CSE (AI & ML)  
**College:** Anand Engineering College, Agra

---

## 📌 Project Overview

**Seasonal Agriculture Performance Analysis** is an end-to-end Data Analytics project focused on understanding agricultural performance across different seasons, crops, irrigation methods, and states.

The project uses a farm-level agricultural dataset to analyze crop yield, production, revenue, cost, profit, water usage, water efficiency, irrigation methods, seasonal performance, state-wise profitability, and other agricultural factors.

The project follows a complete analytics workflow from data preparation and exploratory data analysis to visualization, Power BI dashboard development, business insights, and recommendations.

---

## 🎯 Problem Statement

Agricultural performance can vary across seasons, crops, locations, irrigation methods, environmental conditions, and farming practices.

Without systematic analysis, it can be difficult to identify:

- Which season performs better?
- Which crops have higher yields?
- Which irrigation methods are more efficient?
- Which states have higher profitability?
- How do production, revenue, cost, and profit vary?
- What relationships exist between yield and water efficiency?

**Problem:**

> How can data analytics and visualization be used to identify important patterns, trends, relationships, and performance differences in agricultural data across seasons, crops, irrigation methods, and states?

---

## 🎯 Project Objectives

1. Understand the structure and quality of the agricultural dataset.
2. Inspect and prepare the data for analysis.
3. Identify and handle missing values.
4. Check duplicate records.
5. Perform descriptive and statistical analysis.
6. Analyze agricultural performance across seasons.
7. Compare crop yield across different seasons.
8. Analyze irrigation methods and water efficiency.
9. Compare profitability across states.
10. Study relationships between important numerical variables.
11. Identify important patterns and trends.
12. Create meaningful data visualizations.
13. Develop an interactive Power BI dashboard.
14. Generate evidence-based business insights.
15. Provide data-driven recommendations.

---

## 📊 Dataset Description

The project uses the following dataset:

`seasonal_agriculture_performance_dataset.csv`

The dataset contains:

- **4,000 farm records**
- **28 columns**

The dataset includes information related to farms, crops, seasons, locations, environmental conditions, agricultural inputs, production, financial performance, water usage, and disease/pest risk.

### Main Dataset Categories

| Category | Examples |
|---|---|
| Farm Information | Farm ID, State, District |
| Crop Information | Crop, Season |
| Farm Characteristics | Farm Area |
| Environmental Factors | Rainfall, Temperature, Humidity, Sunlight |
| Soil Conditions | Soil pH, Soil Moisture |
| Nutrients | Nitrogen, Phosphorus, Potassium |
| Agricultural Inputs | Fertilizer, Pesticide |
| Seed Information | Seed Quality Score |
| Production | Yield, Production |
| Financial Metrics | Market Price, Cost, Revenue, Profit |
| Water Analysis | Water Used, Water Efficiency |
| Risk | Disease/Pest Risk |

### Important Variables

**Categorical Variables**

- State
- District
- Crop
- Season
- Irrigation Method
- Fertilizer Used
- Pesticide Used
- Seed Quality

**Numerical Variables**

- Farm Area
- Rainfall
- Average Temperature
- Humidity
- Sunlight Hours
- Soil pH
- Soil Moisture
- Nitrogen
- Phosphorus
- Potassium
- Fertilizer Usage
- Pesticide Usage
- Seed Quality Score
- Yield
- Production
- Market Price
- Total Cost
- Revenue
- Profit
- Water Used
- Water Efficiency
- Disease/Pest Risk

---

## 🛠️ Tools & Technologies

### Programming & Data Analysis

- Python
- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Notebook

- Jupyter Notebook
- Google Colab

### Business Intelligence

- Microsoft Power BI

### Version Control

- Git
- GitHub

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Inspection
   ↓
Data Cleaning & Preparation
   ↓
Exploratory Data Analysis
   ↓
Descriptive & Statistical Analysis
   ↓
Correlation Analysis
   ↓
Data Visualization
   ↓
Power BI Dashboard
   ↓
Business Insights
   ↓
Recommendations
   ↓
Final Documentation
```

---

## 🧹 Data Cleaning & Preparation

The dataset was inspected and prepared before performing the main analysis.

### 1. Dataset Inspection

The dataset structure was examined using:

- Dataset shape
- Column names
- First and last records
- Data types
- Unique values
- Descriptive statistics

The dataset contains:

**4,000 rows × 28 columns**

### 2. Missing Value Analysis

Missing values were identified using Pandas.

The original dataset contained:

**120 missing values**

Missing values were handled using median imputation for numerical columns where required.

After treatment:

**Remaining missing values: 0**

### 3. Duplicate Record Check

Duplicate records were checked using Pandas.

The analysis found:

**0 duplicate rows**

The dataset therefore retained:

**4,000 rows × 28 columns**

### 4. Data Type Review

Numerical and categorical variables were reviewed to ensure that the data was suitable for statistical analysis, visualization, and Power BI.

### 5. Power Query Preparation

The dataset was also prepared in Power Query before building the Power BI dashboard.

The preparation included:

- Promoting headers
- Correcting data types
- Removing blank rows
- Checking data quality
- Removing duplicate records where required

---

## 🔍 Exploratory Data Analysis

The project performs multiple levels of exploratory data analysis.

### Descriptive Analysis

Descriptive statistics were calculated for numerical variables, including:

- Mean
- Median
- Standard deviation
- Minimum
- Maximum

### Univariate Analysis

Individual variables were analyzed using appropriate visualizations and summary statistics.

Examples include:

- Season distribution
- Crop distribution
- Yield distribution
- Profit distribution
- Water-efficiency distribution

### Bivariate Analysis

Relationships between two variables were investigated.

Examples include:

- Crop vs Yield
- Season vs Yield
- State vs Profit
- Irrigation Method vs Water Efficiency
- Farm Area vs Yield
- Yield vs Water Efficiency

### Multivariate Analysis

Multiple variables were analyzed together to understand more complex agricultural patterns.

Examples include:

- Crop × Season × Yield
- State × Profitability
- Irrigation Method × Yield × Water Efficiency
- Seasonal economic performance

### Correlation Analysis

A correlation analysis was performed to study relationships among numerical variables.

One of the strongest observed relationships was between:

**Yield and Water Efficiency**

The correlation was approximately:

**0.915**

This indicates a strong positive association in the analyzed dataset.

> Correlation indicates association and does not by itself prove causation.

---

## 📈 Data Visualizations

The project includes multiple visualizations created during the analysis.

Major visualizations include:

1. Distribution of Records by Season
2. Average Crop Yield Across Seasons
3. Water Efficiency by Irrigation Method
4. Average Agricultural Profit by State
5. Correlation Analysis / Heatmap
6. Crop Yield by Season
7. Seasonal Performance Comparison
8. State-wise Economic Performance

The complete analysis and visualizations are available in the Jupyter Notebook and result screenshots included in the repository.

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was developed using the agricultural dataset.

### Dashboard Title

**SEASONAL AGRICULTURE PERFORMANCE DASHBOARD**

### KPI Cards

The dashboard includes four key performance indicators:

- **Total Production**
- **Total Revenue**
- **Total Profit**
- **Average Yield**

### Interactive Slicers

The dashboard includes filters for:

- State
- Crop
- District
- Season

These slicers allow users to interactively filter the dashboard and explore agricultural performance.

### Dashboard Visualizations

The dashboard includes:

- **Profit by State** — Map
- **Revenue & Profit by Season** — Combination Chart
- **Production Share by Season** — Donut Chart
- **Water Efficiency by Crop** — Treemap
- **Farm Area vs Yield** — Scatter Chart
- **Crop Yield by Season** — Matrix

These visuals provide insights into production, financial performance, yield, geographic differences, seasonal performance, and resource efficiency.

### Dashboard Preview

The Power BI dashboard screenshot is available in the `dashboard screenshot` folder.

---

## 💡 Key Business Insights

### 1. Kharif has the highest average yield

Kharif has an average yield of approximately **5.64 tonnes/ha**, compared with approximately **5.08 tonnes/ha in Rabi** and **4.67 tonnes/ha in Zaid**.

This indicates that Kharif records show the strongest average yield performance in the analyzed dataset.

### 2. Kharif has the highest average profit

Average profit is approximately:

| Season | Average Profit |
|---|---:|
| Kharif | ₹178,915 |
| Rabi | ₹87,689 |
| Zaid | -₹24,805 |

Kharif therefore shows the strongest average economic performance among the three seasons.

### 3. Crop performance varies across seasons

Crop yields vary across seasons.

Most crops show higher average yields in Kharif and comparatively lower average yields in Zaid.

This indicates that crop performance should be evaluated together with seasonal conditions.

### 4. Sugarcane has substantially higher yield values

Sugarcane records have considerably higher average yield values than several other crops such as Wheat, Rice, Maize, and Pulses.

However, raw yield comparisons should also consider crop characteristics and production requirements.

### 5. Rainfed farms show the highest recorded water-efficiency value

Rainfed farms have an average water-efficiency value of approximately **7.56 tonnes per 1000 m³**.

This result should be interpreted carefully because recorded irrigation water does not necessarily represent total water requirements.

### 6. Flood irrigation has the lowest average water efficiency

Flood irrigation has an average water-efficiency value of approximately **3.44 tonnes per 1000 m³**.

This is the lowest among the irrigation methods analyzed.

### 7. Drip irrigation has higher average yield than flood irrigation

The observed average yield is approximately:

- **Drip irrigation:** 6.62 tonnes/ha
- **Flood irrigation:** 4.90 tonnes/ha

This shows an association between drip irrigation and higher average yield in the available records.

However, this observational comparison does not prove that irrigation method alone caused the difference.

### 8. Profitability differs across states

The state-wise analysis shows substantial differences in average agricultural profitability.

**Punjab and Maharashtra** have the highest average profits, while **Andhra Pradesh** has the lowest average profit among the states analyzed.

These differences may be influenced by crop mix, costs, market prices, and farming conditions.

### 9. Yield and water efficiency have a strong positive association

The correlation between yield and water efficiency is approximately **0.915**.

Higher yield values tend to occur alongside higher water-efficiency values in this dataset.

> This is a correlation and does not establish causation.

### 10. Data quality required attention

The original dataset contained **120 missing values**.

These missing values were identified during data-quality analysis and handled before the final analysis.

After treatment:

**Remaining missing values: 0**

---

## 🎯 Business Recommendations

### 1. Consider seasonal differences in agricultural planning

Since Kharif records show higher average yield and profit, seasonal performance should be considered when planning agricultural activities.

Crop-specific and regional conditions should also be evaluated.

### 2. Evaluate irrigation using both yield and water efficiency

Irrigation decisions should consider both:

- Crop yield
- Water efficiency

rather than evaluating water usage alone.

### 3. Review flood-irrigation efficiency

Flood irrigation shows the lowest average water-efficiency value among the analyzed irrigation methods.

Where technically and economically appropriate, alternative irrigation approaches can be evaluated.

### 4. Consider crop-season combinations

Because crop performance varies across seasons, agricultural planning should consider:

**Crop + Season + Region**

rather than evaluating crops independently.

### 5. Consider regional economic differences

The variation in average profitability across states indicates that regional factors should be considered when making agricultural planning and economic decisions.

---

## 📌 Key Questions Answered by the Project

The project helps answer questions such as:

- Which season has the highest average yield?
- Which season has the highest average profit?
- How does crop performance vary across seasons?
- Which crops have higher yield values?
- Which irrigation methods have higher water efficiency?
- How does irrigation method relate to yield?
- Which states have higher average agricultural profit?
- How are yield and water efficiency related?
- How do revenue, profit, production, and yield change across seasons?
- How does agricultural performance change when filtered by state, crop, district, or season?

---

## 📁 Repository Structure

```text
Seasonal-Agriculture-Performance-Analysis-
│
├── dashboard screenshot/
│   └── Power BI dashboard screenshots
│
├── dataset/
│   └── seasonal_agriculture_performance_dataset.csv
│
├── result screenshots/
│   └── Analysis and visualization screenshots
│
├── Seasonal_Agriculture_Performance_Data_Analytics_RajYadav.ipynb
│
├── SEASONAL AGRICULTURE PERFORMANCE DASHBOARD.pbix
│
├── Major Project_Seasonal Agriculture Performance Analysis..pdf
│
├── Major_Project_PPT_RajYadav.pptx
│
└── README.md
```

---

## 📂 Project Files

### Jupyter Notebook

**File:**

`Seasonal_Agriculture_Performance_Data_Analytics_RajYadav.ipynb`

The notebook contains:

- Dataset loading
- Data inspection
- Data cleaning
- Missing-value analysis
- Duplicate checking
- Descriptive statistics
- Statistical analysis
- Outlier investigation
- Univariate analysis
- Bivariate analysis
- Multivariate analysis
- Correlation analysis
- Seasonal analysis
- Crop analysis
- Irrigation analysis
- State-wise analysis
- Visualizations
- Key insights
- Recommendations
- Conclusion

### Power BI Dashboard

**File:**

`SEASONAL AGRICULTURE PERFORMANCE DASHBOARD.pbix`

The Power BI file contains the interactive dashboard with:

- KPI cards
- Slicers
- Map
- Combination chart
- Donut chart
- Treemap
- Scatter chart
- Matrix

### Project Report

**File:**

`Major Project_Seasonal Agriculture Performance Analysis..pdf`

The repository contains the project report documenting the project and analysis.

### Project Presentation

**File:**

`Major_Project_PPT_RajYadav.pptx`

The repository contains the project presentation.

### Screenshots

The repository also contains:

- Power BI dashboard screenshots
- Analysis and visualization screenshots

These are available in:

- `dashboard screenshot/`
- `result screenshots/`

---

## ▶️ How to Run the Project

### Python / Jupyter Notebook

#### 1. Clone the repository

```bash
git clone https://github.com/rajyadav-590/Seasonal-Agriculture-Performance-Analysis-.git
```

#### 2. Open the project folder

```bash
cd Seasonal-Agriculture-Performance-Analysis-
```

#### 3. Install the required Python libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

#### 4. Open the notebook

Open:

```text
Seasonal_Agriculture_Performance_Data_Analytics_RajYadav.ipynb
```

#### 5. Dataset

The dataset is available in:

```text
dataset/
```

#### 6. Run the notebook

Run the notebook cells in sequence to reproduce the data analysis and visualizations.

---

## 📊 How to Use the Power BI Dashboard

1. Open:

`SEASONAL AGRICULTURE PERFORMANCE DASHBOARD.pbix`

2. If Power BI requests the dataset location, select:

`dataset/seasonal_agriculture_performance_dataset.csv`

3. Refresh the data if required.

4. Use the available slicers to interact with the dashboard.

5. Select different states, crops, districts, or seasons to explore the corresponding changes in KPIs and visualizations.

---

## 🚀 Future Scope

The project can be extended in the future by:

- Adding larger and more diverse agricultural datasets.
- Including additional states and crops.
- Incorporating historical agricultural data.
- Integrating weather data.
- Integrating real-time market-price data.
- Adding advanced crop profitability analysis.
- Developing crop-yield prediction models.
- Developing crop recommendation systems.
- Developing irrigation recommendation systems.
- Adding automated data refresh.
- Deploying the dashboard for wider accessibility.

---

## ⚠️ Limitations

The findings should be interpreted within the scope of the available dataset.

- The dataset contains a finite number of farm-level records.
- The analysis identifies associations and patterns rather than proving causation.
- State-level differences may be influenced by crop mix, costs, market prices, and farming conditions.
- Irrigation comparisons are observational.
- Water-efficiency results for rainfed farms should be interpreted carefully because recorded irrigation water does not represent total water requirements.
- Yield should be compared with consideration for crop characteristics and production requirements.

---

## 🏁 Conclusion

The **Seasonal Agriculture Performance Analysis** project demonstrates how Data Analytics can be used to transform agricultural data into meaningful insights.

The project analyzed agricultural performance across:

- Seasons
- Crops
- Irrigation methods
- States
- Production
- Revenue
- Cost
- Profit
- Water usage
- Water efficiency

The analysis identified meaningful differences in seasonal performance, crop yield, irrigation efficiency, and state-level profitability.

Kharif showed stronger average yield and profit compared with Rabi and Zaid in the analyzed records. Differences were also observed between irrigation methods and across states.

The Power BI dashboard provides an interactive way to explore these findings using KPI cards, slicers, maps, charts, and detailed analytical views.

Overall, the project demonstrates an end-to-end Data Analytics workflow:

```text
Data
  ↓
Data Cleaning
  ↓
EDA
  ↓
Statistical Analysis
  ↓
Correlation Analysis
  ↓
Visualization
  ↓
Power BI Dashboard
  ↓
Business Insights
  ↓
Recommendations
```

---

## 👨‍💻 Author

**Raj Yadav**

**B.Tech CSE (AI & ML)**  
**Anand Engineering College, Agra**

**Project:** Seasonal Agriculture Performance Analysis

---

## 📜 License

This project is created for educational and academic purposes.
