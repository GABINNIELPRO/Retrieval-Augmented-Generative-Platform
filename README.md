# RAG Platform – Public Overview

## À propos

Ce dépôt public présente la description, l’architecture et les objectifs d’une plateforme **Retrieval-Augmented Generation (RAG)** complète.

Le code source complet est hébergé dans un dépôt privé, pour des raisons de :
- protection de la propriété intellectuelle,
- sécurité (clés, configurations, pipelines),
- usage professionnel et démonstration contrôlée.

---

## Présentation du projet

Cette plateforme RAG est conçue comme une **architecture full-stack orientée production**, combinant :
- ingestion de documents multi-formats (PDF, Excel, images),
- extraction et chunking intelligent,
- génération d’embeddings vectoriels,
- recherche sémantantique (vector DB),
- génération de réponses via modèles IA (LLM),
- interface web moderne pour l’interaction utilisateur.

Le projet suit une **approche microservices**, avec une forte attention portée à :
- la scalabilité,
- la maintenabilité,
- l’industrialisation.

---

## Architecture

### Backend
- FastAPI (microservices)

### Vector Database & Search
- PostgreSQL + pgvector
- Elasticsearch

### Storage & Cache
- MinIO (S3 compatible)
- Redis

### Frontend
- React
- TypeScript
- Tailwind CSS

### Orchestration
- Docker
- Docker Compose

---

## Demonstration

![alt text](Video/Presentation_doc.mp4)
