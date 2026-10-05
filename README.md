# Om Dangol

**AI Undergraduate | GenAI, Knowledge Systems & Software Engineering**  
Kathmandu, Nepal • [LinkedIn](https://www.linkedin.com/in/om-dangol-0a39243a7/) • [Email](mailto:omdangol68@gmail.com) • [GitHub](https://github.com/omwe77)

---

## Profile

Undergraduate student pursuing a **BSc (Hons) in Computing with Artificial Intelligence** at **Islington College** (affiliated with London Metropolitan University). 

Focused on building practical, grounded AI and software systems—specifically **Large Language Model (LLM) applications**, **document understanding engines**, and **structured knowledge representation**. Practical experience across Python backend architectures, local model orchestration, bilingual NLP/OCR pipelines, object-oriented Java systems, and deterministic web simulation engines.

---

## Technical Competencies

- **Languages:** Python, Java, JavaScript (ES6+), TypeScript, HTML5/CSS3, SQL
- **GenAI & Knowledge Systems:** Local LLM Inference (Ollama), Open Knowledge Format (OKF v0.2), Dense Vector Retrieval (FAISS, `sentence-transformers`), Prompt Security (Injection Defense & Delimitation), Grounding & Contradiction Verification
- **Document AI & NLP:** Tesseract OCR (Devanagari & English), PyMuPDF (fitz), pdfplumber, Text Chunking & Normalization, scikit-learn
- **Backend & Web Engineering:** FastAPI, Next.js, React, Uvicorn, RESTful API Design, Node.js, Java Swing & AWT, Vanilla Web Standards
- **Testing & Tooling:** Pytest (TDD), Playwright E2E, Vite, Git, Linux/Bash, Microsoft Azure

---

## Flagship Project

### [hamiGenZ — Nepal-Focused AI Document Understanding Platform](https://github.com/omwe77/hamiGenz)
*Python 3.12, FastAPI, Ollama (qwen3:8b), FAISS, Tesseract OCR, Next.js 16, TypeScript, React 19*

A local-first, offline-capable AI document-understanding platform engineered to help citizens navigate complex Nepali administrative forms, citizenship certificates, and government gazettes without cloud document leakage.
- **Structured Knowledge Layer:** Implements the **Open Knowledge Format (OKF v0.2)** to maintain a versioned, machine-validated concept graph for Nepali civil procedures rather than relying solely on naive chunk similarity.
- **Trilingual Ingestion & OCR:** Ingests PDFs and degraded scans using dual-engine Tesseract OCR (with dedicated Devanagari `nep` models) and PyMuPDF, dynamically selecting between Nepali and bilingual OCR modes.
- **Multilingual Grounding:** Employs `paraphrase-multilingual-MiniLM-L12-v2` dense vectors in FAISS paired with a deterministic prompt-injection sanitizer and post-inference contradiction verification layer.
- **Production Testing:** Backed by **282 passing regression and pipeline tests** and an interactive split-screen Next.js 16 workspace with live citation highlighting.

---

## Selected Systems & Engineering Projects

### [ARENA_CORE — Deterministic Football Simulation Engine](https://github.com/omwe77/Arena_Core)
*Vanilla JavaScript, Mulberry32 PRNG, WebAudio API, Vite, Playwright, Azure Static Web Apps*
- Built a high-performance single-page sports simulation engine covering 13 major football competitions with zero runtime framework dependencies.
- Implemented a mathematical **Poisson goal-distribution model** paired with a seeded **Mulberry32 PRNG** for strictly deterministic, reproducible tournament simulations.
- Developed an interactive 2D pitch visualizer, custom 48-team World Cup bracket generator, procedural WebAudio sound synthesizer, and complete **Playwright E2E test suite**. Deployed live on Azure.

### [AI Subscription Management System](https://github.com/omwe77/ai-subscription-management-system)
*Java (JDK 17+), Java Swing, Object-Oriented Architecture, File I/O*
- Designed and built a standalone desktop application simulating AI subscription plan tiers and prompt token quota management.
- Implemented object-oriented class hierarchies utilizing abstract base classes (`AIModel`), concrete polymorphic extensions (`PersonalPlan`, `ProPlan`), bounded team seat arrays, and transaction persistence.

---

## Academic Research

### Collaborative Research in Multilingual LLM Evaluation
*Islington College / London Metropolitan University (Academic Research)*
- Participated in comparative evaluation of lightweight open-weights LLMs (including Gemma 3 1B) across domain-specific Nepali datasets (Constitution & Law, civil procedures, socio-cultural texts).
- Investigated hallucination frequency and factual verification performance on multilingual benchmarks (HalluVerse and Poly-FEVER QA datasets).

---

## Additional Coursework & Explorations

- **[MedStore Pharmacy Inventory System](https://github.com/omwe77/pharmacy-inventory-management-system):** Modular Python CLI system with transactional integrity, inventory synchronization, and formatted text invoice generation.
- **[EcoMart Responsive Web Prototype](https://github.com/omwe77/eco-friendly-awareness-mart-website):** Multi-page responsive static e-commerce prototype with client-side cart state management and design wireframes.
- **[Spam Email Classifier](https://github.com/omwe77/spam-email-classifier):** Introductory NLP experiment demonstrating text vectorization (`CountVectorizer`) and probabilistic Naive Bayes classification.

---

## Current Learning & Focus

- Advancing evaluation methodologies for agentic workflows (tool use, multi-step reasoning, plan-verification loops).
- Scaling local inference latency optimization (quantization, vLLM / llama.cpp backends).
- Expanding Open Knowledge Format schemas for complex public-policy and regulatory documents.

---

## Contact

- **Email:** [omdangol68@gmail.com](mailto:omdangol68@gmail.com)
- **LinkedIn:** [linkedin.com/in/om-dangol-0a39243a7](https://www.linkedin.com/in/om-dangol-0a39243a7/)
- **GitHub:** [github.com/omwe77](https://github.com/omwe77)
