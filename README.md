# Regional Sales & Target Tracking Dashboard

## Overview

This dashboard tracks sales performance across different regions and evaluates how individual sales executives are performing against their targets. It’s built in Excel and includes automated calculations and visual summaries (likely powered by macros and formulas).

## File Contents

### 1. `DATA`

This is the raw data source and includes:

- `Emp Code`: Unique ID for each salesperson  
- `Sales Executive`: Name of the salesperson  
- `Region`: Their assigned sales region  
- `Day1` to `Day5`: Daily sales figures  
- `Total Sales`: Sum of daily sales  
- `Target`: Sales goal for the period  
- `Target Hit %`: Ratio of sales to target  
- `Away From Target %`: 1 minus the Target Hit %

> Update this sheet regularly as new sales data comes in.

### 2. `DASHBOARD`

A visual summary for quick review. It aggregates and ranks performance, highlights top performers, regional comparisons, and target progress.

> Data in this sheet is likely auto-generated. Avoid editing it manually unless you understand the structure.

## How to Use

1. **Update Data**: Go to the `DATA` sheet and update sales figures.
2. **Review Dashboard**: Switch to the `DASHBOARD` sheet to see updated summaries.
3. **Save as `.xlsm`**: Keep the macro-enabled format to retain all functionality.

## Notes

- Update targets directly in the `Target` column in the `DATA` sheet.
- To add a new employee, insert a new row in the `DATA` sheet with their info.
- Make sure formulas in `Total Sales`, `Target Hit %`, and `Away From Target %` are extended when adding rows.
