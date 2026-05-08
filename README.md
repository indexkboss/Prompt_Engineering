# Prompt Engineering avec Python

Apprentissage des techniques d'interaction avec plusieurs LLMs (OpenAI, Ollama, Groq) en Python.

---

### 🎯 Objectif du projet

Ce projet a pour but de comprendre et expérimenter le Prompt Engineering ainsi que l’utilisation de différents LLMs (locaux et cloud) à travers Python.

---

### 📌 Contenu du projet

- Tokenisation
- Interagir avec un LLM OpenAI (via OpenRouter – solution gratuite)
- Interagir avec un LLM local via **Ollama**
- Interagir avec Groq
- Génération d'image : Text-to-Image (via Hugging Face, gratuit)
- Image-to-Text (description d'une image par un LLM)
- Cas d'usage : **Analyse de sentiment** (Sentiment Analysis)

#### Techniques de Prompt Engineering utilisées

- Simple Prompt (Text-to-Text)
- Zero Shot Prompt
- Few Shot Prompt
- Text-to-Image Prompt
- Image-to-Image Prompt
- Use Case du Prompt Engineering : Sentiment Analysis

> 💡 Aucun paiement requis : les exemples utilisent OpenRouter, Hugging Face et Ollama en local.

---

### 🔧 Prérequis

- **Python** >= 3.13  
  (projet testé sur Python 3.13)

- **Ollama** installé localement  
  👉 https://ollama.com

- Comptes gratuits pour obtenir des clés API :
  - https://openrouter.ai/
  - https://console.groq.com/
  - https://huggingface.co/

---

### 📦 Installation et configuration

Ce projet utilise **uv** pour gérer les dépendances Python.

#### 1. Installer uv (si nécessaire)

```bash
pip install uv
```

---

#### 2. Cloner le projet

```bash
git clone https://github.com/indexkboss/Prompt_Engineering.git
cd Prompt_Engineering
```

---

#### 3. Installer les dépendances

```bash
uv sync
```

---

#### 4. Configurer les clés API

Créer un fichier `.env` à la racine du projet :

```env
OPENROUTER_API_KEY=your_key
GROQ_API_KEY=your_key
HUGGINGFACE_API_KEY=your_key
OPENAI_API_KEY=your_key
```

---

#### 5. Installer un modèle Ollama

Exemple :

```bash
ollama pull llama3
```

Puis lancer Ollama localement.

---

### 🧠 Cas d’usage présents dans le notebook

- Génération de texte
- Analyse de sentiment
- Génération d’images
- Description d’images
- Comparaison entre plusieurs fournisseurs de LLMs
- Utilisation de modèles locaux et cloud

---

### ⚠️ Remarques

- Ne jamais publier le fichier `.env`
- Ajouter `.env` dans le `.gitignore`
- Certaines fonctionnalités peuvent dépendre de clés API payantes (OpenAI)
- Les performances varient selon le modèle utilisé

---

### 👨‍💻 Auteur

Khadija Bossony  
https://github.com/indexkboss  

Projet réalisé dans le cadre d’un apprentissage du Prompt Engineering et des LLMs avec Python.

---

### 🙏 Crédits

Ce projet s’inspire d’une vidéo YouTube réalisée par le Professeur Mohamed YOUSSFI.

Vidéo source : https://www.youtube.com/watch?v=ueNO9rq8ap8&list=TLPQMjIwNDIwMjYh1SQUM_pj5A&index=5

Les exemples ont été reproduits, testés et adaptés avec différentes APIs et outils comme OpenRouter, Groq, Hugging Face et Ollama.