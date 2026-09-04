# Pharmacy Performance Dashboard

## Objective

Analyze fictional pharmacy sales trends, product mix, revenue contribution, branded versus generic performance, and operational stock priorities using reproducible data-analysis methods.

## Dataset

This project uses the supplied fictional pharmacy sales dataset containing 10 transactions from June 1 to June 5, 2026.

The dataset contains:

* TransactionID
* Date
* DrugName
* Category
* UnitsSold
* UnitPriceINR
* TotalRevenueINR
* StoreLocation
* GenericStatus

## Data Validation

The analysis validates:

* Required columns
* Data types
* Missing values
* Duplicate transaction IDs
* Date values
* Units sold
* Unit prices
* Total revenue
* Revenue calculation consistency
* Category values
* Branded/generic classification

Revenue was checked using:

`UnitsSold × UnitPriceINR = TotalRevenueINR`

## Key Performance Indicators

The dashboard calculates:

* Total transactions
* Total units sold
* Total revenue
* Average transaction revenue
* Average selling price
* Daily revenue
* Product revenue contribution
* Category revenue contribution
* Branded versus generic revenue
* Branded versus generic units sold
* Product-level sales volume for inventory monitoring

## Key Findings

The supplied sample contains 10 transactions and 1,165 units sold, generating total revenue of ₹54,260.

Vitamin D3 60k is the highest-revenue product at ₹15,750.

Cetirizine 10mg has the highest unit sales at 200 units.

Branded products generate more revenue in this sample, while generic products account for more units sold.

The results are descriptive operational findings and do not represent medical advice or clinical conclusions.

## Inventory Opportunities

High-volume products can be considered for closer stock monitoring.

Based on units sold, Cetirizine 10mg, Vitamin D3 60k, and Paracetamol 650mg are useful products to monitor.

However, the dataset does not contain stock-on-hand or stockout information. Therefore, these are sales-volume signals rather than confirmed stock shortages.

## Margin Limitation

The supplied dataset does not contain product cost or purchase-cost information.

Therefore, gross margin and margin percentage cannot be calculated reliably.

No cost values were invented or estimated.

If cost data becomes available:

`Gross Margin = Revenue - Cost`

`Margin % = (Gross Margin / Revenue) × 100`

## Growth Limitation

The dataset covers only five days and contains only 10 transactions.

Daily revenue is shown in the dashboard, but the short observation period is not sufficient to establish a long-term sales trend.

## Limitations

1. The dataset is small.
2. The observation period is only five days.
3. Cost data is unavailable, preventing margin analysis.
4. Stock-on-hand and stockout data are unavailable.
5. The dataset is fictional and should not be treated as representative of real pharmacy operations.

## Files

* `pharmacy_sales_cleaned.csv` — cleaned and validated pharmacy sales data
* `pharmacy_dashboard.ipynb` — reproducible analysis and dashboard charts
* `pharmacy_performance_summary.md` — one-page performance summary
* `README.md` — project documentation

## Conclusion

The analysis identifies revenue leaders, high-volume products, category performance, and differences between branded and generic products.

The main data limitation is the absence of cost and inventory-level information. Collecting purchase cost, stock-on-hand, stockout, and longer-period sales data would allow stronger margin and inventory decisions in a future analysis.

This project uses fictional operational data for educational purposes and does not make medical or clinical claims.

