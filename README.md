# What-If Tool
Useful notebooks on Google's What-If Tool (WIT)(along with samples to deploy/predict via GCP AI Platform)

## Useful Bits

- With the What-If Tool, we can easily slice the model result via certain features (e.g. race) and examine if we are approving more loan applications by certain race (e.g. white vs blacks). 
- If we can identify these, we can use cool fairness optimization strategies like **Demographic Parity**, Equal Opportunity, Equal Accuracy, Group Thresholds to make sure each race gets equal number of loan approvals.
- Another useful tool is the **Nearest Counterfactual**. You can select a data point and ask WIT to find another point that is **very similar** to that point **but has a different prediction outcome**. This will give you more idea on what features lead to certain prediction outcomes.