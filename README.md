# RAG — Retrieval-Augmented Generation Learning Path

A hands-on, module-by-module implementation of a RAG pipeline, built to understand each stage of retrieval-augmented generation from data ingestion through to agentic RAG.

## 📚 Modules
| # | Module | What it covers |
|---|--------|-----------------|
| 0 | Data Ingestion & Parsing | Loading and parsing raw documents |
| 1 | Vector Embeddings & Databases | Generating embeddings, intro to vector storage |
| 2 | Vector Stores | Working with vector store implementations |
| 3 | Vector DB | Vector database integration |
| 4 | Advanced Chunking | Chunking strategies for better retrieval |
| 7 | Agentic RAG | Combining RAG with agentic workflows |

## 🛠️ Tech Stack
- **Language:** Python (managed with `uv`)
- **Core:** RAG pipeline (`src/rag`)
- <!-- fill in: LangChain / LlamaIndex, vector DB used (FAISS/Chroma/Pinecone/etc.), LLM provider -->

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- [uv](https://docs.astral.sh/uv/) package manager

### Installation
\`\`\`bash
git clone https://github.com/123456-raul/Rag.git
cd Rag
uv sync
\`\`\`

### Environment Variables
Create a `.env` file (not committed — see `.env.example` if provided) with:
\`\`\`
<!-- e.g. OPENAI_API_KEY=your-key-here -->
\`\`\`

### Running a Module
Each numbered folder is a self-contained stage of the pipeline. Navigate into a module and run its scripts to see that stage in action, e.g.:
\`\`\`bash
cd "7-Agentic Rag"
python <script>.py
\`\`\`

## 📌 Notes
This repo is structured as a learning progression rather than a single deployable app — each folder builds on concepts from the previous one, culminating in agentic RAG.

## 📌 Future Improvements
- Consolidate learnings into a single end-to-end pipeline/app
- Add a `.env.example` template for required environment variables
- Add module-level READMEs explaining each stage's design choices
