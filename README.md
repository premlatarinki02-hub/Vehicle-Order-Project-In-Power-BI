# DAX Formulas Practice: Vehicle Sales Dashboard (Power BI)

A Power BI project for learning DAX and building sales dashboards. It uses a classic cars / vehicle orders dataset.

**File:** `daxformulas.pbix` (~12 MB, 30 report pages)
**Theme:** Dark (`ReportThemeDark`) on the Fluent 2 base theme

## Data Model

Tables:
- `Vehicle_order`: main orders table (product line, deal size, country/state/city, quantity, price, order date, sales amount)
- `Classic Cars Dataset`: source dataset
- `Combined Dataset`
- `City_State_Mapping`: location mapping; the DAX measures are stored here
- `Calendar`: date table with a Year / Quarter / Month / Day hierarchy
- `Summary Table`, `Summar Table 2`, `Add New Colunm`: derived and summary tables
- Territory hierarchy: Country > State > City

## DAX Concepts Covered

- **Basic aggregates:** Revenue, Quantity Sold, Total Orders
- **Deal size segmentation:** Small, Medium and Large Deal Size Revenue; Classic Cars revenue in Medium deals
- **Contribution analysis:** All Revenue, Revenue Contribution %
- **Time intelligence:** TOTALYTD, TOTALMTD, TOTALQTD for revenue and quantity
- **Rolling windows:** Revenue in Last 3 Months, Revenue in Last 10 Days
- **Date-range filtering:** Revenue Between Dates
- **Previous period comparison:** Previous Month Revenue

## Report Pages

- **Executive Dashboard:** KPI cards, pie chart, gauge, scatter, 100% stacked column, combo chart, slicers
- **Customer Dashboard:** treemap, map, sunburst, ribbon chart, packed bubble chart, country slicer
- **Practice pages:** one page per visual type
  - Bar and column
  - 100% stacked
  - Combo
  - Pie and donut
  - Sunburst
  - Ribbon
  - Gauge
  - Waterfall
  - Treemap
  - Map
  - Scatter
  - Bubble
- **DAX test pages:** matrices showing the YTD/MTD/QTD, rolling-window and date-range measures

## Custom Visuals Used

Sunburst, Activity Gauge, Packed Bubble Chart. The file also bundles KPI Tree and Full Clustered Stacked Bar Chart.

