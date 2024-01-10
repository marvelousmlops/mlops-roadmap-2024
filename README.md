# MLOps Roadmap 2024

## 1. Programming
Programming skills are crucial for an MLOps engineer. Python is the most commonly used language in machine learning, making it important for collaboration with machine learning engineers and data scientists.

### 1.1. Python & IDEs
Start learning Python through books and practice.

- **Book Suggestion:** [Python Crash Course, 3rd Edition](https://www.amazon.com/stores/Eric-Matthes/author/B01DPU378I?ref=ap_rdr&store_ref=ap_rdr&isDramIntegrated=true&shoppingPortalEnabled=true) by Eric Matthes
- **Code Practice:** [LeetCode Python Problems](https://leetcode.com/problemset/)
- **Courses:** [Learn Python 3](https://www.codecademy.com/learn/learn-python-3)
- **Track Suggestions:** Python fundamentals, Python programming
- **Important Topics:** Installing Python, using virtual environments, IDE usage, Python basics, Pytest, Packaging

### 1.2. Bash Basics & Command Line Editors
Understanding bash is essential for MLOps tasks.

- **Book Suggestion:** _The Linux Command Line, 2nd Edition_ by William E. Shotts
- **Course:** Bash mastery
- **Tutorial:** VIM beginners guide

## 2. Containerization and Kubernetes
These technologies are vital in modern software engineering.

### 2.1. Docker
Docker is a popular open-source containerization platform used in MLOps.

- **Docker Roadmap:** [Roadmap.sh Docker](https://roadmap.sh/docker)
- **Tutorial:** Full docker tutorial by Techworld by Nana

### 2.2. Kubernetes
Kubernetes is essential for machine learning model training and deployment.

- **Kubernetes Roadmap:** [Roadmap.sh Kubernetes](https://roadmap.sh/kubernetes)
- **Tutorial:** Kubernetes course by freecodecamp.com
- **Course:** Kubernetes mastery
- **Tool:** [K9s CLI for Kubernetes](https://k9scli.io)

## 3. Machine Learning Fundamentals
An MLOps engineer should have a basic understanding of machine learning models.

- **Course:** [MLCourse.ai](https://mlcourse.ai/)
- **Book Suggestion:** _Applied Machine Learning and AI for Engineers_ by Jeff Prosise

## 4. MLOps Principles
Awareness of MLOps principles and maturity factors is required.

- **Books:**
  - _Designing Machine Learning Systems_ by Chip Huyen
  - _Introducing MLOps_ by Mark Treveil and Dataiku
- **Assessment:** MLOps maturity assessment

## 5. MLOps Components
MLOps platforms consist of various components, from version control to feature stores.

### 5.1. Version Control & CI/CD Pipelines
Critical for traceable and reproducible ML model deployments.

- **Books:**
  - _Learning GitHub Actions_ by Brent Laster
  - _Learning Git_ by Anna Skoulikari
- **Tutorials & Courses:** Git & GitHub for beginners, Python to Production guide
- **Tool:** Pre-commit hooks

### 5.2. Orchestration
Systems like Airflow and Mage are important in ML engineering.

- **Course:** Introduction to Airflow in Python
- **Note:** Airflow is also featured in the _ML Engineering with Python_ book and _The Full Stack 7-Steps MLOps Framework_.

### 5.3. Experiment Tracking and Model Registries
Logging metadata, parameters, and artifacts of training runs.

- **Tool:** MLflow
- **Courses:** MLflow Udemy course, End-to-end machine learning (MLflow piece)

### 5.4. Data Lineage and Feature Stores
Feature stores are a crucial component of MLOps infrastructure.

- **Tutorial:** Creating a feature store with Feast (Parts 1-3)
- **Tool:** DVC for data tracking
- **Course:** End-to-end machine learning (DVC piece)

### 5.5. Model Training & Serving
Decisions depend on the organization's infrastructure.

- **Tutorial Suggestions:** ML deployment with k8s FastAPI, Building an ML app with FastAPI, Basic Kubeflow pipeline, Building and deploying ML pipelines, KServe tutorial

### 5.6. Monitoring & Observability
Vital for the health and performance of ML systems.

- **Course:** Machine learning monitoring concepts, Monitoring ML in Python
- **Tools:** Prometheus, Grafana

## 6. Infrastructure as Code: Terraform
Essential for a reproducible MLOps framework.

- **Course:** Terraform course for beginners
- **Video:** 8 Terraform best practices by Techworld by Nana
- **Book Suggestion:** _Terraform: Up and Running, 3rd Edition_ by Yevgeniy Brikman
