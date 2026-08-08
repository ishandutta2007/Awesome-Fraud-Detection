# Awesome-Fraud-Detection

## Top Fraud Detection Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Transaction Fraud, Account Abuse, Chargeback Prevention, Device Intelligence & Real-Time Risk Scoring*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Fraud Detection**. These tools analyze transactions, devices, behavior, and identity signals in real time to score risk, block fraudulent activity, reduce chargebacks, detect account takeovers, and support investigation workflows across e-commerce, payments, fintech, and digital platforms.

**Examples** include Sift, SEON, Signifyd, Riskified, Forter, Feedzai, Sardine, Kount, Fraud.net, and DataDome (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, machine-learning anomaly detection, graph-based fraud intelligence, rule engines, and open risk-scoring pipelines — ideal for risk teams, data scientists, fintechs, and developers building transparent, auditable fraud prevention systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Sift](https://sift.com/)**  
  Machine-learning digital trust platform for payment fraud, account abuse, content abuse, and real-time risk scoring with a large cross-customer signal network.

- **[SEON](https://seon.io/)**  
  API-first fraud prevention platform combining device fingerprinting, digital footprint enrichment, email/phone intelligence, and transparent risk scoring.

- **[Signifyd](https://www.signifyd.com/)**  
  Chargeback-guarantee fraud protection for e-commerce that approves or declines orders and assumes liability on approved transactions.

- **[Riskified](https://www.riskified.com/)**  
  AI-powered e-commerce fraud prevention with chargeback guarantee, focused on maximizing approvals while protecting merchants from fraud losses.

- **[Forter](https://www.forter.com/)**  
  Identity-based fraud decisioning platform that provides real-time approve/decline decisions using a large cross-merchant identity graph.

- **[Feedzai](https://www.feedzai.com/)**  
  Enterprise RiskOps platform for banks and payment processors combining fraud, AML, and real-time transaction monitoring with explainable AI.

- **[Sardine](https://www.sardine.ai/)**  
  Unified device intelligence, behavioral analytics, fraud, and compliance platform popular with fintechs, crypto, and instant-payment use cases.

- **[Kount (Equifax)](https://kount.com/)**  
  Identity-trust and fraud scoring solution with configurable rules, device data, and global identity insights for e-commerce and payments.

- **[Fraud.net](https://www.fraud.net/)**  
  Multi-layered fraud prevention platform offering AI models, consortium data, and case management for financial services and commerce.

- **[DataDome](https://datadome.co/)**  
  Bot and automated threat protection platform that defends websites, APIs, and mobile apps against scrapers, credential stuffing, and payment abuse.

## Open-Source GitHub Projects

- **[PyOD](https://github.com/yzhao062/pyod)**  
  Comprehensive Python library for anomaly/outlier detection with 60+ algorithms across tabular, time-series, graph, and other data modalities — widely used for fraud scoring.

- **[DGFraud](https://github.com/safe-graph/DGFraud)**  
  Deep graph-based toolbox implementing state-of-the-art GNN models for fraud detection on heterogeneous and homogeneous graphs.

- **[Jube](https://github.com/jube-home/aml-fraud-transaction-monitoring)**  
  Full open-source AML and fraud transaction monitoring platform with real-time scoring, adaptive ML, rule engines, and case management (AGPLv3).

- **[Rift](https://github.com/AngelP17/Rift)**  
  Graph-based intelligence system for entity resolution, anomaly detection, and investigative workflows with hybrid GraphSAGE + XGBoost modeling and audit trails.

- **[PyGOD](https://github.com/pygod-team/pygod)**  
  Python library specialized in graph outlier detection using modern graph neural network techniques.

- **[Fraud Detection MCP](https://github.com/marc-shade/fraud-detection-mcp)**  
  Model Context Protocol server combining Isolation Forest, autoencoders, behavioral biometrics, and network graph analysis for agent-driven fraud detection.

- **[Transaction Anomaly Detection](https://github.com/KuchikiRenji/Transaction-Anomaly-Detection)**  
  Enterprise-style fraud & AML system with XGBoost/LightGBM, autoencoders, LSTM/Transformer models, SHAP explainability, and real-time API.

- **[AntiFraud (AI4Risk)](https://github.com/finint/antifraud)**  
  Collection of published graph and deep-learning models for credit-card and financial fraud detection (GTAN, RGTAN, HOGRL, etc.).

- **[Orion](https://github.com/sintel-dev/Orion)**  
  MIT-originated open-source time-series anomaly detection framework designed for accessibility and large-scale industrial use.

- **[UGFraud](https://github.com/safe-graph/UGFraud)**  
  Unsupervised graph-based toolbox for fraud detection complementary to supervised GNN approaches.

- **[tirreno](https://github.com/tirreno/tirreno)**  
  Security framework focused on event tracking, threat detection, and risk scoring for applications.

- **[FingerprintJS / open device signals](https://github.com/fingerprintjs)**  
  Open-source browser and device fingerprinting libraries that can feed custom fraud and bot-detection pipelines.

### Additional Strong Open-Source Options

- **Isolation Forest, One-Class SVM, Autoencoder, and XGBoost/LightGBM** notebooks and pipelines for classic tabular fraud detection.
- **NetworkX / graph analytics** projects for fraud-ring and mule-account detection.
- **Rule engines** (Drools, Easy Rules, custom Python/Go engines) combined with ML scores.
- **SHAP / LIME** explainability tooling for model transparency and analyst workflows.
- **OpenTelemetry + custom feature stores** for real-time signal collection.
- Many community **credit-card fraud**, **PaySim**, and **synthetic-data** training projects and benchmarks.

**Frameworks for building custom systems**: Combine **PyOD / Isolation Forest / XGBoost** for scoring, **DGFraud or PyGOD** for graph intelligence, **Jube or Rift** for end-to-end monitoring and case management, device fingerprinting libraries, and a rules layer for a complete open-source fraud detection platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Fraud detection systems must comply with applicable regulations (PCI-DSS, GDPR, AML/KYC requirements, etc.) and ethical data-use policies.
- Self-hosted open-source solutions require careful model governance, bias monitoring, data security, and operational reliability.

---

**Made for fraud analysts, risk engineers, fintech builders, and payment security teams.**  
Let's make fraud detection more transparent, controllable, and effective.
