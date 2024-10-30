**GAP Document : Automated Supplier Performance Scoring System**

**Requirement :**

The client needs an automated system to score suppliers in real-time based on metrics like on-time delivery, quality issues, and cost variability (Projected Cost - Actual Cost)  and to generate alerts for underperformance with performance reports.
Solution:
Custom Scoring System: Develop a report to calculate supplier scores using delivery, quality, and cost data.
Alerts: Create an ABAP program to trigger alerts when scores fall below thresholds.

**For e.g.,** : 
On-Time Delivery:  Deliver 95 out of 100 orders on time; alert if below 90.
Quality Issues:  No more than 20 out of 1,000 units should be defective; alert if above 30.
Dashboard: Build a Fiori app for real-time performance tracking and trends.
Configurable Thresholds: Set custom thresholds for each supplier’s performance metrics.

**Benefits of Customization:**

Efficiency: Automates supplier evaluation, saving time and reducing mistakes.
Proactive Management: Alerts help you take quick action when suppliers underperform.
Better Insights: Performance trends make it easier to make informed decisions and improve supplier negotiations.


At which stage should the GAP requirement for the 'Automated Supplier Performance Scoring System' be addressed?
This system cannot be implemented at earlier stages, like Purchase Requisition (PR) creation or Purchase Order (PO) creation.
Let's explore why it is best suited after the PO and Goods Receipt (GR) stages:

**1. Purchase Requisition (PR) Stage:**

PR creation is too early in the process to evaluate supplier performance since the supplier has not yet been engaged.

**2. Purchase Order (PO) Creation Stage:**

While the PO stage defines expectations, it does not provide the actual data needed for performance scoring. We need real transactions to assess how well the supplier meets these expectations.

**3. Post-Goods Receipt (GR) and Invoice Verification:**

 This stage provides actual performance data, which is essential for calculating accurate supplier scores. Only after the supplier has completed their part (delivery, quality, pricing) can we evaluate their performance.


Post-Goods Receipt is the right stage, since we have real data on how well the supplier performed against expectations. This is where the Automated Supplier Performance Scoring System can be effectively implemented to reflect true supplier performance.





