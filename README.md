# ML-Cash-Unpaid-Thresholds
Script to help with the decision making of new thresholds for the ML Cash Unpaid model of the Fraud team.

## Script list
1. **allowed_thresholds.ipynb** : computes metrics at country level for score >= X. It includes precision in GTV of each threshold and the % of blocked customers.
2. **Score Drift.ipynb** : compares the weekly score distribution of the model, to monitor potential changes of the score generation.
3. **V1 vs V2 ML Cash model.ipynb** : compares two version of the ML model, one of which needs to be in shadow mode. 
