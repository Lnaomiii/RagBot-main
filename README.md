RAGBot is an AI knowledge base management system that utilizes Retrieval Augmented Generation (RAG) technology to provide intelligent document processing and retrieval capabilities.

The core technology stack includes ElasticSearch, Kafka, WebSocket, Spring Security, Docker, MySQL, and Redis.

Its goal is to help enterprises and individuals manage and utilize information in their knowledge bases more efficiently. It supports a multi-tenant architecture, allowing users to query the knowledge base using natural language and receive AI-generated responses based on their own documents.

The system allows users to:

- Upload and manage various types of documents
- Automatically process and index document content
- Query the knowledge base using natural language
- Receive AI-generated responses based on their own documents

Backend:

+ Framework: Spring Boot 3.4.2 (Java 17)
+ Database: MySQL 8.0
+ ORM: Spring Data JPA
+ Cache: Redis
+ Search Engine: Elasticsearch 8.10.0
+ Message Queue: Apache Kafka
+ File Storage: MinIO
+ Document Parsing: Apache Tika
+ Security Authentication: Spring Security + JWT
+ AI Integration: DeepSeek API/Local Ollama + Doubao Embedding
+ Real-time Communication: WebSocket
+ Dependency Management: Maven
+ Reactive Programming: WebFlux

Frontend:

+ Framework: Vue 3 + TypeScript
+ Build Tool: Vite
+ UI Components: Naive UI
+ State Management: Pinia
+ Routing: Vue Router
+ Styling: UnoCSS + SCSS
+ Icons: Iconify
+ Package Management: pnpm

## Prerequisites

Before you begin, please ensure you have the following software installed:

- Java 17
- Maven 3.8.6 or higher
- Node.js 18.20.0 or higher
- pnpm 8.7.0 or higher
- MySQL 8.0
- Elasticsearch 8.10.0
- MinIO 8.5.12
- Kafka 3.2.1
- Redis 7.0.11
- Docker (optional, for running Redis, MinIO, Elasticsearch, and Kafka services)
