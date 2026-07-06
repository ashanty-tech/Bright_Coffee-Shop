# Bright_Coffee-Shop
Bright Coffee Shop Sales Analysis

Case Study 1 · BrightLearn 2026

Six months of transaction data (Jan–Jun 2023, 3 NYC stores, ~149k rows) turned into insights and recommendations for a new CEO focused on growing revenue.

## Key findings

- **Revenue nearly doubled** up 104% from January to June.
- **45.8% of daily revenue lands before 11am**  the store runs on the morning rush.
- **Coffee + Tea are two-thirds of revenue**; Bakery is a distant third.
- **All 3 stores are within 3% of each other** a repeatable model.
- **58.5% of orders are a single item**, and Large drinks earn 22% more per cup  the fastest lever is a bigger basket, not a bigger menu.

## What I did

1. **Cleaned & transformed** the raw CSV in Databricks  — fixed the comma-decimal `unit_price`, computed `total_amount`, built 30-minute time buckets and product size.
2. **Analysed** the clean table in SQL — revenue by product, hour, month, and store.
3. **Visualised** in Excel — pivot tables, charts, and a summary dashboard.
4. **Presented** the findings in a CEO-ready deck.

## Repo contents

| Folder | What's inside |
|---|---|
| `docs/` | Project description & methodology (PDF) |
| `data/` | Raw dataset (CSV) |
| `planning/` | Data flow diagram & Gantt chart (Miro) |
| `sql/` | Analysis queries |
| `excel/` | Processed workbook with pivots & charts |
| `presentation/` | CEO presentation |

## Tools

Databricks •SQL · Microsoft Excel · PowerPoint · Miro
