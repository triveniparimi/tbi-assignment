# tbi-assignment
"Cloud-native ML model deployment with Terraform, FastAPI, CI/CD, and monitoring"
# TBI Assignment – ML Model Deployment

This project demonstrates how to serve a Machine Learning model using:

- **FastAPI** for the REST API
- **Docker** for containerization
- **GitHub Actions** for CI/CD automation
- **Terraform** for infrastructure provisioning
- **Prometheus + Grafana** for monitoring

## Project Structure
app/
└── main.py # FastAPI app
infra/
└── main.tf # Terraform infra setup
.github/workflows/
└── deploy.yml # GitHub Actions pipeline
docker/
└── Dockerfile # Container build


## Instructions

1. Build: `docker build -t ml-app .`
2. Run: `docker run -p 8000:8000 ml-app`
3. Open: `http://localhost:8000`

## Author

Triveni Parimi


