# Global Superstore Analysis

Data cleaning, reduction, transformation and statistical analysis of a global retail dataset using Microsoft Excel and IBM SPSS Statistics.

**Course:** IMC501 Information Analytics, Universiti Teknologi MARA (UiTM)
**Type:** Group project (3 members)
**My role:** Data cleaning in Excel and SPSS correlation analysis

## Dataset
- Global Superstore Orders (`global_superstore_2016.xlsx`), sourced from Kaggle
- 5,000 records and 24 attributes covering segment, sales, profit, shipping cost, order priority, discount, product name and ship mode.

## What was done

**1. Data cleaning (Excel)**
- Standardised Order Date and Ship Date to one format (DD-MMM-YYYY).
- Handled missing Postal Code values.
- Removed duplicate Order ID records.

**2. Data reduction (Excel)**
- Removed unnecessary columns (Row ID, Customer Name, Postal Code).
- Aggregated Sales and Profit by Category and Sub-Category using pivot tables.
- Filtered the data to 2015-2016.

**3. Data transformation (Excel)**
- Converted Segment and Order Priority to numeric codes using a mapping table and VLOOKUP.
- Rounded Sales and Profit.

**4. Analysis (SPSS)**
- Spearman correlation between Quantity and Discount: rs = -0.022, p = 0.128 (very weak, not statistically significant).
- Spearman correlation between Shipping Cost and Order Priority: rs = 0.136, p < 0.01 (weak positive, statistically significant).

**5. Visualisation (SPSS)**
- Bar charts for Ship Mode, Segment, Category, Sub-Category and Top 10 Product Names.

## Key observations
- Standard Class is the most common ship mode.
- The Consumer segment is the largest customer group.
- Office Supplies is the most frequent product category.

## Limitations
- Charts show frequency counts only; no profit-based visualisation was produced.
- Duplicates were removed by Order ID only, which may remove valid line items if an order contains several products.

## Repository contents
| Folder | Description |
|---|---|
| `data/` | Original and cleaned Excel files |
| `spss/` | SPSS data file (.sav) and output |
| `report/` | Full project report (PDF) |
| `images/` | Chart and output screenshots |

## Tools
Microsoft Excel (pivot tables, VLOOKUP, filtering), IBM SPSS Statistics

## Notes
This project was completed for academic purposes. The dataset belongs to its original source; please refer to the Kaggle page for its license.
