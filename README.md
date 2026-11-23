# Business KPI Dashboard: Customer Churn

**Track:** Data Analytics

**Live dashboard:** https://YOURUSERNAME.github.io/churn-kpi-dashboard/

An interactive dashboard that explains churn, retention, revenue risk and customer segments. Built with plain HTML, CSS and JavaScript (no external libraries).

## Files
- `index.html` : the dashboard (data embedded)
- `customer_churn_sample.csv` : source dataset (15 customers, no missing values)

## KPI definitions
| KPI | Definition |
|---|---|
| Churn rate | Churned customers / customers in view |
| Retention rate | 1 − churn rate |
| Revenue at risk | MonthlyCharges of churned customers (lost MRR); annualised = × 12; also shown as % of total MRR |
| Tenure KPIs | Average TenureMonths overall, and for churned vs retained customers |

## Filters
Contract type, tenure band (0–6, 7–12, 13–24, 25+ months) and payment method. All KPIs, charts and insight text update together.

## Charts
1. Churn by contract type
2. Churn by tenure band
3. Churn by payment method
4. Monthly revenue lost by plan
5. Average support tickets, churned vs retained

Each chart has a written insight beside it. Colours are colourblind-safe (orange = churned, blue = retained, retained bars hatched) and every bar is labelled.

## Key findings
- Overall churn is 47% (7 of 15); retention is 53%.
- All 7 month-to-month customers churned; all 8 one- and two-year customers stayed.
- Every churned customer had 14 months of tenure or less.
- Every customer with 3+ support tickets churned.
- Revenue at risk is $409.93/month (about $4,919/year), 32% of total MRR. No Enterprise customer churned.

## Recommendations
1. Offer month-to-month customers an incentive to move to an annual plan.
2. Add a proactive check-in during months 1–12.
3. Escalate customers after their third support ticket.

## Caveat
The sample has only 15 rows, and contract, tenure and tickets overlap heavily, so their effects cannot be separated. Treat the patterns as directional.
