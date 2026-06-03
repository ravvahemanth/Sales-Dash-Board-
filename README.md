# 🍫 Chocolate Sales Dashboard — Power BI

A comprehensive sales analytics dashboard built in Power BI for a chocolate products company. It provides an at-a-glance view of key business metrics across products, salespersons, geographies, and time periods.

---

## 📊 Dashboard Overview

### KPI Cards (Top Bar)
| Metric | Value |
|---|---|
| Total Boxes | 5M |
| Shipment Count | 15K |
| Total Profit | $49M |
| Profit % | 57.6% |
| Total Amount | $85M |

> Date range filter: **01-01-2023 to 22-05-2024**

---

## � Visuals & Components

### Amount — CY vs. PY
- Line chart comparing current year vs. previous year sales amount
- Time range: Jan 2024 – Jan 2025

### Boxes — CY vs. PY
- Line chart comparing current year vs. previous year box shipments
- Time range: Jan 2023 – Jul 2025

### Shipment Distribution
- Bar chart showing shipment frequency distribution
- Range: 1 to 1,000 shipments per bin, peak around 380

### Amount by Geo
- Donut chart breaking down sales by country:
  - India: 29.05% (~$25M)
  - Australia: 20.74% (~$18M)
  - New Zealand: 20.90% (~$18M)
  - USA: ~$13M
  - UK: 7.28% (~$6M)
  - Canada: 7.03% (~$6M)

### Top 6 Salespersons
| Salesperson | Total Amount | Total Boxes | Profit % |
|---|---|---|---|
| Suman | $5.5M | 399.7K | 58.9% |
| Ponnan | $7.0M | 436.1K | 58.0% |
| Dinanath | $4.6M | 286.8K | 57.6% |
| Subbarao | $5.0M | 313.6K | 57.1% |
| Duran | $5.6M | 345.9K | 56.8% |
| John | $5.0M | 315.1K | 56.3% |

### Top 6 Products (by Revenue)
| Product | Revenue |
|---|---|
| Organic Choco | $7M |
| Caramel... | $6M |
| Smooth... | $5M |
| 99% Dark... | $5M |
| Almond... | $5M |
| Rasp... | $4M |

### Our Products Table
Full product breakdown with Total Amount and Profit %:

| Product | Total Amount | Profit % |
|---|---|---|
| 85% Dark Bars | 1.6M | -36.7% |
| Baker's Choco Chips | 1.4M | -1.5% |
| After Nines | 0.8M | -0.1% |
| 50% Dark Bites | 0.6M | 32.6% |
| Drinking Coco | 1.0M | 35.1% |
| 99% Dark & Pure | 1.9M | 36.9% |
| Eclairs | 1.4M | 37.3% |
| Spicy Special Slims | 0.9M | 44.6% |
| Organic Choco Syrup | 2.9M | 58.8% |
| Caramel Stuffed Bars | 2.4M | 66.6% |
| Manuka Honey Choco | 1.3M | 68.0% |
| Smooth Silky Salty | 2.1M | 69.1% |
| White Choc | 1.3M | 73.5% |

---

## 🛠️ Tools Used

- **Power BI Desktop** — report building and data modelling
- **DAX** — calculated measures (Profit %, CY vs. PY comparisons)
- **Data Source** — chocolate sales transactional data

---

## � Files

| File | Description |
|---|---|
| `Sales_DashBoard.pbix` | Main Power BI report file |
| `powerbi-demo-1.pbix` | Demo/backup version |
| `*.png` | Dashboard screenshots and visual exports |

---



### Output 


<img width="1292" height="725" alt="image" src="https://github.com/user-attachments/assets/f53a1309-710a-47cd-a9d5-5da686ac5334" />


## 🚀 How to Open

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Open `Sales_DashBoard.pbix`
3. Refresh the data source if prompted
