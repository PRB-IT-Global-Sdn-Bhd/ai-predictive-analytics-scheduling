# AI Solutions — Predictive Analytics & Scheduling

> **PRB IT Global Sdn Bhd** | Custom Software for SME Engineering & Construction Clients (Malaysia)

## Overview

An **AI-powered Predictive Analytics and Project Scheduling** platform that leverages machine learning to forecast project delays, optimise resource allocation, and generate intelligent construction schedules. The system helps SME engineering firms make data-driven decisions to deliver projects on time and within budget.

## Key Features

| Feature | Description |
|---|---|
| Delay Prediction | ML models to predict schedule overruns before they occur |
| Resource Optimisation | AI-driven allocation of labour, equipment, and materials |
| Schedule Generation | Automated CPM/PERT scheduling with constraint handling |
| Risk Assessment | Probabilistic risk scoring for project milestones |
| Weather Integration | Weather data integration for outdoor activity scheduling |
| What-If Scenarios | Simulation of alternative project scenarios |
| Dashboard | Interactive analytics dashboards with drill-down capability |

## Technology Stack

- **AI/ML:** Python, scikit-learn, TensorFlow / PyTorch, XGBoost
- **Backend:** Python (FastAPI / Django)
- **Frontend:** React.js, D3.js / Plotly for visualisations
- **Database:** PostgreSQL + TimescaleDB
- **MLOps:** MLflow, Docker, Kubernetes
- **Cloud:** AWS SageMaker / Azure ML

## Target Users

Project managers, planning engineers, directors, and operations analysts.

## Getting Started

```bash
git clone https://github.com/PRB-IT-Global-Sdn-Bhd/ai-predictive-analytics-scheduling.git
cd ai-predictive-analytics-scheduling
pip install -r requirements.txt
python train.py
uvicorn api.main:app --reload
```

## Licence

Proprietary — © 2024 PRB IT Global Sdn Bhd. All rights reserved.
