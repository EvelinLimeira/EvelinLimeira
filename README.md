# Evelin Limeira

Software engineer and cybersecurity researcher based in João Pessoa, Brazil. Finishing an MSc in Software Engineering at Cesar School, researching intrusion detection for medical IoT networks and working as a researcher on a threat-intelligence data project with CISSA, and building systems for the Paraíba State Legislature (ALPB) day to day.

[LinkedIn](https://www.linkedin.com/in/evelin-limeira) · [ResearchGate](https://www.researchgate.net/profile/Evelin-Limeira-2) · [Lattes](http://lattes.cnpq.br/8347885521421671) · [Email](mailto:evelinlena@gmail.com)

## Education

- MSc in Software Engineering — Cesar School (2025–present)
- Specialization in Artificial Intelligence and Machine Learning — PUC Minas (2023–2024)
- BSc in Systems Analysis and Development — UNINASSAU (2021–2022)
- Bachelor of Laws — Universidade Federal da Paraíba (2006–2010)

## Publications

Two papers accepted at [SBSeg 2026](https://sol.sbc.org.br/index.php/sbseg/issue/view/1728) (Brazilian Symposium on Cybersecurity), both on IoMT intrusion detection. Full list on [ResearchGate](https://www.researchgate.net/profile/Evelin-Limeira-2). The experiments behind them:

**Per-device autoencoder anomaly detection** — one autoencoder per device instead of a single pooled model, thresholds calibrated with Extreme Value Theory and per-feature reconstruction error. Beats the pooled baseline on behavioral protocol attacks: 0.945 vs. 0.681 mean detection rate. Private repo.
`Python` `TensorFlow` `EVT`

**Kill chain-aware IDS evaluation** — compared Random Forest, LightGBM, a 1D-CNN, and an autoencoder across 18 attack categories, checking detection at each stage of the attack lifecycle instead of one aggregate score. Private repo.
`Python` `scikit-learn` `LightGBM` `SHAP` `LIME`

## Cybersecurity research

**Hybrid IDS for IoMT** (work in progress) — instead of one global model, an autoencoder is trained per device to catch anomalies, backed by a supervised classifier and EVT-based thresholds. Tested with leave-one-attack-out and leave-one-group-out splits across four IoMT datasets. Private repo.
`Python` `TensorFlow` `scikit-learn` `EVT` `SHAP`

**LLM-based IDS benchmark** — a side study on whether general-purpose LLMs can hold up against security-tuned ones at spotting IoMT attacks from raw traffic, run locally on quantized models. Private repo.
`Python` `llama.cpp` `GGUF`

**Xeque-Mate Agregador** — funded research project at CESAR (CISSA/EMBRAPII): an intelligent aggregator that collects, cleans, and semantically enriches cybersecurity data (logs, alerts, IoCs, threat-intel reports) into high-quality datasets for LLMs, aimed at better threat detection and response in SOCs.

## Work at ALPB

Legislative Technical Advisor since 2014; working in a software engineering capacity since 2023.

**REGI** — a RAG assistant that answers questions about the Legislature's internal rules and the state/federal constitutions at once. Hybrid search over ChromaDB and BM25, every answer cited back to the article it came from, running on a local model through Ollama.
`Python` `RAG` `ChromaDB` `BM25` `Ollama` `Gradio`

**Painel / Comissão Virtual** — the real-time panel used to run virtual committee sessions and votes: WebSocket updates, OAuth2 login, session documents generated automatically.
`Java` `Spring Boot` `PostgreSQL` `Angular` `WebSocket/STOMP` `OAuth2`

Both are internal systems built for the Assembleia Legislativa da Paraíba.

## Other projects

**[RAG TriviaQA pipeline](https://github.com/EvelinLimeira/rag-triviaqa-pipeline)** — BM25, dense, and hybrid retrieval with reranking, graded by an LLM judge instead of relying on IR metrics alone.
`Python` `LangChain` `FAISS` `deepeval`

**[Sentiment analysis on product reviews](https://github.com/EvelinLimeira/sentiment-analysis-product-reviews)** — four approaches to the same classification problem, from SVM+TF-IDF up to a fine-tuned DistilBERT, checked for statistical significance across 10 runs.
`Python` `PyTorch` `Transformers` `scikit-learn`

**[Detectron2 vs. Gemini](https://github.com/EvelinLimeira/estudo-comparativo-detectron-gemini)** (team project) — Detectron2-ResNet18 against Gemini 2.0-flash on the same image classification task. Gemini won on accuracy, Detectron won on latency.
`Computer Vision` `Detectron2` `Gemini`

## Skills

Python, Java, TypeScript, SQL
Autoencoders, EVT, SHAP/LIME, Random Forest, XGBoost, CNNs, Transformers
RAG, LangChain, Hugging Face Transformers, PyTorch, scikit-learn, deepeval
Spring Boot, PostgreSQL, WebSocket/STOMP, OAuth2
Angular, Tailwind CSS
Docker, Git, ChromaDB, FAISS, Ollama, llama.cpp

## Contact

- LinkedIn: [evelin-limeira](https://www.linkedin.com/in/evelin-limeira)
- ResearchGate: [Evelin-Limeira-2](https://www.researchgate.net/profile/Evelin-Limeira-2)
- Lattes: [8347885521421671](http://lattes.cnpq.br/8347885521421671)
- Email: [evelinlena@gmail.com](mailto:evelinlena@gmail.com)
