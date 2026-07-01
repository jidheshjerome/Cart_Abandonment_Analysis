# Cart_Abandonment_Analysis
Cart Abandonment Analysis A data analyst project examining 5,000 checkout sessions to identify the key reasons behind cart abandonment and recommend measures to reduce it.

# Overview
This project analyses customer cart abandonment behaviour across device types, browsers, operating systems, cart sizes, cart values, coupon usage, and returning customer patterns. The goal is to uncover what drives the 70% abandonment rate and provide data-backed recommendations to improve conversion.

Data Cleaning (Python): Loaded and explored the dataset with pandas, created a new Abandoned column from the abandonment reason field, engineered cart_size and CartAmount category columns, and connected the cleaned dataset to MS SQL Server for structured analysis.

Analysis (SQL): Queried the dataset across eight dimensions — overall abandonment, device type, browser, operating system, cart size, cart value, returning customer status, and coupon usage — to identify where and why customers drop off.

Visualization (Tableau): Built an interactive dashboard to present abandonment trends across all key segments.

# Key Findings

70% of sessions ended in cart abandonment

High Shipping Cost is the #1 reason, driving 36% of all abandonments

Low-value carts abandon at 84.6% — most lost carts are small purchases where shipping feels disproportionate

2–3 item carts have the highest abandonment rate (44.2%) among all cart sizes

Customers with a coupon abandon at nearly half the rate of those without one

New customers abandon significantly more than returning customers (60.65% vs 39.35%)

Device, browser, and OS abandonment rates are nearly uniform — no platform-specific issues detected
