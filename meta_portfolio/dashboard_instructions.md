# Operator Metrics Dashboard – Instructions

This guide explains how to run the Operator Metrics Dashboard with your own data.

## Steps
1. Ensure you have Python 3.9+ and the required dependencies installed (see `requirements.txt` in the dashboard repository).
2. Copy your job-search data into the `data/` folder. Supported formats include CSV and JSON.
3. Run the ingestion script or Jupyter notebook provided in the repository. This will parse your data, compute KPIs and generate an HTML dashboard.
4. Open the generated HTML file in your browser to explore metrics such as interview conversion rate, offer rate, and time to decision.
5. Customize `config_example.json` in the dashboard repository to define your own KPI thresholds or add new metrics.
6. Review the `action_checklist.md` to ensure you act on insights gleaned from the dashboard.

## Sample Data
A small sample dataset (`sample_data.csv`) is provided for testing. Replace it with your own data when ready.
