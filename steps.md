Development Roadmap

We'll proceed in phases, with a working application at the end of each phase.

Phase 1 — Project Foundation
Initialize Git repository.
Create project structure.
Configure dependency management.
Add Docker and Docker Compose.
Set up configuration management.
Configure logging.
Add linting and formatting.
Create initial FastAPI application.
Write the first tests.

Deliverable: A healthy project skeleton running in Docker.

Phase 2 — Document Ingestion
Read PDFs and text files.
Extract content.
Clean text.
Store metadata.
Add ingestion tests.

Deliverable: A reliable ingestion pipeline.

Phase 3 — Chunking
Compare fixed-size, recursive, and semantic chunking.
Implement one approach.
Measure chunk quality.

Deliverable: High-quality document chunks.

Phase 4 — Embeddings
Introduce Sentence Transformers.
Explain embedding vectors.
Cache models.
Benchmark embedding time.
Write embedding tests.

Deliverable: An embedding service with clear interfaces.

Phase 5 — Vector Store
Introduce ChromaDB.
Build a repository layer.
Store embeddings and metadata.
Support similarity search.
Add integration tests.

Deliverable: Searchable knowledge base.

Phase 6 — Retrieval
Explain cosine similarity.
Implement top-k retrieval.
Discuss metadata filtering.
Compare retrieval strategies.

Deliverable: Retrieval pipeline.

Phase 7 — Generation
Design prompt templates.
Implement LLM abstraction.
Build retrieval + generation flow.
Handle empty or low-confidence retrieval results.

Deliverable: Complete RAG pipeline.

Phase 8 — FastAPI
Build REST endpoints.
Add request validation.
Add response schemas.
Centralize error handling.
Generate OpenAPI documentation.

Deliverable: Production-ready API.

Phase 9 — Testing
Unit tests.
Integration tests.
Retrieval evaluation tests.
API tests.
Mock external dependencies.

Deliverable: High-confidence test suite.

Phase 10 — Production Engineering
Structured logging.
Environment variables.
Docker optimization.
Health endpoints.
Performance profiling.
Rate limiting (optional).
Request metrics.

Deliverable: Operationally robust service.

Phase 11 — CI/CD
GitHub Actions.
Automated testing.
Linting.
Build verification.
Optional image publishing.

Deliverable: Automated quality gates.

Phase 12 — AWS Deployment
Deploy on EC2.
Configure Nginx as a reverse proxy.
Enable HTTPS (optional).
Manage persistent storage for the vector database.
Set up monitoring basics.

Deliverable: Publicly accessible RAG service.