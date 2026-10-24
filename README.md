# ChainGuard AI — Supply Chain Digital Twin

A Streamlit prototype for supply-chain visibility, supplier risk, shipment delays,
disruption simulation, recovery planning, evidence review, and audit reporting.

## Requirements
- Python 3.10 or newer
- Internet connection for installing dependencies

## Run locally

```bash
python -m venv .venv
```

Activate the environment:

**Windows**
```powershell
.venv\Scripts\activate
```

**macOS / Linux**
```bash
source .venv/bin/activate
```

Install dependencies and launch:

```bash
pip install -r requirements.txt
streamlit run streamlit_app.py
```

## Deploy to Streamlit Community Cloud
1. Create a GitHub repository and upload the contents of this folder.
2. Visit https://share.streamlit.io/ and connect your GitHub account.
3. Select the repository and set the main file path to `streamlit_app.py`.
4. Deploy.

## Dashboard features
- Overview with seeded shipment risk, priority incidents, and risk distribution charts.
- Supply-chain dependency graph with upstream/downstream views and outage simulation.
- Shipment intelligence, anomaly checks, incident cross-checks, and evidence records.
- Recovery planning, scenario simulation, CSV reports, and a hash-linked audit trail.
- Search, notifications, responsive navigation, and a light/dark theme control.

The dashboard is embedded in `streamlit_app.py`, so Streamlit Community Cloud only
needs the app file and `requirements.txt`. All records are simulated and seeded;
actions and audit history are held in browser memory and are not persisted between
sessions.

## Important
This is a demonstration prototype. All included data is synthetic. Risk scores,
scenario costs, and recommendations are illustrative, not live intelligence.
It does not connect to real suppliers, logistics providers, or ERP systems.
