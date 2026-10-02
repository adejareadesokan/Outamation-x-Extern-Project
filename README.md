# Outamation-x-Extern-Project
A multipurpose PDF query system originally intended for mortgage processing built with Retrieval Augmented Generation. Upload a PDF, and the system processes the document which you can query via the chatbot interface to get sourced information about the document  with a hallucination checker to ensure system faithfulness
## Tech Stack

| Component | Library |
|---|---|
| LLM inference | Groq (`openai/gpt-oss-20b`) |
| PDF parsing | PyMuPDF |
| Embeddings | Sentence-Transformers |
| Vector search | FAISS |
| Document/chunk management | LlamaIndex |
| UI | Gradio |

## Getting Started
### Prerequisites
- Python 3.9 +
- A Groq API Key
### Installation
pip install gradio gradio_pdf pymupdf groq numpy pandas llama-index llama-index-readers-file sentence-transformers faiss-cpu
