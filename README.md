This analysis examines the systemic risks associated with the **Port of Aratu-Candeias**, focusing on how seasonal weather patterns and operational disruptions create global ripple effects. By leveraging high-frequency vessel-tracking data, the project maps the "cost of closure" across domestic and international supply chains.

### **Core Analysis Pillars**

- **The Seasonal Risk Convergence:** Using a 10-year monthly time series (2014–2024), the analysis identifies a critical overlap where peak export volumes (603,000 metric tons/month) coincide with the regional rainy season (March–September). This synchronicity maximizes the economic impact of weather-induced shutdowns.
- **Systemic Shock Modeling:** The study treats Aratu and Salvador as a unified corridor due to their proximity ($<$50km) and shared management (CODEBA). A disruption is modeled as a joint failure, paralyzing two of Brazil's vital maritime gateways simultaneously.
- **Global Spillover Effects:** The analysis quantifies the "upstream" and "downstream" cargo shortfalls resulting from a one-week shutdown:
- **Upstream:** Exposure of ~700,000 metric tons, primarily affecting Santos (Brazil), Tangier-Med (Morocco), and Houston (USA).
- **Downstream:** A ~728,000 metric ton shortfall impacting industrial hubs like Cartagena (Colombia) and Las Palmas (Spain) that rely on Aratu for petrochemicals and fertilizers.

---

### **Project Structure**

- **`[Insert Notebook Name].ipynb`**: Processes raw vessel-tracking data and calculates seasonal volume averages.
- **`[Insert Notebook Name].ipynb`**: Models the propagation of port shutdowns across the global network nodes.
- **`Data/`**: Contains the datasets derived from the **IMF PortWatch** initiative (a collaboration between the International Monetary Fund and the University of Oxford).

---

### **Methodology & Data Sources**

- **Primary Data:** Satellite-derived AIS vessel-tracking data via **PortWatch**.
- **Weather Data:** Regional precipitation and climate risk profiles sourced from **[Insert Source, e.g., Federative Republic of Brazil, 2023]**.
- **Key Metrics:** Metric tons per month (MT/m), upstream/downstream cargo exposure, and seasonal peak windows.

---

### **How to Use**

1. **Environment Setup:** `pip install [Insert Key Libraries, e.g., pandas, matplotlib, geopandas]`
2. **API Keys:** Ensure you have access to `[Insert API/Data Source if applicable]` or place the CSV files in the `/data` folder.
3. **Run the Analysis:** Start with `[Insert Main Notebook Name]` to reproduce the seasonal vulnerability charts.

---

Would you like me to draft a **"Key Findings"** bulleted list based on the specific metric tons mentioned to highlight the project's impact?
