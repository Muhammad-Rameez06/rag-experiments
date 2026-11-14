# RAG Experiments

Experiments with Retrieval-Augmented Generation (RAG), run in Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Muhammad-Rameez06/rag-experiments/blob/main/RAG_EXPERIMENTS.ipynb)

## What's here

| Notebook | Description |
|----------|-------------|
| `RAG_EXPERIMENTS.ipynb` | Embeds a small set of documents with `sentence-transformers` and retrieves the most similar ones for a query (the retrieval step of RAG). |

## How to run

1. Click the **Open in Colab** badge above.
2. Run the cells from top to bottom (**Runtime → Run all**).
3. To save changes back here: **File → Save a copy in GitHub**.

## Stack

- Python (Google Colab)
- [sentence-transformers](https://www.sbert.net/) for text embeddings
- PyTorch

## Roadmap

- [x] Embed documents and find similar ones for a query
- [ ] Chunk real documents (PDF/text)
- [ ] Store embeddings in a vector database
- [ ] Generate answers with an LLM from the retrieved context
- [ ] Evaluate retrieval quality

## Notes

API keys go in Colab's 🔑 Secrets panel and are read with `google.colab.userdata`. Never put them in notebook cells.
