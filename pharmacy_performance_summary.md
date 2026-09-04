# Pharmacy Performance Summary

## Operational Question

Which products, categories, and product types are contributing most to pharmacy sales, and where should operational attention be focused?

## Dataset Scope

This analysis uses 10 fictional pharmacy sales transactions dated from 2026-06-01 to 2026-06-05.

The dataset contains transaction ID, date, drug name, category, units sold, unit price, total revenue, store location, and branded/generic status.

The data is fictional operational training data and is not used for medical decision-making.

## Key Performance Metrics

* **Total transactions:** 10
* **Total units sold:** 1,165
* **Total revenue:** ₹54,260
* **Average revenue per transaction:** ₹5,426
* **Average unit selling price:** approximately ₹46.58

## Product Performance

The highest-revenue products are:

1. **Vitamin D3 60k** — ₹15,750
2. **Atorvastatin 10mg** — ₹8,800
3. **Azithromycin 500mg** — ₹7,800

Vitamin D3 60k contributes the largest share of revenue among the supplied transactions.

The highest unit volume is from:

* Cetirizine 10mg — 200 units
* Vitamin D3 60k — 175 units
* Paracetamol 650mg — 150 units

This shows that high unit volume does not always correspond to the highest revenue.

## Category Performance

The highest-revenue categories in the supplied sample are:

* Supplement — ₹15,750
* Cardiovascular — ₹12,100
* Antibiotic — ₹11,625
* Analgesic — ₹5,110

Category performance should be interpreted as descriptive sales performance only and should not be treated as evidence of clinical demand or treatment effectiveness.

## Branded vs Generic Performance

### Branded products

* Transactions: 4
* Units sold: 360
* Revenue: ₹36,175
* Average revenue per transaction: ₹9,043.75

### Generic products

* Transactions: 6
* Units sold: 805
* Revenue: ₹18,085
* Average revenue per transaction: approximately ₹3,014.17

Generic products account for more units sold, while branded products account for more revenue in this sample.

## Growth

The dataset covers only five days, so growth should be interpreted cautiously.

Daily revenue is compared in the dashboard to identify changes across the supplied observation period. The short time period is not sufficient to establish a long-term sales trend.

## Inventory Opportunities

Units sold can be used as an operational signal for inventory attention.

Products with relatively high unit sales, particularly Cetirizine 10mg, Vitamin D3 60k, and Paracetamol 650mg, may warrant closer stock monitoring.

This is an operational prioritization suggestion based on sales volume, not a clinical recommendation.

## Margin Limitation

The supplied dataset does not contain a cost field.

Therefore, **gross margin and margin percentage cannot be calculated reliably**.

No cost values were invented or estimated. Future analysis should include unit cost or purchase cost so that revenue, gross margin, and margin percentage can be calculated accurately.

## Data Quality

The dataset was checked for:

* Missing values
* Duplicate transaction IDs
* Date format
* Numeric units sold
* Numeric unit price
* Revenue consistency
* Category values
* Branded/generic classification

The supplied revenue values can also be checked against:

`UnitsSold × UnitPriceINR`

No clinical claims are made from the sales data.

## Limitations

1. The dataset contains only 10 transactions over five days.
2. Cost information is not supplied, so margin cannot be calculated.
3. The sample is fictional and should not be treated as representative of real pharmacy operations.
4. Short-term sales patterns may not represent long-term demand.
5. Inventory quantities or stock-on-hand data are not supplied.

## Recommended Next Action

Use the highest-volume products as an initial stock-monitoring priority and collect purchase-cost and stock-on-hand data for the next analysis cycle.

## Follow-up Measurement

Track weekly units sold, revenue, stock-on-hand, stockouts, and gross margin by product for at least four to eight weeks to determine whether the observed patterns persist.

