# Global Sustainable Energy Data Analysis

This repository contains a completed data analysis project developed for the **Data Analytics course** offered by **Correlation One**. It leverages global datasets on sustainable energy to explore insights around renewable energy trends, correlations among variables, and regional comparisons.

---

## 📌 Objective

To analyze and visualize global sustainable energy data to uncover trends, relationships, and insights.

---

## 📊 Data Source

- **Origin**: The primary dataset is sourced from Kaggle: *Global Data on Sustainable Energy* by Ansh Tanwar  
- **Link**: [Kaggle Dataset](https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy?resource=download)  
- This dataset includes a broad range of metrics related to sustainable energy across countries and regions (e.g., renewable energy production, consumption, carbon emissions, etc.).

---

## 📂 Repository Structure

```text
Global_sustainable_energy_data/
├── Notebooks/
│   └── Sustainable_energy_data.ipynb   # Main analysis notebook
├── data/                               # Folder for storing the Kaggle dataset
├── README.md                           # Project overview and documentation

## 📝 Analysis Notebook: *Sustainable_energy_data.ipynb*

This core Jupyter Notebook includes:

1. **Data Import & Cleansing**  
   - Reads in the dataset and handles missing values, data types, and inconsistencies.

2. **Exploratory Data Analysis (EDA)**  
   - Computes summary statistics, visualizes distributions, and examines trends over time.

3. **Correlation Analysis**  
   - Calculates correlation coefficients between variables (e.g., renewable energy output vs. emissions).  
   - Visualizes these relationships via scatter plots, heatmaps, etc.

4. **Regional & Temporal Insights**  
   - Compares energy metrics across regions (e.g., continents, income groups).  
   - Tracks evolution over time where available.

5. **Conclusions & Recommendations**  
   - Summarizes key findings.  
   - Suggests areas for further exploration or potential applications (e.g., policy analysis, forecasting).

---

## ⚙️ How to Run

1. **Clone the repository**  
   ```bash
   git clone https://github.com/xKatyJane/Global_sustainable_energy_data.git
   cd Global_sustainable_energy_data
   ```

2. Launch the notebook
   ```bash
   jupyter notebook
   ```
   Open Notebooks/Sustainable_energy_data.ipynb and run the cells to reproduce the analysis.
