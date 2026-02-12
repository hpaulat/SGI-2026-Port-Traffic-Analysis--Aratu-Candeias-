This analysis examines the systemic risks associated with the **Port of Aratu-Candeias**, focusing on how seasonal weather patterns and operational disruptions create global ripple effects. By leveraging vessel-tracking data, the project maps the "cost of closure" across domestic and international supply chains. I performed this analysis for the Grand Sustainability Challenge 2026 at McGill University. I've attached a copy of the report to the repo as well for reference.

### **Core Analysis**

- **The Seasonal Risk Convergence:** Using a 10-year monthly time series (2014–2024), the analysis identifies a critical overlap where peak export volumes (603,000 metric tons/month) coincide with the regional rainy season (March–September). This synchronicity maximizes the economic impact of weather-induced shutdowns.
- **Systemic Shock Modeling:** The study treats Aratu and Salvador as a unified corridor due to their proximity ($<$50km) and shared management (CODEBA). A disruption is modeled as a joint failure, paralyzing two of Brazil's vital maritime gateways simultaneously.
- **Global Spillover Effects:** The analysis quantifies the "upstream" and "downstream" cargo shortfalls resulting from a one-week shutdown:
- **Upstream:** Exposure of ~700,000 metric tons, primarily affecting Santos (Brazil), Tangier-Med (Morocco), and Houston (USA).
- **Downstream:** A ~728,000 metric ton shortfall impacting industrial hubs like Cartagena (Colombia) and Las Palmas (Spain) that rely on Aratu for petrochemicals and fertilizers.

---

### **Project Structure**

- **`exploratory_analysis.ipynb`**: Processes raw vessel-tracking data and calculates seasonal volume averages.
- **`spillover.ipynb`**: Models the propagation of port shutdowns across the global network nodes.
- **`Data/`**: Contains the datasets derived from the **IMF PortWatch** initiative (a collaboration between the International Monetary Fund and the University of Oxford).

---

### **Methodology & Data Sources**

- **Primary Data:** Satellite-derived AIS vessel-tracking data via **PortWatch**.
- **Key Metrics:** Metric tons per month (MT/m), upstream/downstream cargo exposure, and seasonal peak windows.

---

### **How to Use**

1. **Environment Setup:** `pip install pandas matplotlib]`
2. **API Keys:** Ensure you place the CSV files in the folder before running.
3. **Run the Analysis:** Run the notebooks!

---
