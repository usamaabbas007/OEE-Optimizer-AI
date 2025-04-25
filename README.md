# OEE-Optimizer-AI
**AI-Powered Toolkit to Track, Analyze, and Improve Overall Equipment Effectiveness (OEE) in Dairy and Food Manufacturing**
---
## Overview
OEE-Optimizer-AI is a smart manufacturing analytics system built to optimize plant performance by analyzing **Availability, Performance, and Quality** across departments and shifts. Designed for food processing environments (like dairy plants), it brings together real-time tracking, AI-driven root cause analysis, anomaly detection, and prescriptive insights to reduce downtime, shrink, and inefficiency.
---
## Features
- **Real-Time OEE Dashboard:** Visualize shift-level and department-level metrics live
- **Root Cause AI Engine:** Identify bottlenecks or defects affecting performance
- **Shrink & Waste Forecasting:** Predict material losses before they happen
- **Anomaly Detection:** Get alerted when something doesn’t look right
- **Prescriptive Recommendations:** Actionable insights to improve efficiency
---
## Departments Modeled
- Blowmold (e.g., 1G Jug manufacturing)
- Culture (e.g., Greek Yogurt)
- UHT (e.g., UHT Milk)
- Fluid (e.g., Whole Milk)
- Filler (e.g., Carton Packaging)
- Pasteurizer (e.g., Raw Milk Processing)
---
## Sample Dataset
Realistic dummy data simulates:
- 7 days of production  
- 2 shifts per day (Day/Night, 12 hrs each)  
- Metrics: Downtime (min), Performance (%), Quality (%), OEE (%)
**Preview:**
| Date       | Shift | Department  | Line   | Product         | Downtime (min) | Perf. (%) | Qual. (%) | OEE (%) |
|------------|-------|-------------|--------|------------------|----------------|-----------|-----------|---------|
| 2025-04-18 | Day   | Fluid       | FL-01  | Whole Milk       | 25             | 89.3      | 96.7      | 80.7    |
| 2025-04-18 | Night | UHT         | UHT-01 | UHT Milk         | 40             | 85.5      | 94.8      | 74.2    |
File path: `data/sample_dataset.csv`
---
## Tech Stack
| Layer        | Tech                     |
|--------------|--------------------------|
| Frontend     | React.js, Chart.js       |
| Backend      | Python, Flask/FastAPI    |
| ML/Forecasts | scikit-learn, pandas     |
| DB           | PostgreSQL or SQLite     |
| Deployment   | Docker, Docker Compose   |
---
