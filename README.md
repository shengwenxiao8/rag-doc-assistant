# RAG Document Assistant

> 🚧 Under Development

An intelligent document Q&A system that uses Retrieval-Augmented Generation (RAG)
to answer questions based on your documents with source citations.

## Features (Planned)

- [ ] Document upload (PDF / Markdown / Text)
- [ ] Automatic chunking and embedding
- [ ] Vector search with Chroma
- [ ] AI-generated answers with source citations
- [ ] Multi-turn conversational Q&A
- [ ] Document management dashboard

## Tech Stack

- **Backend:** Python / FastAPI
- **Vector DB:** Chroma
- **LLM:** Claude API
- **Frontend:** React / Next.js / TailwindCSS
- **Embedding:** OpenAI text-embedding-3-small

## Architecture

    Document Upload → Chunking → Embedding → Vector Store (Chroma)
                                                  ↓
    User Question → Embedding → Similarity Search → Retrieved Chunks
                                                  ↓
                                  LLM (Claude) → Answer with Citations

## Status

🔜 Development starts in Phase 1 (W3-W6)

## License

MIT
