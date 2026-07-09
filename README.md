# Global Population Demographics Visualizer

A comprehensive data analysis and visualization project exploring global population distributions, structural demographics, and regional growth trends using historical data from the World Bank.

## 📌 Project Overview
Understanding demographic shifts is crucial for socioeconomic planning, policy-making, and resource allocation. This project processes global demographic records to visualize distribution patterns, contrast population scales between high-growth and low-growth nations, and break down gender ratios across various geographical regions.

## 🚀 Key Features
* **Global Scale Comparison:** Compares the top 10 most populous countries against the bottom 10 to highlight demographic disparities.
* **Gender Breakdown:** Analyzes male versus female ratios utilizing stacked bar charts for structural insights.
* **Dynamic Distribution Plotting:** Visualizes continuous and categorical distributions using customized Matplotlib and Seaborn pipelines.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

## 📈 Methodology & Pipeline
1. **Data Acquisition:** Sourced historical population indicator metrics from the [World Bank Open Data](https://data.worldbank.org/indicator/sp.pop.totl).
2. **Data Cleaning & Wrangling:**
   * Handled missing values and filtered out regional aggregates to focus strictly on country-level records.
   * Restructured the dataset from wide format to long format for streamlined plotting.
3. **Exploratory Data Analysis (EDA):** Grouped data by country and year to compute comparative growth rates and gender distributions.
4. **Data Visualization:** Built clean, professional graphs with customized palettes and layout configurations.

## 💡 Key Insights
* **Demographic Disparities:** The difference in population magnitude between the top 10 countries and bottom 10 countries spans multiple orders of magnitude, illustrating high regional concentration.
* **Gender Ratios:** Stacked bar chart distributions show relatively stable gender ratios across major populous regions, with slight variances in specific demographic groups.

## 📂 Project Structure
```text
├── Task_01.ipynb                                   # Exploratory Data Analysis & Visualization Notebook
├── worldpopulationdata.csv                         # World Bank population dataset
└── README.md                                       # Project documentation
```

## 👤 Author
* **Khan Sohail**
  * [LinkedIn](https://www.linkedin.com/in/khan-sohail-386b2027a)
  * Email: ks646397@gmail.com
