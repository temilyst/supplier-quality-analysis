# Analysis Notes – Supplier Quality

## Understanding the Data
The dataset contains information about supplier performance across multiple manufacturing plants.

### Key Fields:
- Vendor  
- Plant Location  
- Material Type  
- Defect Type  
- Total Defect Quantity  
- Total Downtime Minutes  

This data allows us to evaluate both quality issues (defects) and operational impact (downtime).

---

## Initial Observations
- Defects are linked to both vendor and material type  
- Downtime provides a measure of business impact  
- Vendor performance may vary across different plants  

---

## Key Analysis Questions

### 1. Vendor Performance
- Which vendors have the highest defect quantities?  
- Which vendors cause the most downtime?  

### 2. Plant Performance
- Which plants are experiencing the most defects?  
- Are some plants more affected than others?  

### 3. Material Analysis
- Which material types are most prone to defects?  
- Do certain materials consistently fail across vendors?  

### 4. Combined Analysis
- Vendor + Material → poor quality combinations  
- Vendor + Plant → inconsistent performance  
- Material + Plant → location-specific issues  

---

## Planned Dashboard Metrics

- Total Defect Quantity  
- Total Downtime Minutes  
- Defect Rate (to be calculated)  
- Downtime per Vendor  
- Downtime per Plant  

---

## Next Steps
- Build data model in Power BI  
- Create DAX measures for key KPIs  
- Design KPI cards for quick insights  
- Build visuals for vendor and plant comparison  
- Add filters for interactivity  

---

## Goal
To create a dashboard that helps management:
- Identify underperforming suppliers  
- Reduce downtime caused by defects  
- Improve overall manufacturing efficiency  
