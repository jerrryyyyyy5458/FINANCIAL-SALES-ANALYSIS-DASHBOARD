# Financial Sales Analysis Dashboard

An interactive Power BI report for exploring sales performance across products, customer segments, countries, and time. The report is designed to help stakeholders compare revenue and profit patterns and narrow the view with interactive filters.

## Objectives

- Summarize overall sales performance in a clear dashboard.
- Compare sales across countries and customer segments.
- Review product level profitability.
- Explore monthly sales trends over time.
- Make the report easy to filter and use for business discussions.

## Dashboard features

- Total Sales KPI card.
- Sales by country clustered column chart.
- Profit by product clustered bar chart.
- Monthly sales trend line chart.
- Sales by segment donut chart.
- Interactive country and product slicers.

## Key insights

The report layout supports analysis of:

- Which countries contribute the most sales.
- How sales are distributed across segments.
- Which products contribute more or less profit.
- How sales change over the monthly timeline.

No numeric findings are stated here because the report's embedded data has not been reviewed for public sharing. Add verified, non-sensitive findings after confirming the dataset is safe to publish.

## Tools

- Microsoft Power BI Desktop
- Power BI report visuals and slicers

## Repository structure

```text
Financial-Sales-Analysis-Dashboard/
├── README.md
├── .gitignore
└── screenshots/
    ├── README.md
    └── dashboard-overview.png   # Add a sanitized screenshot here
```

## Screenshots

Add sanitized dashboard images to [`screenshots/`](screenshots/). Remove customer names, confidential figures, or other sensitive information before sharing. A full-page overview is a good starting point.

## Data and privacy

The PBIX file is intentionally excluded from Git by default because Power BI files can contain imported data, credentials, or other private information. Before publishing the PBIX, review its data model, Power Query source settings, and report pages; remove private information and credentials. The original PBIX remains outside this repository and has not been changed.

If you publish a sanitized PBIX, place a reviewed copy in this project folder and update `.gitignore` deliberately. GitHub currently rejects individual files over 100 MB; this dashboard's source PBIX is approximately 0.8 MB, but size does not establish that its contents are safe to publish.

## Open the report

After a reviewed PBIX has been added to the repository, open it in Microsoft Power BI Desktop. Data refresh may require configuring an approved public or local data source.

## License

No license has been selected. Add a `LICENSE` file only after deciding how you want others to use this portfolio project.
