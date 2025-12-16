# Aqura AI Platform 🌱🤖

Aqura is an **AI-powered, voice-first aquaponics platform** designed to address **water scarcity, food security, and community empowerment** in Tunisia.
This repository serves as the **main monorepo** that brings together all AI, speech, RAG, and service components described in the project documentation.

The system combines **Agentic RAG**, **Tunisian dialect STT/TTS**, **mobile interfaces**, and **AI microservices** to deliver an accessible, culturally adapted, and scalable solution for non-technical users.

---

## 🌍 Project Vision

Aqura aims to democratize advanced AI and IoT technologies for **rural communities, women cooperatives, youth, and schools** by:

* Reducing water usage by **up to 90%** through intelligent aquaponics
* Providing **voice-based interaction in Tunisian dialect**
* Enabling **AI-guided decision making** via Agentic RAG
* Supporting **food security, income generation, and climate resilience**

Technology is designed to **support people, not replace them**.

---

## 🧠 Core Capabilities

* 🎙️ **Speech-to-Text (STT)** in Tunisian Arabic
* 🔊 **Text-to-Speech (TTS)** with natural Tunisian voices
* 🤖 **Agentic RAG** for contextual, actionable AI assistance
* 🧩 **AI Microservices** architecture (LLM, speech, orchestration)
* 📱 **Mobile-first & voice-first design** for inclusivity

---

## 📂 Repository Structure

```text
.
├── mobile_dev/        # Mobile application (Flutter)
├── STT/               # Tunisian Speech-To-Text service
├── TTS/               # Tunisian Text-To-Speech service
├── Agentic_rag/       # Agentic RAG pipelines & orchestration
├── AI_services/       # Core AI microservices & APIs
└── README.md          # This file
```

Each folder contains (or will contain) an independent service or application, developed and versioned separately, but designed to work together.

---

## 🔗 Integrated Repositories

This monorepo integrates the following existing projects:

### 🧠 Agentic RAG

**Repository:** `Tunisian_Agentic_RAG`

* Agent-based Retrieval-Augmented Generation
* Context-aware decision support for aquaponics
* Tool-using AI agents (querying data, rules, knowledge base)
* Designed for **agriculture & aquaponics domain knowledge**

Used for:

* System diagnostics explanations
* Action recommendations
* Educational guidance via conversational AI

---

### 🎙️ Tunisian STT

**Repository:** `Tunisian_STT`

* Speech-to-Text optimized for **Tunisian dialect**
* Based on fine-tuned Whisper models
* Low-latency inference suitable for real-time interaction

Used for:

* Voice commands ("Chnouwa el situation?")
* Hands-free system control
* Accessibility for illiterate users

---

### 🔊 Tunisian TTS

**Repository:** `Tunisian_TTS`

* Natural-sounding Tunisian Arabic Text-to-Speech
* Supports conversational responses and alerts
* Compatible with avatar lip-sync and animations

Used for:

* Spoken AI feedback
* Urgent alerts & notifications
* Voice-guided learning and assistance

---

## 📱 Mobile Application (`mobile_dev/`)

The mobile application is the **primary user interface** for Aqura.

Key features:

* Voice-first interaction (STT ↔ LLM ↔ TTS)
* Simple dashboards (color-coded health status)
* Animated speaking avatar ("Sami")
* Offline-first support for rural areas
* Community learning & notifications

Target users:

* Rural households
* Women cooperatives
* Youth & schools
* Elderly or low-literacy users

---

## 🧩 AI Services (`AI_services/`)

This folder hosts shared and backend AI components, including:

* LLM APIs
* Speech service orchestration
* Agent routing logic
* Integration with IoT, digital twin, and cloud services

Architecture principles:

* Microservices-based
* Containerized (Docker / Kubernetes-ready)
* Scalable & fault-tolerant

---

## ⚙️ High-Level Architecture

```text
User (Voice)
   ↓
STT (Tunisian)
   ↓
Agentic RAG (LLM + Tools)
   ↓
AI Services (Decision Logic)
   ↓
TTS (Tunisian)
   ↓
User (Voice + Mobile UI)
```

This pipeline enables **natural, contextual, and explainable AI interaction**.

---

## 🌱 Social & Environmental Impact

* 💧 **90% water savings** compared to traditional farming
* 🍅 Year-round local food production
* 👩‍🌾 Economic empowerment for women & youth
* 🗣️ Language inclusion via Tunisian dialect
* 🌍 Climate-resilient, low-carbon agriculture

---

## 🚀 Getting Started (High Level)

```bash
# Clone the monorepo
git clone https://github.com/AhmedBensalah8603/aqura-ai-platform.git
cd aqura-ai-platform

# Each folder can be run independently
cd STT
# or
cd TTS
# or
cd Agentic_rag
```

Detailed setup instructions are provided inside each subproject.

---

## 🧪 Development Philosophy

* Modular & composable services
* Explainable AI over black-box decisions
* Voice-first accessibility
* Community-centered design
* Open, extensible architecture

---

## 📌 Status

This project is under **active development** as part of an academic, research, and humanitarian initiative.

Planned next steps:

* Full service orchestration
* Digital Twin integration
* Cloud deployment (Azure / AKS)
* CI/CD automation

---

## 👤 Author

**Ahmed Bensalah**
AI & Data Engineering | Sustainable Tech | Agentic AI

---

## 📜 License

License to be defined (Academic / Open Innovation friendly).

---

> *Aqura is not just a technical system — it is a model for how AI can empower communities while respecting culture, language, and the environment.* 🌍✨
