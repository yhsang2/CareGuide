# CareGuide – Medical Triage PoC

CareGuide is an **explainable, rule-based medical triage service** designed to guide users to the appropriate medical department based on self-reported symptoms.

This project intentionally **does NOT provide medical diagnosis or treatment**.  
It focuses on **triage, safety, explainability, and regulatory readiness**, making it suitable for hospital PoCs, internal ventures, and early-stage validation.

---

## ✨ Key Features

- 🩺 **Rule-based Medical Triage**
  - Explicit, auditable clinical rules
  - Clear separation of medical logic and API orchestration

- ⚖️ **Rule Weight & Confidence Score**
  - Each rule has a clinical risk weight
  - Heuristic confidence score (0–1), **not a diagnostic probability**
  - Human-readable confidence labels: `High / Medium / Low`

- 🔍 **Explainability by Design**
  - Keyword matching evidence included in responses
  - Rule ID exposed for auditing and medical review
  - Candidate rules list available for clinician view

- 📚 **PubMed RAG Integration (PoC)**
  - Returns relevant medical literature references
  - Links directly to PubMed search results

- 📱 **Mobile-first UI**
  - Optimized for iOS WebView / mobile browsers
  - Patient mode / Clinician mode separation

- 🛡️ **Medical & Legal Safety**
  - No diagnosis or prescription
  - Clear medical disclaimers
  - Rule-first architecture (AI is optional and controlled)

---

## 🧠 Why Rule-Based First?

Hospitals and medical institutions strongly prefer systems that are:

- Explainable
- Auditable
- Deterministic
- Legally defensible

CareGuide intentionally starts with a **Rule-based Triage Engine**, with AI models positioned as **optional assistants**, not decision-makers.

---

## 🏗️ Architecture Overview

