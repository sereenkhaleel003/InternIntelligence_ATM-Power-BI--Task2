# 📐 Design Notes – ATM Power BI Report

## 🧩 Data Model
- Single dataset: `AggregatedData.csv`
- Columns: transaction counts, transaction amounts, branch names, and dates.
- Relationships: Not needed as data is aggregated.

## 📊 Visuals & Pages
- **Overview Page**: Key KPIs (total transactions, total amount)
- **Branch Performance**: Bar chart showing top-performing branches
- **Time Trends**: Line chart showing monthly trends
- **Geo Map**: Map visual highlighting transaction distribution by branch location

## 🎨 Design Approach
- Clear, minimal design
- Consistent color palette (corporate theme)
- Interactive filters: by branch, date, and transaction type
