# Experience

## Senior Associate Data Scientist
**Commonwealth Bank of Australia — AI Labs** · 2024 – present

Applied research team covering LLM fine-tuning, agentic AI systems, and MLOps, with a focus on knowledge-representation-driven system design for downstream task performance.

### Research & Modeling

**EmbGen: Synthetic Data Generation Algorithm**
- Lead author; manuscript under review at EMNLP 2026
- Generates training data that captures concept relationships across documents
- Outperformed existing baselines on internal benchmarks

**Domain-Specific LLM Fine-tuning**
- Fine-tuned open-source LLMs for financial-domain tasks, matching or exceeding frontier closed-source model quality on internal evaluations
- Enabled production deployment of open-source models in place of external APIs

**Lightweight NER via Synthetic Data & Distillation**
- Built a synthetic data generation framework to fine-tune NER/PII detection models
- Applied structured pruning and knowledge distillation from a larger teacher model
- Delivered a lightweight model with substantially improved inference latency and minimal accuracy loss relative to the teacher

**Semantic Drift Detection Framework**
- Designed for deployed generative AI agents in production
- Combines embedding-based domain representation with LLM-scored retrieval
- Outperformed standard statistical drift methods

**PII Detection Model Improvements**
- Class rebalancing, constrained decoding, ensemble inference
- Resolved reproducibility failures with measurable F1 gains

**AI Agent PoC for Customer Vulnerability**
- Joint project with an AI vendor
- Improved vulnerable customer identification from near-zero to 89%

### MLOps & Infrastructure

**Seven-Layer Modular Architecture**
- Designed a scalable object-oriented architecture for LLM fine-tuning
- Standardized across three projects

**Automated End-to-End Training Pipeline**
- AWS HyperPod deployment
- Single-command pre-training → fine-tuning → inference → evaluation
- Parallel job execution with structured logging

**Experiment Tracking & Cloud Infrastructure**
- MLflow integration for reproducible tracking
- AWS SageMaker, IAM, KMS, and S3 management
- Kubernetes-based distributed training

---

??? info "Wells Fargo — Senior Quantitative Model Solutions Specialist · July 2022 – June 2024"

    Quantitative modeling, economic forecasting, and production ML systems in financial risk.

    **Economic Data Visualization Tool**
    - Developed a Python tool for dynamic dashboard generation of economic forecasts
    - Automated chart and table creation in PowerPoint templates, generating hundreds of slides within minutes
    - Built an integrated UI for non-technical users

    **Pre-Provision Net Revenue (PPNR) Model**
    - Supported annual CCAR submissions and mid-year financial assessments
    - Ran six statistical forecast models and analyzed key drivers
    - Achieved a 90x efficiency improvement through Python automation
    - Integrated PSI monitoring into the production control process

    **Customer Attrition NLP Challenge**
    - 9th place globally out of thousands of entries (one of two Indian teams in the top 10)
    - Built an NLP solution using customer–bank communication data
    - Applied RoBERTa, AllenNLP, TF-IDF, BERT, and topic modeling (Gensim)
    - Weighted ensemble models with balanced class weights on PCA components

??? info "ICICI Bank — Manager 1, Risk Analytics · Oct 2020 – June 2022"

    Risk modeling, statistical profiling, and production model monitoring for the retail portfolio.

    **Master Rating Scale Development**
    - Developed an instrumental rating scale for risk differentiation
    - Used K-means clustering for PD bin formation in the retail portfolio

    **Statistical Profiling Model for Sales Hiring**
    - Quantified behavioral psychology for candidate scoring
    - Used AHP (Analytic Hierarchy Process) and Mahalanobis distance
    - Personality trait assessment using PCA

    **SME ML Model Monitoring**
    - PSI-CSI analysis for model stability evaluation
    - Automated feature recategorization and WOE computation
    - Built Python-based production monitoring scripts

    **Model Validation (US GAAP CECL)**
    - Automated PD-LGD aggregation for the retail portfolio
    - Validated ARIMAX models across 21 retail segments
    - Systemic factor estimation using Nelder-Mead optimization

---

## Education

**B.Tech in Chemical Engineering** (Minor: Data Driven Modeling & Systems Engineering)
Indian Institute of Technology Madras — 2020

Coursework: Applied Time Series Analysis, Multivariate Data Analysis, Machine Learning for Engineering, Mathematics for Data Science

??? info "Academic Projects"

    **Model Identification using IPCA & NCA**
    - Face recognition on the YaleFace dataset
    - Pipeline network leak detection and chemometrics calibration

    **Time Series Forecasting**
    - SARIMA modeling with ACF/PACF analysis

    **Credit Card Fraud Detection**
    - SVM implementation (linear, quadratic, and Gaussian kernels)
    - 91% accuracy using grid search and 10-fold cross-validation

---

## Community & Mentoring

- **Gen AI Banking Hackathon** — designed and ran a three-week program for 30 graduate hires
- **Competitive ML Learning Programme** — co-built a community learning program
- **Speaker Series** — hosted researchers from Stanford, UNSW, and industry
- **Mentoring** — guided junior data scientists through independent research projects
- **Campus Recruitment** — designed coding assessments and recruited at IITs

---

## Technical Skills

**Languages:** Python, PySpark, R, SQL, MATLAB, Bash

**ML / Deep Learning:** LLM fine-tuning, synthetic data generation, data selection (SIFT/submodular), NER/PII detection, ensemble methods, multimodal VLM fine-tuning, reinforcement learning, pruning & knowledge distillation

**Algorithms & Statistics:** UMAP, HDBSCAN, Gaussian Processes, K-means clustering, PSI/CSI analysis, submodular optimization, drift detection

**NLP & Evaluation:** RoBERTa, AllenNLP, BERT, GENSIM, TF-IDF, LLM-as-judge evaluation

**Cloud & Infrastructure:** AWS SageMaker, HyperPod, S3, IAM, KMS, Kubernetes, distributed training

**MLOps & Tools:** MLflow, Optuna, H2O.ai, Tableau, modular OO architecture, reproducible experiment tracking

**Libraries:** Keras, NumPy, Pandas, NLTK, Gensim, Scikit-learn
