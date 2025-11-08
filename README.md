Overview
This project is a climate‑data analysis and visualization dashboard built with Python and FastAPI. It demonstrates the collection, processing, and presentation of climate trends (such as CO₂ emissions, temperature changes, rainfall variations) with the goal of supporting decision‑making in sustainable development and environmental protection.

Purpose & Relevance

Aligns with sustainable development goals (SDGs) such as SDG 13: Climate Action

Demonstrates ability to build web APIs, data pipelines, and dashboards — skills in high demand in UN‑agency digital transformation

Built for potential adaptation by organizations working in environment, climate policy, or humanitarian tech


Tech Stack

Backend: Python + FastAPI

Data Storage: CSV / Pandas for initial dataset

Visualization: Streamlit (or React)

Version Control: Git + GitHub

Cloud Ready: Structured for deployment (e.g., AWS, Azure)


Features

1. Load and preprocess climate datasets (CO₂, temperature, rainfall)


2. REST API endpoints for retrieving processed data


3. Dynamic dashboard for visualization of trends and maps


4. Clear documentation and clean code structure for maintenance and extension



Repository Structure

climate-dashboard/
│
├─ backend/
│  ├─ app/
│  │  ├─ main.py
│  │  ├─ routers/
│  │  ├─ models/
│  │  ├─ services/
│  │  └─ schemas/
├─ data/
│  └─ climate_data.csv
└─ README.md

Next Steps

Expand dataset to include region-specific (Kenya / East Africa) climate data

Develop frontend UI (Streamlit or React)

Deploy on cloud (e.g., AWS EC2 or AWS Lambda + API Gateway)

Add authentication and user roles if used in organization context


How to Run Locally

1. Clone the repository
git clone https://github.com/Leposo-Brian/climate-dashboard.git
cd climate-dashboard/backend


2. Install dependencies
pip install -r requirements.txt


3. Run the FastAPI app
uvicorn app.main:app --reload


4. Open browser at http://localhost:8000/docs to explore API endpoints



Contact
Leposo Brian – Kenya
GitHub: https://github.com/Leposo-Brian
add initial README.md
