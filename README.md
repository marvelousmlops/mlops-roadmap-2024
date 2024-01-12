# MLOps Roadmap 2024

## 1. Programming
Programming skills are crucial for an MLOps engineer. Python is the most commonly used language in machine learning, making it important for collaboration with machine learning engineers and data scientists.

### 1.1. Python & IDEs
Start learning Python through books and practice.
- **Tutorial Suggestion:** https://realpython.com
- **Book Suggestion:** [Python Crash Course, 3rd Edition](https://www.amazon.com/stores/Eric-Matthes/author/B01DPU378I?ref=ap_rdr&store_ref=ap_rdr&isDramIntegrated=true&shoppingPortalEnabled=true) by Eric Matthes
- **Code Practice:** [LeetCode Python Problems](https://leetcode.com/problemset/)
- **Courses:** [Learn Python 3](https://www.codecademy.com/learn/learn-python-3)
- **Track Suggestions:** [Python fundamentals](https://app.datacamp.com/learn/skill-tracks/python-fundamentals), [Python programming](https://app.datacamp.com/learn/skill-tracks/python-programming)

- **Important Topics:** [Installing Python, using virtual environments](https://marvelousmlops.substack.com/p/the-right-way-to-install-python-on), [IDE usage](https://mlops.community/how-to-configure-vs-code-for-ai-ml-and-mlops-development-in-python-🛠%EF%B8%8F%EF%B8%8F/), Python basics, [Pytest](https://app.datacamp.com/learn/skill-tracks/python-programming), [Packaging](https://www.freecodecamp.org/news/how-to-build-and-publish-python-packages-with-poetry/)

### 1.2. Bash Basics & Command Line Editors
Understanding bash is essential for MLOps tasks.

- **Book Suggestion:** _The Linux Command Line, 2nd Edition_ by William E. Shotts
- **Course:** [Bash mastery](https://www.udemy.com/course/bash-mastery)
- **Tutorials:** [VIM beginners guide](https://www.freecodecamp.org/news/vim-beginners-guide/), [VIM adventures](https://vim-adventures.com/), [VIM by Daniel Miessler](https://danielmiessler.com/p/vim/)

## 2. Containerization and Kubernetes
These technologies are vital in modern software engineering.

### 2.1. Docker
Docker is a popular open-source containerization platform used in MLOps.

- **Docker Roadmap:** [Roadmap.sh Docker](https://roadmap.sh/docker)
- **Tutorial:** [Full docker tutorial by Techworld by Nana](https://www.youtube.com/watch?v=3c-iBn73dDE)

### 2.2. Kubernetes
Kubernetes is essential for machine learning model training and deployment.

- **Kubernetes Roadmap:** [Roadmap.sh Kubernetes](https://roadmap.sh/kubernetes)
- **Tutorial:** [Kubernetes course by freecodecamp.com](https://www.youtube.com/watch?v=d6WC5n9G_sM)
- **Course:** [Kubernetes mastery](https://www.udemy.com/course/kubernetesmastery/)
- **Tool:** [K9s CLI for Kubernetes](https://k9scli.io)

## 3. Machine Learning Fundamentals
An MLOps engineer should have a basic understanding of machine learning models.

- **Courses:** [MLCourse.ai](https://mlcourse.ai/), [Fast.ai](https://course.fast.ai)
- **Book Suggestion:** _Applied Machine Learning and AI for Engineers_ by Jeff Prosise

## 4. MLOps Principles
Awareness of MLOps principles and maturity factors is required.

- **Books:**
  - _Designing Machine Learning Systems_ by Chip Huyen
  - _Introducing MLOps_ by Mark Treveil and Dataiku
- **Assessment:** [MLOps maturity assessment](https://marvelousmlops.substack.com/p/mlops-maturity-assessment)
- **Great resource on MLOps:** [ml-ops.org](https://ml-ops.org)

## 5. MLOps Components
MLOps platforms consist of various components, from version control to feature stores. 
- [The minimum set of must-haves for MLOps article.](https://marvelousmlops.substack.com/p/the-minimum-set-of-must-haves-for)

- [Made with ML MLOps Course](https://madewithml.com/courses/mlops/)

- [The full stach 7-steps MLOps Framework](https://www.pauliusztin.me/courses/the-full-stack-7-steps-mlops-framework)
- [End-to-end machine learning](https://www.udemy.com/course/sustainable-and-scalable-machine-learning-project-development/)


### 5.1. Version Control & CI/CD Pipelines
Critical for traceable and reproducible ML model deployments.

- **Books:**
  - _Learning GitHub Actions_ by Brent Laster
  - _Learning Git_ by Anna Skoulikari
- **Tutorials & Courses:** [Git & GitHub for beginners](https://www.youtube.com/watch?v=RGOj5yH7evk), [Python to Production guide](https://www.udemy.com/course/setting-up-the-linux-terminal-for-software-development/), [Version Control Missing Semester](https://missing.csail.mit.edu/2020/version-control/), https://learngitbranching.js.org/
- **Tool:** [Pre-commit hooks](https://marvelousmlops.substack.com/p/welcome-to-pre-commit-heaven)

### 5.2. Orchestration
Systems like Airflow and Mage are important in ML engineering.

- **Course:** [Introduction to Airflow in Python](https://app.datacamp.com/learn/courses/introduction-to-airflow-in-python)
- **Note:** Airflow is also featured in the _ML Engineering with Python_ book and [_The Full Stack 7-Steps MLOps Framework_](https://www.pauliusztin.me/courses/the-full-stack-7-steps-mlops-framework).

### 5.3. Experiment Tracking and Model Registries
Logging metadata, parameters, and artifacts of training runs.

- **Tool:** MLflow
- **Courses:** [MLflow Udemy course](https://www.udemy.com/course/mlflow-course/), [End-to-end machine learning (MLflow piece)](https://www.udemy.com/course/sustainable-and-scalable-machine-learning-project-development/)

### 5.4. Data Lineage and Feature Stores
Feature stores are a crucial component of MLOps infrastructure.

- **Tutorial:** Creating a feature store with Feast [Part 1](https://kedion.medium.com/creating-a-feature-store-with-feast-part-1-37c380223e2f) [Part 2](https://kedion.medium.com/feature-storage-for-ml-with-feast-part-2-34df1971a8d3) [Part 3](https://kedion.medium.com/feature-storage-for-ml-with-feast-a061899fc4a2)
- **Tool:** DVC for data tracking
- **Course:** [End-to-end machine learning (DVC piece)](https://www.udemy.com/course/sustainable-and-scalable-machine-learning-project-development/)

### 5.5. Model Training & Serving
Decisions depend on the organization's infrastructure.

- **Repository Suggestion:** [ML Deployment k8s Fast API](https://github.com/sayakpaul/ml-deployment-k8s-fastapi/tree/main)
- **Tutorial Suggestions:** [ML deployment with k8s FastAPI, Building an ML app with FastAPI](https://dev.to/bravinsimiyu/beginner-guide-on-how-to-build-a-machine-learning-app-with-fastapi-part-ii-deploying-the-fastapi-application-to-kubernetes-4j6g), [Basic Kubeflow pipeline](https://towardsdatascience.com/tutorial-basic-kubeflow-pipeline-from-scratch-5f0350dc1905), [Building and deploying ML pipelines](https://www.datacamp.com/tutorial/kubeflow-tutorial-building-and-deploying-machine-learning-pipelines?utm_source=google&utm_medium=paid_search&utm_campaignid=19589720818&utm_adgroupid=157156373991&utm_device=c&utm_keyword=&utm_matchtype=&utm_network=g&utm_adpostion=&utm_creative=683184494153&utm_targetid=dsa-2218886984380&utm_loc_interest_ms=&utm_loc_physical_ms=9064564&utm_content=&utm_campaign=230119_1-sea~dsa~tofu_2-b2c_3-eu_4-prc_5-na_6-na_7-le_8-pdsh-go_9-na_10-na_11-na-dec23&gad_source=1&gclid=Cj0KCQiA4Y-sBhC6ARIsAGXF1g7iSih9h2RGL27LwWY6dlPLhEss-e5Af8pnaBvdDynRh7IHIKi8sGgaApD-EALw_wcB), [KServe tutorial](https://towardsdatascience.com/kserve-highly-scalable-machine-learning-deployment-with-kubernetes-aa7af0b71202)

### 5.6. Monitoring & Observability
Vital for the health and performance of ML systems.
- [**ML Monitoring vs Observability article**](https://marvelousmlops.substack.com/p/ml-monitoring-vs-ml-observability)
- **Course:** [Machine learning monitoring concepts](https://app.datacamp.com/learn/courses/machine-learning-monitoring-concepts), [Monitoring ML in Python](https://app.datacamp.com/learn/courses/monitoring-machine-learning-in-python)
- **Tools:** [Prometheus, Grafana](https://www.udemy.com/course/mastering-prometheus-and-grafana/)

## 6. Infrastructure as Code: Terraform
Essential for a reproducible MLOps framework.

- **Course:** [Terraform course for beginners](https://www.youtube.com/watch?v=SLB_c_ayRMo)
- **Video:** [8 Terraform best practices by Techworld by Nana](https://www.youtube.com/watch?v=gxPykhPxRW0)
- **Book Suggestion:** _Terraform: Up and Running, 3rd Edition_ by Yevgeniy Brikman
