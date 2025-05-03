# Quantifying Sales Uplift With Causal Impact Analysis

This project applies **Causal Impact Analysis** to estimate the **incremental effect of a marketing intervention** (such as a campaign or promotion) on sales performance using time series data.

---

## Overview

This Jupyter Notebook demonstrates:

-  **Data Preparation**: Loading and preprocessing time series data.
-  **Intervention Period Definition**: Specifying pre- and post-intervention timeframes.
-  **Causal Modeling**: Using Google's `CausalImpact` model to estimate counterfactual sales (i.e., what would have occurred without the intervention).
-  **Impact Estimation**: Calculating the difference between actual and predicted values.
-  **Result Interpretation**: Visual output and statistical summary of the intervention's effect.

---

##  Tech Stack

- Python 3.x  
- `pandas`, `numpy`, `matplotlib`  
- `causalimpact` (Python wrapper)

---
