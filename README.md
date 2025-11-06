# Finance KPI Dashboard – YoY Performance & Business Insight

This Power BI dashboard evaluates revenue evolution over time using:
- Year-over-Year comparison (YoY)
- Variance and Variance %
- Trend line visualization on a multi-year horizon

## Key Business Insights
- Annual revenue growth is stable between **+4% and +6% YoY**
- No structural decline or negative break in trend
- Sales trajectory shows **healthy and predictable performance**

## Data Modeling Approach
- Star schema with a dedicated Calendar (Date) table
- One-to-many relationship (Calendar → Sales)
- Time Intelligence measures built using `CALCULATE` + `DATEADD`
- All KPIs stored in a dedicated **Measures table** (clean modeling practice)

## DAX Measures Included
