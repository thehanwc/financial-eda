# Data Overview

---

## Dataset Description

This project uses the **Power BI Financial Sample dataset**, a publicly available dataset designed to simulate real-world financial and sales reporting scenarios. The dataset captures transactional-level performance across multiple business dimensions, making it suitable for **exploratory data analysis (EDA)** and **business intelligence (BI)** applications.

The data reflects common analytical challenges found in industry settings, including mixed data types, monetary fields requiring normalization, and multiple categorical dimensions used for performance segmentation.

---

## Data Structure

The dataset consists of the following key feature groups:

### Categorical Dimensions
- **Segment** – Customer or market segment classification.
- **Country** – Geographic market identifier.
- **Product** – Product category or SKU grouping.
- **Discount Band** – Pricing and promotional tier applied to transactions.
- **Month Name / Year** – Temporal descriptors for time-based analysis.

### Numerical Measures
- **Units Sold** – Quantity of products sold.
- **Manufacturing Price** – Unit production cost.
- **Sale Price** – Unit selling price.
- **Gross Sales** – Total revenue before discounts.
- **Discounts** – Monetary value of discounts applied.
- **Sales** – Net revenue after discounts.
- **COGS** – Cost of goods sold.
- **Profit** – Net profit after costs.

---

## Data Characteristics

- Monetary columns are stored as formatted strings and require transformation into numerical values.
- Placeholder symbols are present in certain fields and must be handled during preprocessing.
- Temporal information is distributed across multiple columns, requiring alignment for trend analysis.
- The dataset size allows for comprehensive EDA without computational constraints.

---

## Analytical Assumptions

The following assumptions are applied throughout the project:

- Monetary values are accurate and internally consistent after cleaning.
- Each row represents a single sales or financial record.
- Profitability is evaluated at both aggregate and segmented levels.
- No external enrichment or augmentation of the dataset is performed.

---

## Intended Use

This dataset is used exclusively for:
- Exploratory data analysis
- Data cleaning and validation
- Business performance evaluation
- Dashboard-driven insight communication

The dataset is **not modified beyond cleaning and normalization**, ensuring transparency and reproducibility of analytical results.