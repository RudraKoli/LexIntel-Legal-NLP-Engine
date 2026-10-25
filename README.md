# ⚖️ LexIntel: Explainable Legal Document Classification & Key Information Extraction Suite

An enterprise-grade, modular Natural Language Processing (NLP) pipeline built to automate contract classification, key entity extraction, and compliance risk auditing with full Explainable AI (XAI) transparency.

## 🚀 Key Features
* **Module 1 (Ingestion & Chunker):** Dual-path PyMuPDF text parser and OCR fallback with clause-aware boundary segmentation to bypass 512-token Transformer limits.
* **Module 2 (Classification & XAI):** Dual-stage document and clause classification using fine-tuned **Legal-BERT**, complete with gradient-based token saliency heatmaps, counterfactual testing, and plain-English legal translations.
* **Module 3 (Key Information Extraction - KIE):** Hybrid extraction engine combining **RoBERTa-CUAD** extractive QA with deterministic regex to pull contracting parties, effective dates, governing law, and monetary/liability caps.
* **Module 4 (Compliance Risk Engine & UI):** Automated missing-clause risk audit and an interactive **Streamlit** dashboard supporting CSV/JSON report exports.

## 👥 4-Member Team Architecture
This project is engineered as an independent 4-person vertical module split:
1. **Data & Ingestion Lead:** Parser, OCR, and sliding-window legal chunker.
2. **Classification Lead:** Legal-BERT benchmarking and XAI saliency attribution.
3. **Extraction Lead:** CUAD-QA neural extraction and regex normalization.
4. **Systems & UI Lead:** FastAPI orchestration, Risk Compliance Engine, and Streamlit Dashboard.
