# NEXACORE: AI Clinical Decision Support System (CDSS)

![Domain](https://img.shields.io/badge/Domain-Oncology-blue)
![AI](https://img.shields.io/badge/AI-Explainable%20(XAI)-orange)
![ Compliance](https://img.shields.io/badge/Standard-HL7%20FHIR-green)

## 🏥 Project Mission
An AI-driven interface for Oncologists to validate diagnoses and assess risk factors based on multi-modal data (Genetics + Clinical History).

### 🎥 Demo Walkthrough
The video demonstrates the **"Active Learning"** workflow:
1.  **Complex Data Ingestion:** System accepts TNM Staging, Molecular Profiles (EGFR, PD-L1), and Host Factors.
2.  **Explainable AI (XAI):**
    * Unlike "Black Box" models, NEXACORE breaks down the risk score (99.0%) into specific contributors (e.g., *Metastatic Volume: +50%*).
3.  **RLHF Loop (Reinforcement Learning from Human Feedback):**
    * The **"Teach the AI"** module allows senior doctors to correct the model's verdict, creating a continuous improvement cycle.

## 🧠 Architecture
* **Orchestration:** Python-based Agentic Swarm (Medical Specialist Agents).
* **Knowledge Base:** RAG (Retrieval-Augmented Generation) over 1M+ medical protocols.
* **Security:** AES-256 encryption for Patient Data (PII).

> *Note: This is a UI/UX demonstration of the internal CDSS algorithm.*
