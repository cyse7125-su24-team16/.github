# AI Orchestrator

© 2024 AI Orchestrator

**Aim:**
- To automate the processing and storage of CVE data, ensuring timely updates and enhancing the ability to query this data using advanced machine learning techniques, while maintaining a scalable and efficient infrastructure.

**Implementation:**
- Deployed infrastructure on AWS EKS using Terraform and managed Kubernetes resources with Helm charts and Docker.
- Configured Jenkins for CI/CD pipelines, incorporating Packer for image creation and deploying on EC2 instances with Caddy as a sidecar proxy.
- Developed Kafka-based distributed systems with Go to process and store CVE data in a Postgres database.
- Built a custom Kubernetes operator to process CVE deltas released every hour.
- Automated the CVE data ingestion pipeline, integrating processed data into a vector database to enhance an LLM's capability to answer CVE-related queries.

**Outcome:**
- The project successfully created a robust, automated system for processing and storing CVE data, ensuring timely updates and improving query capabilities through machine learning integration. This resulted in enhanced system reliability, data integrity, and overall efficiency in managing and utilizing CVE information.

## Topics

- [x] **Training LLM models**
- [x] **DevOps, GitOps, SRE**
- [x] **Linux, Shell Scripting**
- [x] **Version Control with Git**
- [x] **Cloud Computing**
- [x] **Microservices Architecture**
- [x] **Application containerization**
- [x] **Orchestration of containerized applications using Kubernetes**
- [x] **Custom Kubernetes Operator**
- [x] **Identity & Access Management**
- [x] **Infrastructure as Code**
- [x] **Service Meshes**
- [x] **Continuous Integration, Continuous Delivery, and Continuous Deployment**
- [x] **Operational Visibility (Logging, Metrics, Monitoring, and Alerting)**
- [x] **Bash/Shell scripting**
- [x] **Auto-scaling Applications**
- [x] **Event-driven Architecture**
- [x] **Serverless Computing**
- [x] **Securing cloud applications and infrastructure**


## Authors
- [Vaishnavi Mantri](https://github.com/VaishnaviNEU)
- [Anusha Senthilnathan](https://github.com/Anu-3980)
