# Evelin Limeira

Cybersecurity and trustworthy AI researcher working on machine-learning systems under heterogeneous, adversarial, and previously unseen conditions.

I am completing an MSc in Software Engineering at CESAR School, where my research focuses on intrusion and behavioral anomaly detection for Internet of Medical Things (IoMT) networks. I also investigate reliability and failure modes of local LLMs for security applications.

My work combines machine learning, cybersecurity, statistical evaluation, and reproducible experimentation. I am particularly interested in robust and trustworthy learning systems, distributed AI, and model behavior under distribution shift and adversarial conditions.
Software engineer and cybersecurity researcher based in João Pessoa, Brazil. Finishing an MSc in Software Engineering at Cesar School, on intrusion detection for medical IoT networks. Also a researcher on a threat-intelligence data project with CISSA, Embrapii-certified Cybersecurity Competence Center. Day-to-day work is building systems for the Paraíba State Legislature (ALPB).

[LinkedIn](https://www.linkedin.com/in/evelin-limeira) · [ResearchGate](https://www.researchgate.net/profile/Evelin-Limeira-2) · [Lattes](http://lattes.cnpq.br/8347885521421671) · [Email](mailto:evelinlena@gmail.com)

## Cybersecurity research

Also private repos unless a link is given.

**Hybrid IDS for IoMT** (work in progress) uses one autoencoder per device rather than one global model, backed by a supervised classifier and EVT-based thresholds. Tested with leave-one-attack-out and leave-one-group-out splits across four IoMT datasets.
`Python` `TensorFlow` `scikit-learn` `EVT` `SHAP`

**LLM-based IDS benchmark** (work in progress) compares pre-quantized open-source LLMs, general-purpose and cybersecurity-specialized, against classical ML baselines for IoMT intrusion detection, run locally on consumer hardware. Hypotheses are pre-registered before each run, so a negative result still counts.
`Python` `llama.cpp` `GGUF`

**Xeque-Mate Agregador** is a Cyber Threat Intelligence research at CISSA/CESAR, investigating the use of structured threat-intelligence data and LLMs for cybersecurity analysis.

## Publications

Two papers accepted at [SBSeg 2026](https://sol.sbc.org.br/index.php/sbseg/issue/view/1728) (Brazilian Symposium on Cybersecurity), both on IoMT intrusion detection, each with a reproducible artifact repo. Full list on [ResearchGate](https://www.researchgate.net/profile/Evelin-Limeira-2).

**[Per-device autoencoder anomaly detection](https://github.com/EvelinLimeira/autoencoders_sbseg2026_public)** trains one autoencoder per device instead of a single pooled model, with thresholds calibrated using Extreme Value Theory and per-feature reconstruction error. Beats the pooled baseline on behavioral protocol attacks: 0.945 vs. 0.681 mean detection rate.
`Python` `TensorFlow` `EVT`

**[Kill chain-aware IDS evaluation](https://github.com/EvelinLimeira/kill_chain_ids_eval_sbseg2026)** compares Random Forest, LightGBM, a 1D-CNN, and an autoencoder across 18 attack categories in the CICIoMT2024 dataset, checking detection at each stage of the attack lifecycle instead of one aggregate score. Results are validated with bootstrap confidence intervals and McNemar's test rather than a single accuracy number.
`Python` `scikit-learn` `LightGBM` `SHAP` `LIME`

## Other projects

**[RAG TriviaQA pipeline](https://github.com/EvelinLimeira/rag-triviaqa-pipeline)** uses BM25, dense, and hybrid retrieval with reranking, graded by an LLM judge rather than IR metrics alone.
`Python` `LangChain` `FAISS` `deepeval`

**[Sentiment analysis on product reviews](https://github.com/EvelinLimeira/sentiment-analysis-product-reviews)** compares four approaches to the same classification problem, from SVM+TF-IDF up to a fine-tuned DistilBERT, checked for statistical significance across 10 runs.
`Python` `PyTorch` `Transformers` `scikit-learn`

**[Detectron2 vs. Gemini](https://github.com/EvelinLimeira/estudo-comparativo-detectron-gemini)** (team project). Detectron2-ResNet18 against Gemini 2.0-flash on the same image classification task. Gemini won on accuracy, Detectron won on latency.
`Computer Vision` `Detectron2` `Gemini`

## Professional experience

### Paraíba State Legislature (ALPB)

Legislative Technical Advisor since 2014 and software engineer since 2023.

I develop information systems for public-sector workflows, including retrieval-augmented information systems and real-time legislative systems.

`Java` `Spring Boot` `Python` `Angular` `PostgreSQL` `RAG`  

## Education

- MSc in Software Engineering, Cesar School (2025–present)
- Specialization in Artificial Intelligence and Machine Learning, PUC Minas (2023–2024)
- BSc in Systems Analysis and Development, UNINASSAU (2021–2022)
- Bachelor of Laws, Universidade Federal da Paraíba (2006–2010)

## Skills

Python, Java, TypeScript, SQL

Cyber Threat Intelligence, Autoencoders, EVT, SHAP/LIME, Random Forest, LightGBM, XGBoost, CNNs, Transformers, Bootstrap CI / McNemar's Test

RAG, LangChain, Hugging Face Transformers, PyTorch, scikit-learn, deepeval

Spring Boot, PostgreSQL, WebSocket/STOMP, OAuth2

Angular, Tailwind CSS

Docker, Git, ChromaDB, FAISS, Ollama, llama.cpp

## Contact

- LinkedIn: [evelin-limeira](https://www.linkedin.com/in/evelin-limeira)
- ResearchGate: [Evelin-Limeira-2](https://www.researchgate.net/profile/Evelin-Limeira-2)
- Lattes: [8347885521421671](http://lattes.cnpq.br/8347885521421671)
- Email: [evelinlena@gmail.com](mailto:evelinlena@gmail.com)
