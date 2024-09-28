# Hackathon - Health&Med
This repository is a indexer of Health&Med project repositories. Proposed as final project for the Software Architecture Postgraduate course at FIAP built in Hackathon format.

## Repositories
| Repository | Content |
| :---:   | :---: |
| [health-med-infra](https://github.com/FIAP-5SOAT-G56/health-med-infra) | Terraform project to provisioning an infrastructure on AWS including VPC, Subnets, Security Groups, ECR, ECS, RDS, Redis, SNS and SQS. |
| [health-med-api](https://github.com/FIAP-5SOAT-G56/health-med-api) | Health&Med REST API (Backend) |
| [health-med-web](https://github.com/FIAP-5SOAT-G56/health-med-web) | Health&Med Web Application Project (Frontend) |
| [health-med-notifier](https://github.com/FIAP-5SOAT-G56/health-med-notifier) | Notification Service to send emails to our users |

## Archictecture Diagrams

### Network Architecture Diagram
<img src="./docs/network_architecture.png" alt="Network Architecture Diagram" width="1200"/>

### Application Architecture Diagram
<img src="./docs/application_architecture.png" alt="Application Architecture Diagram" width="1200"/>

### Notifier Architecture Diagram
<img src="./docs/notifier_architecture.png" alt="Notifier Architecture Diagram" width="900"/>


### Concurrence Handling Diagram
<img src="./docs/concurrence_handling.png" alt="Concurrence Handling Diagram" width="1200"/>