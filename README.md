# Evelin Limeira

**Software Engineer & Cybersecurity Researcher** — building intelligent systems for the public sector and applied ML/NLP research.

MSc Candidate in Software Engineering · Cybersecurity Researcher at CISSA · Systems Developer at Assembleia Legislativa da Paraíba (ALPB) · João Pessoa, Brazil

[LinkedIn](https://www.linkedin.com/in/evelin-limeira) · [ResearchGate](https://www.researchgate.net/profile/Evelin-Limeira-2) · [Email](mailto:evelinlena@gmail.com)

## Currently

- Researching retrieval-augmented generation (RAG) and applied NLP as part of my MSc in Software Engineering
- Building REGI, a RAG-based legal assistant for the Paraíba State Legislature
- Investigating cybersecurity topics as part of the CISSA research group

## Selected Work

**REGI — Regimento Eletrônico de Gestão Inteligente**
RAG-based legal assistant that answers natural-language questions across multiple legal sources at once — the Legislature's internal rulebook, the State Constitution, and the Federal Constitution. Combines ChromaDB semantic search with BM25 keyword search via Reciprocal Rank Fusion, routes each query to the most relevant source, and returns answers with structured inline citations (`[Source: Name, Art. N]`). Served through a local LLM (Gemma via Ollama) behind a Gradio interface.
`Python` · `RAG` · `ChromaDB` · `BM25` · `Ollama` · `Gradio`
*Internal system — Assembleia Legislativa da Paraíba*

**Painel / Comissão Virtual**
Real-time virtual committee and voting panel for legislative sessions, with WebSocket-based live updates, an OAuth2 authorization server, and automated generation of session documents (PDF/DOCX).
`Java` · `Spring Boot` · `PostgreSQL` · `Angular` · `WebSocket/STOMP` · `OAuth2`
*Internal system — Assembleia Legislativa da Paraíba*

**[RAG TriviaQA Pipeline](https://github.com/EvelinLimeira/rag-triviaqa-pipeline)**
End-to-end RAG pipeline benchmarking BM25, dense (FAISS), and hybrid retrieval with cross-encoder reranking. Evaluated with an LLM-judge (via deepeval) for correctness, faithfulness, and answer relevancy, alongside classic IR metrics (Hit Rate@k, MRR).
`Python` · `LangChain` · `FAISS` · `BM25` · `deepeval` · `Ollama`

**[Sentiment Analysis on Product Reviews](https://github.com/EvelinLimeira/sentiment-analysis-product-reviews)**
Comparative NLP study of four sentiment-classification approaches — SVM+TF-IDF, SVM+embeddings, fine-tuned DistilBERT, and few-shot in-context learning — validated across 10 runs with different random seeds and statistical significance testing (Wilcoxon, Kruskal-Wallis).
`Python` · `PyTorch` · `Transformers` · `scikit-learn`

**[Comparative Study: Detectron2 vs. Gemini](https://github.com/EvelinLimeira/estudo-comparativo-detectron-gemini)**
Research paper comparing a traditional object-detection model (Detectron2) against a multimodal LLM (Gemini) on the same detection task.
`Computer Vision` · `Detectron2` · `Gemini`

## Research

MSc candidate in Software Engineering, focused on retrieval-augmented generation and applied NLP for the legal/legislative domain. Publications and working papers on [ResearchGate](https://www.researchgate.net/profile/Evelin-Limeira-2).

## Skills

- **Languages** — Python, Java, TypeScript, SQL
- **ML / NLP** — RAG pipelines, LangChain, Hugging Face Transformers, PyTorch, scikit-learn, LLM evaluation (deepeval)
- **Backend** — Spring Boot, PostgreSQL, WebSocket/STOMP, OAuth2
- **Frontend** — Angular, TypeScript, Tailwind CSS
- **Tools** — Docker, Git, ChromaDB, FAISS, Ollama

## Connect

- LinkedIn — [evelin-limeira](https://www.linkedin.com/in/evelin-limeira)
- ResearchGate — [Evelin-Limeira-2](https://www.researchgate.net/profile/Evelin-Limeira-2)
- Email — [evelinlena@gmail.com](mailto:evelinlena@gmail.com)
