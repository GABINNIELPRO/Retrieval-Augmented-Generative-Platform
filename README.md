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

### Presentation
https://github.com/user-attachments/assets/d11c8c0a-2380-40a0-95d7-6de04653331b

### Description Image
https://github.com/user-attachments/assets/4c4a090f-716c-461c-9e1b-2f820efc2fb0

### Extraction Markdown
https://github.com/user-attachments/assets/cef341c4-188f-4d79-af28-841798fd7024

### Chunking
https://github.com/user-attachments/assets/1ef7bad2-5bdb-4be6-a755-97a386865314

### Embedding
https://github.com/user-attachments/assets/aabf896b-81ad-4559-9525-cbcb4225cee0

### Réponse par mot clé
https://github.com/user-attachments/assets/1667cab4-e63b-45ff-8eb6-347479ebf81f

### Réponse mot clé et sémantique
https://github.com/user-attachments/assets/8f929062-1d0e-4a32-a926-9ca813326004

### Réponse par mot clé et sémantique + image
https://github.com/user-attachments/assets/69306bf9-fe78-42c8-aae8-238ecb61edf0


https://github.com/user-attachments/assets/a4cbe0db-a47f-4421-a496-4d733eaaca95

### Réponse par texte uniquement
https://github.com/user-attachments/assets/ccdb2673-ea68-4d3b-87de-baeb8ac18c79




























