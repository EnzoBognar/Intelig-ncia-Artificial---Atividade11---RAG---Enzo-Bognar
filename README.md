# Mini Aplicação RAG (Retrieval-Augmented Generation)

Este repositório contém uma implementação simples de um sistema RAG utilizando:

- HuggingFace Transformers
- SentenceTransformers
- FAISS
- Python 3.10+
- Google Colab

## 🔍 Objetivo
Demonstrar como LLMs podem melhorar suas respostas consultando uma base de conhecimento externa antes de gerar o texto.

## 🧠 Tecnologias
- `sentence-transformers/all-MiniLM-L6-v2` → embeddings
- `faiss-cpu` → busca vetorial
- `google/flan-t5-base` → geração de texto

## 📁 Conteúdo
- `rag_demo.ipynb` — notebook com o código completo dividido em blocos.
- `apresentacao.pdf` — slides da atividade (3 slides).
- Este README explicativo.

## ▶️ Como executar
Abra o arquivo `rag_demo.ipynb` no Google Colab e execute célula por célula.
