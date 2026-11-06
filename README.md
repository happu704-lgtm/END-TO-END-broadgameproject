# END-TO-END-broadgameproject

### End-to-End DevSecOps CI/CD Pipeline with Jenkins and Kubernetes

**Technologies:** AWS EC2, AWS EKS, Jenkins, GitHub, Maven, SonarQube, Nexus Repository, Docker, Trivy, Docker Hub, Kubernetes, Prometheus, Grafana.

- Designed and implemented an end-to-end CI/CD pipeline using Jenkins to automate source code integration, compilation, testing, code analysis, artifact management, and application deployment.
- Integrated GitHub with Jenkins to trigger automated pipeline execution whenever developers push new code changes.
- Used Maven for application compilation, testing, and package generation, with SonarQube for static code quality analysis.
- Configured Nexus Repository Manager to store and manage versioned application build artifacts.
- Containerized the application using Docker and integrated Trivy for container image vulnerability scanning.
- Pushed validated Docker images to Docker Hub and automated application deployment to an AWS EKS Kubernetes cluster.
- Integrated Prometheus and Grafana for application and infrastructure monitoring, with automated pipeline notifications.





end-to-end-devsecops-cicd-pipeline/
│
├── Jenkinsfile
├── Dockerfile
├── pom.xml
├── README.md
│
├── kubernetes/
│   ├── deployment.yaml
│   └── service.yaml
│
├── monitoring/
│   ├── prometheus.yml
│   └── grafana/
│
├── scripts/
│   └── deploy.sh
│
└── screenshots/
    └── architecture.png
