# Retail Sales Performance Dashboard

A Power BI retail analytics case study covering **revenue, gross profit, margin, demand, budget achievement, and pricing scenarios**.

**Power BI · DAX · Power Query · Excel · Retail Analytics**

> **Portfolio status:** Documentation in progress. The source PBIX and Excel workbook have been reviewed separately but are **not yet committed to this repository**. Screenshots and a validated model diagram are pending. The README intentionally avoids claiming that missing files are downloadable here.

## Project Overview

An interactive retail report designed to explore performance across products, product lines, retailer countries, and reporting periods. The supplied Power BI file contains **9 report pages**.

## Report Pages

| Page | Analysis |
| --- | --- |
| Summary | Executive overview of retail KPIs and breakdowns |
| Top Revenue | Highest-revenue products and comparisons |
| Bottom Revenue | Lowest-revenue products and comparisons |
| Achievement | Revenue achievement against planned revenue |
| Top Margin | High-margin performance |
| Bottom Margin | Low-margin performance |
| Demand | Quantity and demand patterns |
| What if | Pricing scenario exploration |
| Tooltip Details | Supporting contextual detail |

**Screenshots:** To be added from Power BI Desktop, following the visual presentation style used in the [Finance Performance Dashboard](https://github.com/omaraligomaa/finance-performance-dashboard).

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
