<h1 align="center">Andrew Khaleski Opata</h1>

<h3 align="center">Data Scientist · Business Analyst · ML Engineer</h3>

<p align="center">
  <em>Turning data into decisions  from exploratory analysis to deployed ML systems</em>
</p>

<p align="center">
  📍 Sydney, Australia &nbsp;|&nbsp;
  <a href="https://www.linkedin.com/in/andrew-khaleski-opata-a932b2183/">LinkedIn</a> &nbsp;|&nbsp;
  <a href="mailto:andrewopata2@gmail.com">Email</a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Ndelaski&style=flat-square&color=blue" alt="profile views" />
</p>

---

## About me

I'm a data scientist and business analyst with a postgraduate background in data science from Western Sydney University. I work across the full data lifecycle — from stakeholder requirements and business analysis through to machine learning model development, API deployment, and CI/CD pipelines. I'm passionate about building interpretable, impactful ML systems in healthcare, business intelligence, and AI engineering.

-  Currently building: end-to-end ML pipelines with MLflow + FastAPI deployment
-  Power BI dashboard portfolio covering sales, HR analytics, and KPI reporting
- Exploring: LLM applications and RAG systems with LangChain
-  MSc Data Science — Western Sydney University

---

## Skills matrix

| Area | Tools & Technologies |
|------|----------------------|
| **Languages** | Python · SQL · R · Bash |
| **Machine learning** | scikit-learn · XGBoost · PyTorch · TensorFlow · pgmpy |
| **NLP & LLMs** | HuggingFace Transformers · LangChain · FAISS · OpenAI API |
| **MLOps** | MLflow · DVC · GitHub Actions · Docker · pre-commit |
| **Data & BI** | pandas · NumPy · Power BI · DAX · Power Query · Excel |
| **Visualisation** | matplotlib · seaborn · Plotly · Power BI |
| **Cloud & deployment** | AWS (ECS, S3, ECR) · FastAPI · uvicorn · Terraform |
| **Business analysis** | Requirements documentation · BPMN · User stories · Stakeholder mapping |
| **Databases** | PostgreSQL · MySQL · SQLite |

---

## Project index

###  Machine learning & data science

| # | Project | Description | Stack | Status |
|---|---------|-------------|-------|--------|
| 1 | [covid-bayesian-prediction](https://github.com/Ndelaski/Advanced-projects) | Predicting COVID-19 and Long COVID risk using Bayesian networks, SVM, neural networks, and decision trees on clinical symptom data. Postgraduate capstone. | pgmpy · sklearn · pandas | ✅ Complete |
| 2 | [sensor-drift-ml](https://github.com/Ndelaski/sensor-drift-ml) | VOC gas classification from a 128-feature sensor array — key finding: all models drop from 98% CV accuracy to 35–50% on test due to sensor drift, not overfitting | sklearn · XGBoost · MLP · LassoCV | ✅ Complete |
| 3 | [robot-navigation-rl](https://github.com/Ndelaski/robot-navigation-rl) | 2D robot navigation simulation with reward-based control — architecturally structured for Q-learning and DQN extension | Pygame · Python · Kinematics | ✅ Complete |
| 4 | [sales-forecasting] | Time series forecasting comparing ARIMA, Prophet, and LSTM on retail sales data with seasonality decomposition | Prophet · statsmodels · PyTorch | 📋 Planned |
| 5 | [cv-image-classifier] | Transfer learning image classification with EfficientNet, data augmentation, GradCAM visualisation, and ONNX export | PyTorch · torchvision · Albumentations | 📋 Planned |

###  ML engineering & deployment

| # | Project | Description | Stack | Status |
|---|---------|-------------|-------|--------|
| 6 | [ml-api-fastapi](https://github.com/Ndelaski/ml-api-fastapi)| Production REST API serving ML model predictions — Pydantic validation, Swagger docs, Dockerised deployment | FastAPI · Docker · Pydantic | ✅ Complete |
| 7 | [ml-cicd-pipeline] | Full CI/CD pipeline: lint → test → train → evaluate → deploy gate. Automated on every push via GitHub Actions | GitHub Actions · pytest · DVC · pre-commit | 📋 Planned |
| 8 | [cloud-ml-deploy] | Infrastructure-as-code deployment of ML API to AWS ECS Fargate with auto-scaling and HTTPS | Terraform · AWS ECS · Docker | 📋 Planned |

###  Power BI & business analysis

| # | Project | Description | Tools | Status |
|---|---------|-------------|-------|--------|
| 9 | [powerbi-sales-dashboard] | Executive sales dashboard with YTD/MoM KPIs, regional drill-through, and product performance pages | Power BI · DAX · Power Query | 🔨 Building |
| 10 | [powerbi-hr-analytics](https://github.com/Ndelaski/powerbi-hr-analytics/tree/main) | HR attrition dashboard — same dataset as the ML churn project, showing the same problem from both a BI and predictive modelling angle | Power BI · DAX · IBM HR dataset | ✅ Complete |
| 11 | [healthcare-operations-dashboard](https://github.com/Ndelaski/-powerbi-healthcare-operations)|Power BI dashboard analyzing hospital operations across 4 report pages — ER visit trends, admission types, patient demographics (gender, race, blood type, condition), wait time & satisfaction by department, and billing/financial performance by insurance provider and condition |Power BI · DAX · Power Query |  ✅ Complete |



---

## Power BI highlights

> Dashboards are hosted as `.pbix` files with PDF exports and screenshots in each repo.

**Sales performance dashboard** — `powerbi-sales-dashboard`
- Revenue YTD, MoM growth, and variance to target KPI cards
- Regional sales drill-through with territory breakdown
- Top 10 products by margin and volume
- Built on AdventureWorks / Contoso sample data with full star schema model

**HR attrition dashboard** — `powerbi-hr-analytics`
- Attrition rate by department, age band, tenure, and job role
- Risk segmentation: high / medium / low attrition probability bands
- Paired with the [customer-churn-mlflow](https://github.com/Ndelaski/customer-churn-mlflow) ML project — the same business problem tackled from both a BI and predictive modelling angle

---

## Featured work: COVID-19 Bayesian Network

> Postgraduate capstone · Western Sydney University

Developed a probabilistic graphical model to predict COVID-19 infection and long COVID risk from clinical symptom data and demographic features. Model comparison across two prediction horizons:

| Model | Prediction horizon | Notes |
|-------|--------------------|-------|
| Bayesian Network (pgmpy) | 4 weeks · 6 months | Handles missing data natively |
| Logistic Regression | 4 weeks · 6 months | Interpretable baseline |
| Decision Trees | 4 weeks · 6 months | Clinically interpretable |
| SVM | 4 weeks · 6 months | Non-linear boundary exploration |
| Neural Network | 4 weeks · 6 months | Deep learning comparison |

📁 [View the repository →](https://github.com/Ndelaski/Advanced-projects)

---

## GitHub stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Ndelaski&show_icons=true&theme=default&hide_border=true&count_private=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ndelaski&layout=compact&theme=default&hide_border=true" />
</p>

---

## Connect

<p>
  <a href="https://www.linkedin.com/in/andrew-khaleski-opata-a932b2183/">
    <img src="https://img.shields.io/badge/LinkedIn-Andrew%20Khaleski%20Opata-0077B5?style=flat-square&logo=linkedin" />
  </a>
  &nbsp;
  <a href="https://github.com/Ndelaski">
    <img src="https://img.shields.io/badge/GitHub-Ndelaski-181717?style=flat-square&logo=github" />
  </a>
  &nbsp;
  <a href="mailto:your.email@gmail.com">
    <img src="https://img.shields.io/badge/Email-andrewopata2@gmail.com-D14836?style=flat-square&logo=gmail" />
  </a>
</p>

---

<p align="center">
  <sub>Open to data scientist, business analyst, and ML engineer roles in Sydney and remotely.</sub>
</p>
