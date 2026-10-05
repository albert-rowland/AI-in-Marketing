# Metric Definitions

All rows in past-campaigns.csv contain synthetic data for a fictional brand. All spending figures use USD. Leads count completed email sign-ups. Orders count paid Discovery Box purchases in the training dataset. A lead and an order measure different outcomes.

CTR = clicks / impressions × 100.
Lead conversion = leads / landing_visits × 100.
CPL = spend_usd / leads.
Cost per order = spend_usd / orders.

Use the stated denominator for each metric. Report an undefined value when a denominator equals zero. Attribute orders consistently before comparing cost per order. These rows lack randomized assignment and a common campaign objective, so they support a test hypothesis rather than a causal finding. Revenue, profit, and ROAS require additional data.
