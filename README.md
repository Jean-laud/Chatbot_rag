# Chatbot RAG (Retrieval-Augmented Generation)

Ce projet implémente un système de chatbot utilisant la technique **Retrieval-Augmented Generation (RAG)** pour améliorer les réponses générées par un modèle en utilisant des informations provenant de documents externes. Le chatbot est capable de répondre à des questions en extrayant des informations pertinentes de fichiers PDF, texte ou tout autre document stocké sur un service de stockage dans le cloud, comme AWS S3.

## Prérequis

Avant de pouvoir exécuter ce projet, vous devez vous assurer que vous avez les éléments suivants :

- **Python 3.x** installé sur votre machine.
- **Bibliothèques nécessaires** : `boto3`, `PyPDF2`, `spaCy`, `transformers`, etc.
- Un **compte AWS** et un **bucket S3** pour stocker les fichiers PDF et texte utilisés pour les recherches.
- **Clé d'accès AWS** configurée sur votre machine via `aws configure` ou des variables d'environnement.

## Installation

1. Clonez ce dépôt sur votre machine :

```bash
git clone https://github.com/votre-utilisateur/chatbot-rag.git

pip install -r requirements.txt

aws configure
