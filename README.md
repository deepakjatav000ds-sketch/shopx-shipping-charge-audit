# shopx-shipping-charge-audit

Objective: Verify courier company charges against ShopX’s internal data (weights & zones).

Problem: Courier costs are very high (~₹2 Cr/month). ShopX suspects overcharging.

Solution:

Calculate expected charges using ShopX’s internal order data.

Compare with courier invoices.

Generate order-level mismatch report + summary.

🛠️ Tech Stack

Python (pandas, numpy, openpyxl)

Jupyter Notebook

Excel

Dataset (Sample)

ShopX Orders

ShopX Product Weights

ShopX Pincode Zones

Courier Invoice

Courier Rate Card

📊 Outputs

Order-Level Report – with actual vs expected charges

Summary Table – Correctly charged / Overcharged / Undercharged
