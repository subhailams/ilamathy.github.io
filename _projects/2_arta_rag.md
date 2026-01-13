---
layout: page
title: Arta RAG - AI Research Assistant
description: Graph-based retrieval system for comprehensive research answers
img: assets/img/arta-rag.jpg
importance: 2
category: work
giscus_comments: true
---

## Problem
Typical LLM and naive RAG systems provide isolated insights lacking context. Researchers need comprehensive answers that connect related concepts and provide contextual understanding.

## Solution
ArGraph enhances queries with a context-aware graph-based retrieval system to deliver comprehensive and connected answers. The system builds knowledge graphs from research documents and uses graph traversal to provide holistic responses.

## Key Features
- **Graph-Based Retrieval**: Knowledge graph construction from documents
- **Context-Aware Queries**: Enhanced query understanding through graph relationships
- **Connected Insights**: Linking related concepts across documents
- **Research Assistant**: Specialized for academic and technical research

## Technical Implementation
- **Tech Stack**: LLamaIndex, Agentic AI, TypeScript, Neo4j, FastAPI
- **Knowledge Graph**: Neo4j for storing and querying relationships
- **Vector Search**: Hybrid retrieval combining semantic and graph search
- **API Design**: RESTful API for integration with research workflows

## Research Applications
- Academic paper analysis and synthesis
- Technical documentation exploration
- Cross-domain concept discovery
- Literature review automation

**Client**: Argonne National Laboratory  
**Repository**: [GitHub](https://github.com/subha-ilamathy/argraph)
