# 🚗 Dynamic Pricing for Urban Parking Lots  
*Capstone Project – Summer Analytics 2025*  
Hosted by Consulting & Analytics Club × Pathway

---

## 📌 Overview

Urban parking spaces are a scarce resource. Static pricing causes inefficiencies — overcrowding or underutilization — depending on time and demand.  
This project develops a **real-time, demand-driven pricing system** for 14 urban parking lots using only Python, Pandas, NumPy, and Pathway.

We implemented:
- **Baseline Linear Pricing**
- **Demand-Based Dynamic Pricing**
- **Competitive Pricing using Geo-Location**
- **Real-time simulation using Pathway**
- **Live price visualizations using Bokeh**

---

## 🛠️ Tech Stack Used

| Component     | Tool/Library       |
|---------------|--------------------|
| Language      | Python 3           |
| Data Handling | Pandas, NumPy      |
| Streaming     | [Pathway](https://pathway.com/) |
| Visualization | Bokeh              |
| Distance Calc | Haversine Formula  |
| Notebook      | Google Colab       |
| Diagram Tool  | Mermaid Live Editor|

---

## 🗺️ Architecture Diagram

```mermaid
flowchart TD
    A[CSV Data Input (dataset.csv)] --> B[Preprocessing & Feature Extraction]
    B --> C[Model 1: Linear Pricing]
    B --> D[Model 2: Demand-Based Pricing]
    B --> E[Model 3: Competitive Adjustment]
    C & D & E --> F[Real-Time Stream Processing with Pathway]
    F --> G[Live Visualization via Bokeh]
    G --> H[Dynamic Price Output & Suggestions]
