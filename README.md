# DevOps-Dashboard-Full-Stack-DevOps-
A dashboard to track build status, server health, and deployments across projects

## 🧱 Folder Structure
``` 
DevOps-Dashboard/
├── backend/
│   ├── app.py (Flask or FastAPI)
│   ├── requirements.txt
│   └── Dockerfile
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   ├── package.json
│   └── Dockerfile
├── ci/
│   └── github-actions.yml
├── infra/
│   ├── docker-compose.yml
│   ├── prometheus/
│   ├── grafana/
│   └── nginx/
├── k8s/
│   ├── dashboard-deployment.yaml
│   └── service.yaml
├── monitoring/
│   ├── alerts.yml
│   └── dashboards.json
├── README.md
└── .env.example
```