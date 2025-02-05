# Chat with Your Documents (Powered by ModernBert & Llama-3.2)

This is an interactive **Streamlit** application that allows users to upload **PDF documents** and chat with them using a combination of **ModernBert** for embeddings and **Llama-3.2** for generating responses.

## Features
- **Upload PDFs** and process them for querying.
- **Document indexing** using `VectorStoreIndex`.
- **AI-powered Q&A** with contextual understanding.
- **PDF Preview** within the app.
- **Chat History** retention across interactions.
- **Efficient embeddings** using `HuggingFaceEmbedding`.

## Installation

1. Clone the repository:
   ```bash
   git clone <repo_url>
   cd <repo_name>
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For macOS/Linux
   venv\Scripts\activate     # For Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the Streamlit application:
```bash
streamlit run app.py
```

## How It Works
1. Upload a **PDF document** via the sidebar.
2. The document is **indexed and embedded** using `ModernBert`.
3. Ask questions about the document in the chat interface.
4. The AI retrieves relevant information and **generates answers** using `Llama-3.2`.
5. Enjoy an interactive, AI-powered **document conversation** experience! 🎉

## Dependencies
- **FastAPI** - For API interactions
- **LlamaIndex** - For document processing and querying
- **Transformers** - For embedding models and LLM processing
- **Streamlit** - For UI
- **HuggingFace Embeddings** - For vector indexing

## Known Issues
- **Large PDFs may take time to process.** Consider optimizing document handling.
- **Responses depend on model performance.** Some queries might not return accurate answers.
- **Llama-3.2 model must be installed locally.** Ensure it's available.
- and yes I am currently working on them.

