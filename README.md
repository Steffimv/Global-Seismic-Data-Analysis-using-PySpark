# Global Seismic Data Analysis using PySpark

## Overview
This project presents a comprehensive analysis of global seismic activity using **Apache Spark (PySpark)**.  
The objective is to process large-scale earthquake datasets to uncover **spatial and temporal trends**, evaluate **magnitude–depth correlations**, and derive insights into **regional seismic behavior**.

By leveraging distributed data processing through PySpark, this project demonstrates scalable big-data analytics and visual exploration of complex, real-world geophysical phenomena.

---

## Objectives
- Perform **data cleaning and preprocessing** on global earthquake datasets.  
- Conduct **spatio-temporal trend analysis** to study the frequency and intensity of seismic events.  
- Examine **magnitude–depth relationships** to understand seismic impact variation.  
- Utilize **PySpark’s distributed computing** for efficient handling of large datasets.  
- Provide **visual analytics** through interactive charts and geographic mapping.  

---

## Technologies and Tools
| Category | Tools / Libraries |
|-----------|------------------|
| Programming Language | Python |
| Big Data Framework | Apache Spark (PySpark) |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Plotly |
| Environment | Jupyter Notebook |
| Dataset Source | [Global Seismic Dataset (2000–2024)](https://github.com/nadeeshafdo/SeismicDataWorldwide/blob/main/query_M4.5%2B_2000-2024.csv) |
---

## Methodology
1. **Data Acquisition** – Load and integrate global earthquake records from open data sources.  
2. **Data Preprocessing** – Clean, filter, and structure the dataset using PySpark DataFrames.  
3. **Exploratory Data Analysis** –  
   - Temporal analysis: Yearly and monthly trends.  
   - Spatial analysis: Mapping of latitude, longitude, and magnitude.  
4. **Statistical Insights** – Evaluate distributions of magnitude and depth.  
5. **Performance Evaluation** – Assess Spark job efficiency, partitioning, and cache utilization.  

---

## Results and Insights
- Identified temporal clusters of high seismic activity.  
- Detected regional hotspots for frequent earthquakes.  
- Demonstrated scalable analysis of >500K records within seconds using Spark.  
- Generated performance metrics indicating efficient caching and parallel processing.  

*(Detailed outputs and visualizations are available in the notebook `BDA_Project.ipynb`.)*

---

## How to Run
```bash
# Clone the repository
git clone https://github.com/<your-username>/Global-Seismic-Data-Analysis-using-PySpark.git
cd Global-Seismic-Data-Analysis-using-PySpark

# Install required dependencies
pip install pyspark matplotlib seaborn plotly pandas numpy

# Launch Jupyter Notebook
jupyter notebook BDA_Project.ipynb
