# RAG Engineering Field Guide

A static, searchable learning and reference portal for building production-grade Retrieval-Augmented Generation applications.

## Documentation website

After GitHub Pages is enabled with **Source: GitHub Actions**, the site is published at:

https://sivakavin.github.io/production-rag-patterns/

## Local preview

Open `docs/index.html` in a browser. The site is static HTML, CSS and JavaScript; no build step or package installation is required.

## Topics

- Document ingestion, parsing, OCR, tables and chunking
- Vector, lexical and hybrid retrieval
- Query rewriting, decomposition, HyDE and multi-hop retrieval
- Grounded generation, citations and context management
- Production latency, rate limits, caching and observability
- Prompt injection, tenant isolation, PII and secrets
- Evaluation metrics, readiness checklist and acceptance tests

## Deployment

A GitHub Actions workflow at `.github/workflows/deploy-docs.yml` deploys the `docs/` directory to GitHub Pages when documentation changes are pushed to `main`.
