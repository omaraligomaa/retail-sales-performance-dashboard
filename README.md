# Retail Sales Performance Dashboard

A Power BI retail analytics case study covering **revenue, gross profit, margin, demand, budget achievement, and pricing scenarios**.

**Power BI · DAX · Power Query · Excel · Retail Analytics**

> **Portfolio status:** Documentation in progress. The source PBIX and Excel workbook should be checked separately for availability in this repository. A validated model diagram is pending. Five screenshots have been added. The README intentionally avoids claiming that missing files are downloadable here.

## Project Overview

An interactive retail report designed to explore performance across products, product lines, retailer countries, and reporting periods. The supplied Power BI file contains **9 report pages**.

## Report Pages

### Retail Summary
Executive overview of revenue, cost, gross profit, gross margin, and product/geographic performance.

![Retail Summary](images/retail-summary.png)

### Achievement
Actual versus planned revenue and achievement by product line, product, and country.

![Achievement](images/achievement.png)

### Top Margin
Revenue and gross margin across product lines, product types, and products.

![Top Margin](images/top-margin.png)

### Demand
Demand percentage and revenue across product lines and selected products.

![Demand](images/demand.png)

### What If Analysis
Price increase scenario and modeled impact on revenue and profit.

![What If Analysis](images/what-if-analysis.png)

**Other report pages:** Top Revenue, Bottom Revenue, Bottom Margin, and Tooltip Details (screenshots not yet provided).

## Business Questions

- Which products and product lines contribute most and least to revenue?
- How does actual revenue compare with planned revenue?
- How do gross profit and margins vary by product?
- How does demand change across reporting periods?
- How might a pricing adjustment affect the modeled outcome?

## Source Dataset

The supplied Excel workbook contains **84,672 data rows** and **14 columns** in one worksheet.

| Field | Field | Field |
| --- | --- | --- |
| Year | Product line | Product type |
| Product | Order method type | Retailer country |
| Revenue | Planned revenue | Product cost |
| Quantity | Unit cost | Unit price |
| Gross profit | Unit sale price | |

The source dataset is not currently downloadable from this repository. Check dataset redistribution rights before publishing it.

## Report & Model Verification

The nine page names and the presence of visual elements were verified from the supplied PBIX package. A full model relationship audit, DAX logic validation, visual rendering check, and data-refresh test in Power BI Desktop are **still pending**.

The report package includes custom visuals. Opening it in Power BI Desktop is recommended before distributing or modifying the PBIX.

## Measures & Documentation

See [Measure Inventory](docs/measures.md) and [Report Pages](docs/report-pages.md). These documents describe the report; their measure logic must be checked against the Power BI model before being presented as a complete verified DAX reference.

## Tools & Technologies

- Power BI Desktop
- DAX
- Power Query
- Excel
- Retail performance analytics

## Repository Structure — Target

```text
retail-sales-performance-dashboard/
├── README.md
├── dashboard/
│   └── Retail Dashboard.pbix             # Pending upload
├── data/
│   └── WA_Retail-SalesMarketing_-ProfitCost.xlsx  # Pending rights review/upload
├── images/
│   └── *.png                             # Pending screenshots
└── docs/
    ├── report-pages.md
    └── measures.md
```

## Next Steps

1. Capture full-size screenshots of all report pages and the data model.
2. Validate measures, relationships, and refresh behavior in Power BI Desktop.
3. Add the PBIX and only data permitted for redistribution.
4. Replace this status note with validated report screenshots and model documentation.

## Author

**Omar Ali**

[LinkedIn](https://www.linkedin.com/in/eng-omargomaa) · [GitHub](https://github.com/omaraligomaa)
