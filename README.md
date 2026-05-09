<p align="center">
  <img src="data1.png" width="100%"/>
</p>

# Hi 👋, I'm Sohel Ahmed

**Full-Stack Data Scientist | ML Engineer | Production Systems**  
📍 Michigan, USA | 8+ Years Building Production-Scale ML Systems  
![Profile Views](https://komarev.com/ghpvc/?username=sohel10)

---

## 🎯 About Me

I build **end-to-end production ML systems** that solve real business problems across healthcare, energy, and large-scale data platforms. From data ingestion to real-time deployment, I specialize in taking models from prototype to production at scale.

**Core Focus:**
- 🚀 Production ML deployment (FastAPI, Docker, AWS, CI/CD)
- ⚡ Real-time systems with sub-100ms latency
- 🏥 Healthcare AI & NLP applications
- 📊 Scalable data pipelines (100M+ records)
- 🌐 Cost-optimized cloud infrastructure

---

## 🌟 Featured Projects

### 1️⃣ ⚡ **Production ML Forecasting System** (Live Deployment)

**🌐 Live Demo:** https://energyforecastai.org/  
**📂 GitHub:** https://github.com/sohel10/energy-forecasting-ml-system

Deployed production ML system predicting electricity demand 24 hours ahead across 20 Michigan cities (9.8M population coverage).

**What I Built:**

| Component | Technology | Performance |
|-----------|-----------|-------------|
| **Data Ingestion** | OpenWeatherMap API (real-time) | 20 cities simultaneously |
| **Feature Engineering** | Temporal + lag features + rolling averages | Time-series optimized |
| **ML Model** | XGBoost with recursive forecasting | 85%+ accuracy, RMSE: 0.35 kWh |
| **API** | FastAPI REST endpoints | <100ms response time |
| **Deployment** | Docker + AWS EC2 + GitHub Actions | Automated CI/CD |
| **Monitoring** | PostgreSQL + Prometheus + Grafana | Real-time dashboards |
| **Infrastructure** | t2.micro cost-optimized | ~$12/month total |

**Key Achievements:**
✓ Handles 20 concurrent city forecasts with <100ms latency  
✓ Production-ready with health checks & automated deployments  
✓ Domain-aware constraints (non-negative predictions, baseline loads)  
✓ Extensible architecture (easily scales to other regions)  
✓ Comprehensive monitoring & observability  

**Business Impact:**
💰 Potential **$6-16M annual savings** for medium utilities through optimized grid capacity planning and reduced emergency power purchases (based on industry research)

**Technical Highlights:**
- Recursive forecasting for 24-hour predictions
- Real-time weather data integration
- Production-grade error handling & validation
- Cost-optimized deployment ($12/month vs $100s/month alternatives)

---

### 2️⃣ 🧠 **Clinical LLM Chatbot with RAG**  (Production System - LIVE)
## 🌐 Live Demo: https://clinicalenergyforecastai.org/
📂 GitHub: https://github.com/sohel10/clinicalnote-ai-mimic-iv

Production-grade Retrieval-Augmented Generation system analyzing 130M+ de-identified clinical 
notes using Bio_ClinicalBERT embeddings and LLaMA 3 for healthcare applications.

What I Built:

Component	Technology	Scale
Data Processing	PySpark distributed pipelines	130M+ clinical notes (MIMIC-IV)
Embeddings	Bio_ClinicalBERT + FAISS	951,725 vectors, medical domain optimized
RAG System	Vector search + LLM retrieval	<2.6s latency (242ms embed + 68ms retrieve + 2,312ms inference)
LLM Integration	LLaMA 3 with LangChain orchestration	Production inference with prompt optimization
Monitoring	Prometheus + Grafana	Real-time latency & performance tracking
Deployment	Docker + AWS EC2	Automated CI/CD, health checks
Governance	HIPAA-aware architecture	Access controls, audit trails, compliance-ready

Key Achievements:
✓ 951,725 FAISS vectors from 130M+ clinical documents
✓ Bio_ClinicalBERT for biomedical domain specificity
✓ Sub-3-second end-to-end response latency
✓ Production LLMOps with Prometheus/Grafana monitoring
✓ Governance-aware design for healthcare compliance
✓ Live, testable product (not just prototype)

Technical Highlights:

Clinical BERT embeddings for medical terminology
FAISS vector database optimized for fast retrieval
Distributed PySpark processing for 130M+ records
LangChain multi-turn conversation management
Confidence scoring & retrieval evaluation
Production monitoring for model drift & quality assurance

Business Impact:
🏥 Enables faster clinical decision support and knowledge retrieval for healthcare professionals
🏥 Demonstrates ability to ship production GenAI systems with full LLMOps
**Technical Highlights:**
- Clinical BERT embeddings for medical terminology
- FAISS vector database for fast retrieval
- Distributed processing for 130M+ records
- Prompt engineering for clinical accuracy
- Monitoring for model drift & quality assurance

**Business Impact:**
🏥 Enables faster clinical decision support and knowledge retrieval for healthcare professionals

---

## 📊 Additional Projects

### 🔹 NYC Spark Lakehouse ML Pipeline
- Engineered pipeline processing **100M+ NYC taxi records**
- Reduced processing time by **60%** using distributed computing
- Built end-to-end system with Airflow, FastAPI, PostgreSQL
- Deployed using Docker + AWS + CI/CD pipelines

### 🔹 YOLOv8 Vision AI System (Object Detection + OCR)
- Real-time detection system using YOLOv8 + EasyOCR
- Built FastAPI service with low-latency inference (<300ms)
- Implemented monitoring using Prometheus + Grafana
- Deployed on AWS with production-ready architecture

---

## 🛠️ Tech Stack

**Languages:** Python, SQL, R, SAS  
**ML/Deep Learning:** XGBoost, PyTorch, TensorFlow, LLMs, RAG, ClinicalBERT  
**Big Data & Distributed Computing:** PySpark, Hadoop, Spark SQL  
**Backend & APIs:** FastAPI, REST APIs, async Python  
**MLOps & DevOps:** Docker, GitHub Actions, CI/CD pipelines, MLflow  
**Cloud Infrastructure:** AWS (EC2, S3, ECR, RDS)  
**Monitoring & Observability:** Prometheus, Grafana, logging  
**Databases:** PostgreSQL, FAISS vector database  

---

## 🎯 What I Specialize In

| Area | Focus |
|------|-------|
| **Production ML** | End-to-end systems from data → model → API → monitoring |
| **Real-Time Systems** | Sub-100ms latency inference & forecasting |
| **Scalability** | 100M+ record processing with distributed computing |
| **Healthcare AI** | Clinical NLP, RAG systems, domain-aware models |
| **Cloud Deployment** | AWS, Docker, automated CI/CD pipelines |
| **Cost Optimization** | Enterprise-grade systems at startup costs |

---

## 📈 Key Metrics

- **Production Systems Deployed:** 3+ live systems in healthcare & energy
- **Data Scale Processed:** 130M+ records (clinical) + 100M+ records (taxi)
- **API Performance:** <100ms latency (forecasting), 1.3-4.0s (RAG + retrieval)
- **Cost Efficiency:** Production systems at ~$12-50/month on AWS
- **Accuracy:** 85%+ (energy forecasting), domain-optimized (clinical)

---

## 🚀 Recent Deployments

✅ **Energy Forecasting System** — Live at energyforecastai.org  
✅ **Clinical LLM Chatbot** — Production RAG system  
✅ **Monitoring & Observability** — Prometheus + Grafana dashboards  

---

## 📚 Approach to Problem-Solving

1. **Understand the Problem** → Business context, constraints, metrics
2. **Design the Solution** → Architecture-first thinking
3. **Build MVP** → Prototype quickly, iterate
4. **Scale to Production** → Docker, monitoring, CI/CD
5. **Measure Impact** → Business metrics & technical performance

**The domain changes. The approach doesn't.**

---

## 📫 Connect With Me

🔗 **LinkedIn:** https://www.linkedin.com/in/sohelcu06/  
💻 **GitHub:** https://github.com/sohel10  
🌐 **Portfolio:** https://energyforecastai.org/  

---

## 💡 Open To

- **Full-time roles:** ML Engineer, Data Scientist, Production ML roles
- **Focus areas:** Healthcare AI, Time-series forecasting, LLM systems, MLOps
- **Remote/Hybrid:** Flexible arrangements

---

<p align="center">
  ⭐ If you find my work interesting, feel free to star my repositories!
</p>
