# IT Asset Performance Dashboard

A small IT analytics project that evaluates server health using CPU, memory, disk usage, and uptime. It computes a HealthScore to rank assets and highlight which servers need maintenance priority.

## What it does
- Loads IT asset metrics from a CSV
- Computes a weighted HealthScore
- Ranks servers needing urgent attention
- Prints summary insights

## Run
```bash
pip install pandas
python asset_dashboard.py
