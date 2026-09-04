# RAG and Knowledge Architecture

## Pipeline
Knowledge source → ingestion → parsing/chunking → metadata → embeddings/vector index → retrieval → grounding → response → provenance.

## Requirements
- Tenant-aware retrieval.
- Source provenance.
- Document versioning.
- Access-control filtering before context reaches the model.
- Relevance evaluation.
- Protection against prompt injection in retrieved documents.
- Citation/provenance metadata where appropriate.

## Knowledge quality
Only approved and appropriately classified knowledge should be eligible for production retrieval.
