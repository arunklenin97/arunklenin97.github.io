# Experience

<div class="highlights-strip" markdown>
  <span class="stat-chip"><strong>5+ yrs</strong> across AI research, risk analytics & fintech</span>
  <span class="stat-chip"><strong>3</strong> organizations: CBA, Wells Fargo, ICICI Bank</span>
  <span class="stat-chip"><strong>1</strong> lead-author publication (EMNLP 2026, under review)</span>
</div>

<div class="timeline" markdown>

<div class="timeline-entry" markdown>

## :material-bank: Commonwealth Bank of Australia — AI Labs

> :material-map-marker: _Bengaluru, India_

### Data Scientist · Jul 2026 – present

Knowledge representation, LLM fine-tuning, model compression, and agentic AI safety research.

**Customer Privacy Protection: NER Fine-tuning & Model Compression**

- Designed a synthetic data generation framework to fine-tune NER models for customer privacy detection
- Merged fine-tuned model variants using model souping, and applied Viterbi decoding with custom loss functions to improve sequence-level accuracy
- Used structured pruning and knowledge distillation to produce a compact, low-latency model with under 1% performance drop from the teacher model

**Agentic System User-Vulnerability Research**

- Built an end-to-end framework simulating vulnerability scenarios that arise while users interact with agentic systems on a primary task
- Built an evaluation pipeline to assess a benchmark dataset of these scenarios
- Studied frontier LLM behavior under different vulnerable circumstances as part of a responsible AI research effort

</div>

<div class="timeline-entry" markdown>

### Senior Associate Data Scientist · 2024 – Jun 2026

Applied research team covering LLM fine-tuning, agentic AI systems, and MLOps, with a focus on knowledge-representation-driven system design for downstream task performance.

#### LLM Fine-tuning & Agentic Systems

**EmbGen: Synthetic Data Generation Algorithm**

- Generates training data that captures concept relationships across documents
- Outperformed existing baselines on internal benchmarks
- Published as lead author; see [Publications](#publications)

**LLM Fine-tuning**

- Fine-tuned an open-source LLM for a customer-facing banking task using an adapted Synthetic Continued Pretraining approach to generate large volumes of training data from noisy, insufficient real data
- Outperformed frontier closed-weight models, with the fine-tuned model learning internal bank taxonomy and responding more accurately to customer problems
- Enabled production deployment of an open-source model in place of external APIs

**Infrastructure & Tooling**

- Trained and fine-tuned LLMs at scale on AWS SageMaker and HyperPod, with vLLM for efficient inference and Kubernetes for distributed training
- Used MLflow for experiment tracking across projects, keeping training runs reproducible

</div>

<div class="timeline-entry timeline-entry--muted" markdown>

## :material-finance: Wells Fargo — Senior Quantitative Model Solutions Specialist

Jul 2022 – Jun 2024 · :material-map-marker: _Bengaluru, India_

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

</div>

<div class="timeline-entry timeline-entry--muted" markdown>

## :material-bank-outline: ICICI Bank — Manager 1, Risk Analytics

Oct 2020 – Jun 2022 · :material-map-marker: _Mumbai, India_

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

</div>

</div>

---

## Publications

**[EmbGen: Teaching with Reassembled Corpora](https://arxiv.org/abs/2605.19394)**
Arun K Lenin, Kai Rouse, Andrea Nicastro, Anna Leontjeva
Lead author · arXiv:2605.19394 · under review, EMNLP 2026

A synthetic data generation algorithm for LLM fine-tuning that captures how concepts relate across a document rather than in isolation; outperformed existing baselines on internal benchmarks.

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

- **Hackathon Problem Design** — designed the problem statement for a CBA India hackathon within two months of joining, and for the Gen AI Banking Hackathon, a three-week program guiding 30 graduate hires through real, use-case-driven projects
- **Competitive ML Learning Programme** — co-built a community learning program
- **Mentoring** — guided junior data scientists through independent research projects
- **Campus Recruitment** — designed coding assessments and recruited at IITs

---

## Technical Skills

**Languages:** Python, PySpark, R, SQL, MATLAB, Bash

**ML / Deep Learning:** LLM fine-tuning, synthetic data generation, data selection (SIFT/submodular), NER/PII detection, ensemble methods, multimodal VLM fine-tuning, reinforcement learning, pruning & knowledge distillation

**Algorithms & Statistics:** UMAP, HDBSCAN, Gaussian Processes, K-means clustering, PSI/CSI analysis, submodular optimization, drift detection

**NLP & Evaluation:** RoBERTa, AllenNLP, BERT, GENSIM, TF-IDF, LLM-as-judge evaluation

**Cloud & Infrastructure:** AWS SageMaker, HyperPod, vLLM, Kubernetes, distributed training

**MLOps & Tools:** MLflow, Optuna, H2O.ai, Tableau, modular OO architecture, reproducible experiment tracking

**Libraries:** Keras, NumPy, Pandas, NLTK, Gensim, Scikit-learn
