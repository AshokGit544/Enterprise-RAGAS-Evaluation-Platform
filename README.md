# Enterprise RAGAS Evaluation Platform

## Project Overview
This project demonstrates a RAGAS-style evaluation workflow for enterprise document intelligence.

The project simulates how a RAG system can be evaluated after retrieval and grounded answer generation. The focus is not only on building retrieval, but also on measuring whether:
- retrieval quality is good
- answers are grounded in retrieved context
- responses are relevant to the question
- the system behaves consistently across evaluation cases

## Business Problem
In enterprise AI, building a RAG workflow is not enough. The system must also be evaluated carefully so teams can trust production outputs.

Without evaluation, a system may:
- retrieve weak context
- generate partially unsupported responses
- regress after updates
- lose trust from business users

## Project Goal
The goal of this project is to simulate an enterprise RAG evaluation framework using RAGAS-style metrics.

The project shows how to:
1. generate enterprise documents
2. preprocess and chunk them
3. build retrieval-ready indexed records
4. retrieve relevant chunks for a question
5. generate a grounded response
6. evaluate response quality with RAGAS-style metrics

## Main Metrics
This project uses lightweight RAGAS-style metrics:
- answer relevance
- groundedness
- context precision
- context recall

## End-to-End Flow
1. Create synthetic enterprise manufacturing documents
2. Preprocess and normalize text
3. Chunk documents into smaller retrieval units
4. Enrich chunks with metadata
5. Build a retrieval index
6. Create evaluation questions
7. Retrieve top-k chunks
8. Generate grounded responses
9. Evaluate the responses using RAGAS-style metrics
10. Create benchmark summary outputs

## Main Features
- synthetic enterprise manufacturing documents
- metadata enrichment
- chunking for retrieval
- TF-IDF retrieval
- grounded response generation
- RAGAS-style evaluation metrics
- retrieval benchmarking summary
- output files for retrieval and evaluation review


├── outputs/── config/
