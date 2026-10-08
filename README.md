# wind-turbine-alayser
# WT Sentinel

### AI-Powered Cyberattack Detection for Wind Turbine SCADA

WT Sentinel is an AI-based cybersecurity system designed to **detect and classify cyberattacks in wind turbine SCADA systems**.

## Features

-  SCADA attack detection
- ML/DL-based anomaly detection
- Multiclass attack classification
- Attack source analysis
- Risk assessment
- Automated incident-response playbook generation
- Interactive Streamlit dashboard

## Models

- Random Forest
- MLP
- 1D-CNN
- LSTM
- GRU
- CNN-LSTM
- Autoencoder *(planned)*

## Dataset

Initially uses the **HAI Security Dataset** for SCADA attack detection, with additional labelled datasets being explored for multiclass classification such as **FDI, DoS, DDoS and MitM**.

## Tech Stack

`Python` · `TensorFlow` · `Scikit-learn` · `Pandas` · `Streamlit` · `Plotly`

## Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

###  Detect. Classify. Investigate. Respond.

**WT Sentinel — AI-powered cybersecurity for wind turbine SCADA.**
