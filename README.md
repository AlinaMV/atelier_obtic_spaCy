# Atelier ObTIC : Introduction au NLP avec spaCy

Bienvenue dans le dépôt de l'atelier sur le Traitement Automatique des Langues (TAL) avec la bibliothèque Python **spaCy**. Cet atelier a été conçu pour offrir une introduction pratique aux concepts fondamentaux du NLP en français, de la tokenisation de base à l'analyse sémantique.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlinaMV/atelier_obtic_spaCy/blob/main/atelier_spacy.ipynb)

## 📖 À propos de cet atelier

Cet atelier s'adresse aux étudiants, chercheurs et développeurs ayant des bases en Python et souhaitant découvrir le traitement automatique du langage naturel. À travers un notebook Jupyter interactif, nous explorons les fonctionnalités essentielles de spaCy en partant des concepts les plus simples pour progresser vers des applications plus avancées.

**Date** : ObTIC - 13 février 2026

### Ce que vous apprendrez :

#### 📚 Partie 1 : De la Tokenisation à l'Analyse Complète

* **Concept fondamental** : Comprendre la tokenisation et ses subtilités (mots, ponctuation, contractions)
* **Pipeline minimal** : Utiliser `spacy.blank()` pour la tokenisation de base
* **Segmentation en phrases** : Découper un texte en phrases avec le `sentencizer`
* **Cas pratique** : Analyser un roman complet (statistiques, structure)

#### 🏷️ Partie 2 : Annotations Linguistiques avec Modèles Pré-entraînés

* **Modèles spaCy** : Charger et comparer les modèles français (`fr_core_news_sm/md/lg`)
* **Lemmatisation** : Réduire les mots à leur forme canonique
* **POS Tagging** : Identifier les catégories grammaticales (noms, verbes, adjectifs...)
* **Analyse morphologique** : Extraire les traits grammaticaux (genre, nombre, temps...)
* **Visualisation** : Créer des arbres de dépendance syntaxique avec **displaCy**
* **Reconnaissance d'Entités Nommées (NER)** : Identifier personnes, lieux, organisations

#### 🚀 Partie 3 : Techniques plus avancées 

* **Pattern Matching** : Utiliser le **Matcher** pour trouver des motifs linguistiques complexes
* **AttributeRuler** : Comprendre comment coffiger les erreurs des modèles pré-entraînés
* **EntityRuler** : Utiliser le **EntityRuler** pour avoir des labels personnalisés

#### 🧠 Partie 4 : Word Embeddings

* **Similarité sémantique** : Mesurer la proximité entre mots et phrases grâce aux word embeddings
* **Application pratique** : Construire un moteur de recherche sémantique pour une FAQ

---

## 📂 Contenu du Dépôt

1. **`atelier_spacy.ipynb`** : Le notebook Jupyter principal contenant tout le code, les exercices et les explications
2. **`README.md`** : Ce fichier, qui fournit une vue d'ensemble du projet

---

## ❓Comment commencer ?

### Option 1 : Google Colab (Recommandé)

Le moyen le plus simple de suivre cet atelier est d'utiliser Google Colab. Cela ne nécessite aucune installation sur votre machine.

Cliquez simplement sur le badge ci-dessous pour ouvrir le notebook dans votre navigateur :

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlinaMV/atelier_obtic_spaCy/blob/main/atelier_spacy.ipynb)


### Option 2 : En local

Si vous préférez exécuter le notebook sur votre propre machine :

1. **Clonez ce dépôt** :
   ```bash
   git clone https://github.com/VOTRE_NOM_UTILISATEUR/atelier-spacy-nlp.git
   cd atelier-spacy-nlp
   ```

2. **Créez un environnement virtuel** (recommandé) :
   ```bash
   python -m venv venv
   source venv/bin/activate  # Sur Windows: venv\Scripts\activate
   ```

3. **Installez les dépendances** :
   ```bash
   pip install -U spacy jupyter
   ```

4. **Téléchargez le modèle français** :
   ```bash
   python -m spacy download fr_core_news_lg
   ```

5. **Lancez Jupyter** :
   ```bash
   jupyter notebook atelier_spacy.ipynb
   ```

---

## 📚 Ressources Supplémentaires

### spaCy
- **Documentation officielle** : https://spacy.io
- **Cours gratuit** : https://course.spacy.io
- **Modèles disponibles** : https://spacy.io/models

Cet atelier a été préparé par l'équipe **ObTIC** de Sorbonne Université et mis à disposition à des fins éducatives.