# User CRUD Monitoring

Proyecto de gestión de usuarios desarrollado con FastAPI, PostgreSQL, Prometheus y Grafana.

## Descripción

El proyecto permite crear y consultar usuarios mediante una API desarrollada con FastAPI.

La información de los usuarios se almacena en PostgreSQL. Además, se implementó Prometheus para recopilar métricas de la aplicación y Grafana para visualizar estas métricas mediante un dashboard.

Todo el proyecto se ejecuta utilizando Docker y Docker Compose.

## Tecnologías utilizadas

- Python
- FastAPI
- PostgreSQL
- SQLAlchemy
- Docker
- Docker Compose
- Prometheus
- Grafana

## Estructura del proyecto

```text
user-crud-monitoring/
│
├── app/
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   ├── requirements.txt
│   └── Dockerfile
│
├── prometheus/
│   └── prometheus.yml
│
├── docker-compose.yml
└── README.md