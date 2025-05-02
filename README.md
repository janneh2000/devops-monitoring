DevOps-monitoring

A complete monitoring stack using Prometheus, Grafana, and Alertmanager.

 DevOps Monitoring Stack 

A complete, containerized monitoring solution using Prometheus, Grafana, and Alertmanager, built to visualize system metrics, trigger alerts, and improve observability.

Stack Overview

- Prometheus – Metrics collection & alerting engine
- Node Exporter – Exposes system-level metrics to Prometheus
- Grafana – Dashboarding and data visualization
- Alertmanager – Sends alerts via email, Slack, or webhook

 Technologies Used

| Tool            | Purpose                           |
|-----------------|-----------------------------------|
| Docker Compose  | Container orchestration           |
| Prometheus      | Metrics scraping and storage      |
| Grafana         | Real-time dashboards              |
| Node Exporter   | Server metrics collection         |
| Alertmanager    | Notification system               |
| YAML            | Configuration management          |


  How to Run It Locally

 Clone the repository:
   'bash':
   git clone git@github.com:janneh2000/devops-monitoring.git
   cd devops-monitoring




This project is licensed under the MIT License.
