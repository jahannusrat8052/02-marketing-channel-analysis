# Marketing Channel Performance: Revenue vs Spend
**Portfolio demo | Synthetic Bangladesh retail data**

## Business question
How do Facebook Ads, Google Ads, Organic Search and Direct traffic differ in completed-order revenue and recorded channel spend?

## Run
```bash
python -m pip install -r requirements.txt
python src/analyze.py
```

## Verified results
- Total tracked channel spend: **BDT 138,500** over July–September 2026.
- See `outputs/channel_summary.csv` for each channel's completed-order revenue, order count and spend.
- Channel revenue divided by recorded spend is explicitly **not actual ROAS** without conversion attribution and matching definitions.

## Recommendation
Audit attribution, conversion definitions, gross margin and campaign-level costs before recommending budget shifts. Channel association alone does not prove causal performance.

## Tools
Python, Matplotlib, SQL aggregates, marketing KPI interpretation. CSV files can be imported into Power BI as a separate channel analysis page.

## Disclosure
Synthetic data; initially prepared as a reproducible portfolio demonstration. Do not claim paid-campaign optimization or client ROAS outcomes.
