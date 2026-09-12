# Evelin Limeira

Software engineer and cybersecurity researcher based in João Pessoa, Brazil. Finishing an MSc in Software Engineering at Cesar School, on intrusion detection for medical IoT networks. Also a researcher on a threat-intelligence data project with CISSA. Day-to-day work is building systems for the Paraíba State Legislature (ALPB).

[LinkedIn](https://www.linkedin.com/in/evelin-limeira) · [ResearchGate](https://www.researchgate.net/profile/Evelin-Limeira-2) · [Lattes](http://lattes.cnpq.br/8347885521421671) · [Email](mailto:evelinlena@gmail.com)

## Education

- MSc in Software Engineering, Cesar School (2025–present)
- Specialization in Artificial Intelligence and Machine Learning, PUC Minas (2023–2024)
- BSc in Systems Analysis and Development, UNINASSAU (2021–2022)
- Bachelor of Laws, Universidade Federal da Paraíba (2006–2010)

## Publications

Two papers accepted at [SBSeg 2026](https://sol.sbc.org.br/index.php/sbseg/issue/view/1728) (Brazilian Symposium on Cybersecurity), both on IoMT intrusion detection. Full list on [ResearchGate](https://www.researchgate.net/profile/Evelin-Limeira-2). The experiments behind them (repos are private):

**Per-device autoencoder anomaly detection** trains one autoencoder per device instead of a single pooled model, with thresholds calibrated using Extreme Value Theory and per-feature reconstruction error. Beats the pooled baseline on behavioral protocol attacks: 0.945 vs. 0.681 mean detection rate.
`Python` `TensorFlow` `EVT`

**Kill chain-aware IDS evaluation** compares Random Forest, LightGBM, a 1D-CNN, and an autoencoder across 18 attack categories, checking detection at each stage of the attack lifecycle instead of one aggregate score.
`Python` `scikit-learn` `LightGBM` `SHAP` `LIME`

## Cybersecurity research

Also private repos unless a link is given.

**Hybrid IDS for IoMT** (work in progress) uses one autoencoder per device rather than one global model, backed by a supervised classifier and EVT-based thresholds. Tested with leave-one-attack-out and leave-one-group-out splits across four IoMT datasets.
`Python` `TensorFlow` `scikit-learn` `EVT` `SHAP`

**LLM-based IDS benchmark** is a side study on whether general-purpose LLMs can hold up against security-tuned ones at spotting IoMT attacks from raw traffic, run locally on quantized models.
`Python` `llama.cpp` `GGUF`

**Xeque-Mate Agregador** is a funded research project at CESAR (CISSA/EMBRAPII): an aggregator that pulls in cybersecurity data (logs, alerts, IoCs, threat-intel reports), cleans it, and enriches it semantically to build training datasets for LLMs used in SOC threat detection.

## Work at ALPB

Legislative Technical Advisor since 2014, doing software engineering there since 2023.

**REGI** is a RAG assistant that answers questions about the Legislature's internal rules and the state/federal constitutions at once. Hybrid search over ChromaDB and BM25, every answer cited back to the article it came from, running on a local model through Ollama.
`Python` `RAG` `ChromaDB` `BM25` `Ollama` `Gradio`

**Painel / Comissão Virtual** is the real-time panel used to run virtual committee sessions and votes: WebSocket updates, OAuth2 login, session documents generated automatically.
`Java` `Spring Boot` `PostgreSQL` `Angular` `WebSocket/STOMP` `OAuth2`

Both are internal systems; no public repos.

## Other projects

**[RAG TriviaQA pipeline](https://github.com/EvelinLimeira/rag-triviaqa-pipeline)** uses BM25, dense, and hybrid retrieval with reranking, graded by an LLM judge rather than IR metrics alone.
`Python` `LangChain` `FAISS` `deepeval`

**[Sentiment analysis on product reviews](https://github.com/EvelinLimeira/sentiment-analysis-product-reviews)** compares four approaches to the same classification problem, from SVM+TF-IDF up to a fine-tuned DistilBERT, checked for statistical significance across 10 runs.
`Python` `PyTorch` `Transformers` `scikit-learn`

**[Detectron2 vs. Gemini](https://github.com/EvelinLimeira/estudo-comparativo-detectron-gemini)** (team project). Detectron2-ResNet18 against Gemini 2.0-flash on the same image classification task. Gemini won on accuracy, Detectron won on latency.
`Computer Vision` `Detectron2` `Gemini`

## Skills

Python, Java, TypeScript, SQL

Cyber Threat Intelligence, Autoencoders, EVT, SHAP/LIME, Random Forest, XGBoost, CNNs, Transformers

RAG, LangChain, Hugging Face Transformers, PyTorch, scikit-learn, deepeval

Spring Boot, PostgreSQL, WebSocket/STOMP, OAuth2

Angular, Tailwind CSS

Docker, Git, ChromaDB, FAISS, Ollama, llama.cpp

## Contact

- LinkedIn: [evelin-limeira](https://www.linkedin.com/in/evelin-limeira)
- ResearchGate: [Evelin-Limeira-2](https://www.researchgate.net/profile/Evelin-Limeira-2)
- Lattes: [8347885521421671](http://lattes.cnpq.br/8347885521421671)
- Email: [evelinlena@gmail.com](mailto:evelinlena@gmail.com)
