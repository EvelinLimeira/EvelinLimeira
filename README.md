# Evelin Limeira

**Software Engineer & Cybersecurity Researcher** — building ML-based intrusion detection for medical IoT networks, and RAG-based intelligent systems for the public sector.

MSc Candidate in Software Engineering · Cybersecurity Researcher at CISSA · Systems Developer at Assembleia Legislativa da Paraíba (ALPB) · João Pessoa, Brazil

[LinkedIn](https://www.linkedin.com/in/evelin-limeira) · [ResearchGate](https://www.researchgate.net/profile/Evelin-Limeira-2) · [Email](mailto:evelinlena@gmail.com)

## Currently

- Finishing my MSc dissertation on per-device autoencoder anomaly detection for IoMT (Internet of Medical Things) networks
- Building DeviceShield-IoMT, a hybrid intrusion-detection framework, with the CISSA cybersecurity research group
- Developing REGI, a RAG-based legal assistant for the Paraíba State Legislature

## Publications

**Beyond Aggregate Accuracy: Kill Chain-Aware Evaluation of IoMT Intrusion Detection Models**
E. E. D. Limeira, R. Roque, L. Cabral, F. Aires, W. R. M. Santos, M. Lima, J. A. Suruagy
*Anais do Simpósio Brasileiro de Cibersegurança (SBSeg)*, 2026 · [DOI: 10.5753/sbseg.2026.27104](https://doi.org/10.5753/sbseg.2026.27104)
Kill chain-aware analysis of Random Forest, LightGBM, a 1D-CNN, and an autoencoder across 18 attack categories on the CICIoMT2024 dataset, showing that aggregate accuracy conceals failures in detecting early-stage attack behaviors.

**Per-Device Behavioral Anomaly Detection in IoMT Networks Using Autoencoders and EVT-Based Adaptive Thresholds**
E. E. D. Limeira, R. Roque, L. Cabral, F. Aires, W. R. M. Santos, M. Lima
*Anais do Simpósio Brasileiro de Cibersegurança (SBSeg)*, 2026, pp. 913–928 · [DOI: 10.5753/sbseg.2026.27109](https://doi.org/10.5753/sbseg.2026.27109)
Per-device autoencoders (one per medical camera), calibrated with EVT-based and per-feature reconstruction-error thresholds, outperform a single pooled/global model on behavioral protocol attacks — mean detection rate 0.945 vs. 0.681 under LRE, and 0.836 vs. 0.524 under EVT.

Full list on [ResearchGate](https://www.researchgate.net/profile/Evelin-Limeira-2).

## Research Projects — Cybersecurity / IoMT

**DeviceShield-IoMT** *(MSc dissertation, work in progress · private repository)*
Hybrid intrusion-detection framework combining benign-only autoencoders trained per device/species with global supervised classifiers (Random Forest, XGBoost, CNN, Transformer) and EVT statistical calibration. Evaluated with Leave-One-Attack-Out and Leave-One-Group-Out protocols across four public IoMT datasets (CICIoMT2024, N-BaIoT, MedSec-25, MedBIoT).
`Python` · `TensorFlow/Keras` · `scikit-learn` · `EVT` · `SHAP`

**LLM-based IDS Benchmark** *(private repository)*
Companion study benchmarking seven quantized open-source LLMs — general-purpose vs. cybersecurity-specialized — as intrusion detectors on IoMT network flows against the DeviceShield-IoMT baselines, controlling for base model vs. domain-specialized pretraining, with latency and explainability as first-class results.
`Python` · `llama.cpp` · `GGUF` · local LLM inference

## Selected Work — Public Sector Systems

**REGI — Regimento Eletrônico de Gestão Inteligente**
RAG-based legal assistant that answers natural-language questions across multiple legal sources at once — the Legislature's internal rulebook, the State Constitution, and the Federal Constitution. Combines ChromaDB semantic search with BM25 keyword search via Reciprocal Rank Fusion, routes each query to the most relevant source, and returns answers with structured inline citations (`[Source: Name, Art. N]`). Served through a local LLM (Gemma via Ollama) behind a Gradio interface.
`Python` · `RAG` · `ChromaDB` · `BM25` · `Ollama` · `Gradio`
*Internal system — Assembleia Legislativa da Paraíba*

**Painel / Comissão Virtual**
Real-time virtual committee and voting panel for legislative sessions, with WebSocket-based live updates, an OAuth2 authorization server, and automated generation of session documents (PDF/DOCX).
`Java` · `Spring Boot` · `PostgreSQL` · `Angular` · `WebSocket/STOMP` · `OAuth2`
*Internal system — Assembleia Legislativa da Paraíba*

## Other Projects

**[RAG TriviaQA Pipeline](https://github.com/EvelinLimeira/rag-triviaqa-pipeline)**
End-to-end RAG pipeline benchmarking BM25, dense (FAISS), and hybrid retrieval with cross-encoder reranking. Evaluated with an LLM-judge (via deepeval) for correctness, faithfulness, and answer relevancy, alongside classic IR metrics (Hit Rate@k, MRR).
`Python` · `LangChain` · `FAISS` · `BM25` · `deepeval` · `Ollama`

**[Sentiment Analysis on Product Reviews](https://github.com/EvelinLimeira/sentiment-analysis-product-reviews)**
Comparative NLP study of four sentiment-classification approaches — SVM+TF-IDF, SVM+embeddings, fine-tuned DistilBERT, and few-shot in-context learning — validated across 10 runs with different random seeds and statistical significance testing (Wilcoxon, Kruskal-Wallis).
`Python` · `PyTorch` · `Transformers` · `scikit-learn`

**[Comparative Study: Detectron2 vs. Gemini](https://github.com/EvelinLimeira/estudo-comparativo-detectron-gemini)** *(team project)*
Study comparing a traditional object-detection model (Detectron2-ResNet18) against a multimodal LLM (Gemini 2.0-flash) on a binary image-classification task, with statistical validation (Wilcoxon test) over 24 paired simulations.
`Computer Vision` · `Detectron2` · `Gemini`

## Skills

- **Languages** — Python, Java, TypeScript, SQL
- **Cybersecurity / IDS** — Autoencoders, Extreme Value Theory (EVT), SHAP/LIME explainability, Random Forest, XGBoost, CNN/Transformer classifiers, CICIoMT2024/N-BaIoT/MedBIoT datasets
- **ML / NLP** — RAG pipelines, LangChain, Hugging Face Transformers, PyTorch, scikit-learn, LLM evaluation (deepeval)
- **Backend** — Spring Boot, PostgreSQL, WebSocket/STOMP, OAuth2
- **Frontend** — Angular, TypeScript, Tailwind CSS
- **Tools** — Docker, Git, ChromaDB, FAISS, Ollama, llama.cpp

## Connect

- LinkedIn — [evelin-limeira](https://www.linkedin.com/in/evelin-limeira)
- ResearchGate — [Evelin-Limeira-2](https://www.researchgate.net/profile/Evelin-Limeira-2)
- Email — [evelinlena@gmail.com](mailto:evelinlena@gmail.com)
