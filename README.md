# Open-Domain-Question-Answering-System---RAG
🤖 Production-ready RAG system for open-domain QA | Hybrid retrieval (Dense+BM25) + LLM generation | Natural Questions &amp; TriviaQA | FastAPI + Docker | 61.4% F1 score
A scalable RAG question-answering system combining SBERT embeddings, BM25 retrieval, and LLM generation with comprehensive evaluation on Natural Questions and TriviaQA datasets. 

┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Data Pipeline │ → │ Retrieval System │ → │ Generation API  │
└─────────────────┘    └──────────────────┘    └─────────────────┘
         │                       │                       │
    ┌────────────┐         ┌─────────────┐        ┌─────────────┐
    │ NQ + TQA   │         │Dense + BM25 │        │ FastAPI +   │
    │Processing  │         │+ Reranking  │        │ Docker      │
    └────────────┘         └─────────────┘        └─────────────┘


🎯 Core Value Proposition
Problem Solved: Eliminates LLM hallucinations through grounded retrieval
Performance: 61.4% F1 score on combined NQ+TriviaQA benchmarks
Production Ready: Sub-second responses, Docker deployment, monitoring

🏆 Technical Highlights
Hybrid Architecture: 70% dense + 30% sparse retrieval fusion
Advanced Evaluation: 6+ metrics including ROUGE, BLEU, Exact Match
Modern Stack: FastAPI, Docker, FAISS, Sentence-Transformers

