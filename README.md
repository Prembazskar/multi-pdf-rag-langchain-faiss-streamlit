# Multi-PDF RAG App (LangChain, FAISS, Streamlit)

A Streamlit app where you upload multiple PDFs, index them into a FAISS vector store, and ask questions that are answered from the documents with sources shown.

> Part of my Gen AI course practice work (Week 2, Day 4).

## Tech stack

- Python 3
- Streamlit
- LangChain
- FAISS
- OpenAI (`gpt-4o-mini`, `text-embedding-3-small`)
- pypdf

## Features

- Upload multiple PDFs
- Text splitting and embedding into a FAISS index
- Question answering grounded in the documents
- Answer plus source references

## Getting started

1. Clone the repository:
   ```bash
   git clone https://github.com/Prembazskar/multi-pdf-rag-langchain-faiss-streamlit.git
   cd multi-pdf-rag-langchain-faiss-streamlit
   ```
2. Install and configure:
   ```bash
   pip install -r requirements.txt
   cp .env.example .env   # then add your OpenAI key
   ```

Environment variables (set in `.env`, never commit it):

- `OPENAI_API_KEY`

## Usage

```bash
streamlit run rag_app.py
```

## Screenshots

![Multi PDF RAG APP SS1](Screenshots/Multi_PDF_RAG_APP_SS1.png)

![Multi PDF RAG APP SS2](Screenshots/Multi_PDF_RAG_APP_SS2.png)

![Multi PDF RAG APP SS3](Screenshots/Multi_PDF_RAG_APP_SS3.png)

![Multi PDF RAG APP SS4](Screenshots/Multi_PDF_RAG_APP_SS4.png)

![Script Run ss](Screenshots/Script_Run_ss.png)

## License

MIT, see [LICENSE](LICENSE).
