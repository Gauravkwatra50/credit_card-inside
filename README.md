# Credit Card Insights — Power BI Dashboard

An interactive Power BI report analyzing credit card transactions and customer demographics across two pages.

## Pages

**1. CC Transaction** — Revenue, transaction amount, interest, and volume KPIs with breakdowns by card category, expense type, chip usage, education, and job. Includes quarterly trends and client distribution treemaps.

**2. Customer Overview** — Customer-focused KPIs (revenue, income, satisfaction score) with demographic breakdowns by age, gender, marital status, education, job, state, and income group.

Both pages include a **Week Number slicer** for time-based filtering.

## Data Tables

- **`credit_card`** — Transaction data: revenue, transaction amount/volume, interest, card category, expense type, quarter, week
- **`customer`** — Demographics: age group, income, gender, job, education, marital status, satisfaction score, state

## Getting Started

1. Open `cc_insit.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Update the data source connection if needed
3. Refresh the data model
4. Use the Week Number slicer to filter by time period

## Built With
Power BI Desktop 2026.03 · DAX · Power Query
