# AI/ML Projects by Senior Data Scientist

[![Python](https://img.shields.io/badge/Python-3.9+-blue)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.12-orange)](https://pytorch.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)](https://www.tensorflow.org/)
[![AWS](https://img.shields.io/badge/AWS-Cloud-yellow)](https://aws.amazon.com/)
[![Azure](https://img.shields.io/badge/Azure-Cloud-blue)](https://azure.microsoft.com/)
[![GCP](https://img.shields.io/badge/GCP-Cloud-lightgrey)](https://cloud.google.com/)

---

## 👨‍💻 About Me
I am a **Senior Data Scientist** with 6+ years of experience delivering AI/ML solutions across **financial services, insurance, and telecom**. Skilled in real-time anomaly detection, AML monitoring, and AI-driven risk scoring to enhance fraud prevention and compliance.  
Experienced in building scalable **data pipelines**, **ETL workflows**, and production **ML systems** using **Python, PySpark, SQL**, and cloud platforms (**AWS, Azure, GCP**).  
Adept at translating complex business problems into **data-driven solutions** that improve decision-making and operational efficiency.

---

## 🧬 Project 1: Cancer Detection

**Objective:**  
Identify metastatic cancer in histopathologic images using deep learning. Classify small image patches extracted from pathology scans as **cancerous** or **non-cancerous**.

**Models Developed:**
- **Custom CNN**
- **Pre-trained ResNet50**

**Key Outcomes:**
- Custom CNN achieved **~80% training accuracy** and **~75% validation accuracy**.
- ROC-AUC for Custom CNN: **0.5065**  
- ROC-AUC for ResNet50: **0.4640**

**Challenges:**  
- Models struggled to differentiate cancerous and non-cancerous tissue effectively.  
- Potential issues: class imbalance, data complexity, need for advanced architectures, and hyperparameter tuning.

**Conclusion:**  
The project highlights the complexity of histopathologic image classification. While CNN-based approaches show potential, further enhancements are required for reliable deployment.

---

## 🎨 Project 2: CGAN for Monet-style Painting Generation

**Objective:**  
Generate Monet-style paintings from real photos using a **CycleGAN** architecture.

**Dataset:**  
- Photos and Monet paintings, **256x256 RGB images**
- Unpaired examples

**Suggestions for Improvement:**
- Fine-tune hyperparameters (learning rates, epochs)
- Stabilize training using gradient penalty, instance normalization, or WGAN
- Monitor overfitting by balancing generator and discriminator

**Conclusion:**  
The Cycle GAN model learns to translate between photo and painting domains but shows training instability. Further tuning is needed for higher-quality generation.

---

## 📊 Project 3: Advanced Customer Segmentation & Predictive Analysis

**Objective:**  
Segment customers and predict **high-value customers** using the **Online Retail Dataset** (UK-based, Dec 2010–Dec 2011).

**Analysis Highlights:**
- Most customers purchase regularly (Recency ~111 days)
- Cluster 1 contains loyal customers with high Frequency & Monetary value
- Some customers are one-time visitors (guests)

**Model Performance:**
- **R² Score:** 1.0  
- **Mean Absolute Error (MAE):** 3.71e-10  
- **Mean Squared Error (MSE):** 1.70e-19  

**Conclusion:**  
Predictive models are highly accurate in identifying potential high-value customers, aiding targeted marketing and retention strategies.

---

## 💳 Project 4: Fraud Detection Model

**Objective:**  
Detect fraudulent financial transactions using historical transaction data.

**Features Used:**  
- Transaction amount, time, location, and other attributes  

**Outcome:**  
- Classifies transactions as **Fraud** or **Non-Fraud**  
- Enables **real-time fraud monitoring** and reduces financial losses

---

## ⚠️ Project 5: Anomaly Detection for Online Payment Data

**Objective:**  
Detect unusual patterns in online payment transactions to prevent potential financial risks.

**Approach:**  
- Applied statistical and ML-based anomaly detection methods
- Monitors deviations in payment amount, frequency, and location

**Outcome:**  
- Improves **risk management**
- Enables proactive investigation of suspicious transactions

---

## 🔧 Technologies & Tools

### Programming & Data Technologies
- **Languages & Libraries:** Python, R, PySpark, SQL, Pandas, NumPy, Scikit-learn, TensorFlow, Keras, Matplotlib, Seaborn  
- **Big Data & Pipelines:** Databricks, Hadoop, Spark, Shell Scripting, Airflow, Kafka, ETL Pipelines, Feature Engineering, Batch & Streaming Jobs  

### Cloud & DevOps
- AWS, Azure, GCP, Docker, Kubernetes, Git  

### Databases & Data Warehousing
- Oracle, SQL Server, PostgreSQL, MongoDB  

### Machine Learning
- Regression, Classification, Clustering, Time-Series Forecasting, Survival Analysis, Risk Scoring, Churn Prediction, Fraud Detection, Anomaly Detection  

### AI & Model Operations
- NLP (Text Classification, Entity Extraction)  
- AML Transaction Monitoring, Sanctions Screening  
- Experimentation System Design, A/B Testing, KPI Definition  
- ML Model Monitoring & Optimization, LLM API Integration  

### Business & Analytics Tools
- Tableau, Power BI, Business Intelligence Analytics, Dashboard Development  
- Data Literacy, Decision-Making Support  

### Financial Crime Compliance & Risk Analytics
- AML Transaction Monitoring Models, Sanctions Screening, KYC Remediation  
- FCC Regulatory Reporting, ISO 20022 / RTP Payment Fraud Models  

### Soft Skills & Core Competencies
- Problem-Solving, Defining & Moving Metrics, Statistical Modeling  
- Data-Driven Decision-Making, Cross-Functional Collaboration  
- Process Automation, Communication with Stakeholders


---

## 📄 License
This repository is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 📬 Contact
**Senior Data Scientist**  
- Email: [rammohanreddyds@gmail.com](mailto:rammohanreddyds@gmail.com)  
- GitHub: [https://github.com/ramkr2712/Rm_Analytics_K](https://github.com/ramkr2712/Rm_Analytics_K)
