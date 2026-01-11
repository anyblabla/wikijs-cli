# Wiki.js CLI Manager by BlablaLinux

![License](https://img.shields.io/badge/License-GPL--3.0-blue.svg)
![Python](https://img.shields.io/badge/Python-3.9%2B-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)
![Platform](https://img.shields.io/badge/Platform-Linux-lightgrey.svg)

Un outil en ligne de commande (CLI) simple et efficace pour gérer votre instance [Wiki.js](https://js.wiki/) directement depuis le terminal.

**English version available below.**

---

## 📦 Dépôts disponibles

- **GitHub** : [https://github.com/anyblabla/wikijs-cli](https://github.com/anyblabla/wikijs-cli)  
- **Gitea (miroir auto‑hébergé)** : [https://gitea.blablalinux.be/blablalinux/wikijs-cli](https://gitea.blablalinux.be/blablalinux/wikijs-cli)  

---

## 🇫🇷 Fonctionnalités

- **Lister / Rechercher** : Affiche les pages avec leur statut (publié / brouillon) et leur langue.  
- **Créer** : Génère des pages Markdown avec détection automatique de la langue via le slug.  
- **Modifier** : Ouvre rapidement une page dans votre éditeur local (Nano, Vim, etc.).  
- **Supprimer** : Suppression sécurisée avec confirmation interactive.

---

## 🚀 Installation rapide

### 1. Cloner le dépôt

#### 🔵 Depuis GitHub

```bash
git clone https://github.com/anyblabla/wikijs-cli.git
cd wikijs-cli
```

#### 🟠 Depuis Gitea

```bash
git clone https://gitea.blablalinux.be/blablalinux/wikijs-cli.git
cd wikijs-cli
```

### 2. Installer les dépendances

```bash
pip3 install -r requirements.txt
```

### 3. Configuration

Éditez `wiki_cli.py` et renseignez :

```python
WIKI_URL = "https://votre-wiki.tld/graphql"
WIKI_TOKEN = "votre_token_api"
```

---

## 📖 Documentation complète

[https://wiki.blablalinux.be/fr/python-conception-cli-wikijs](https://wiki.blablalinux.be/fr/python-conception-cli-wikijs)

---

## ⚖️ Licence

Distribué sous licence **GPL‑3.0**.

---

# 🇬🇧 English Version

## ✨ Features

- **List / Search**: Display pages with their status (published / draft) and language.  
- **Create**: Generate Markdown pages with automatic language detection based on the slug.  
- **Edit**: Quickly open a page in your local editor (Nano, Vim, etc.).  
- **Delete**: Safe deletion with interactive confirmation.

---

## 🚀 Quick Installation

### 1. Clone the repository

#### 🔵 From GitHub

```bash
git clone https://github.com/anyblabla/wikijs-cli.git
cd wikijs-cli
```

#### 🟠 From Gitea

```bash
git clone https://gitea.blablalinux.be/blablalinux/wikijs-cli.git
cd wikijs-cli
```

### 2. Install dependencies

```bash
pip3 install -r requirements.txt
```

### 3. Configuration

Edit `wiki_cli.py` and set:

```python
WIKI_URL = "https://your-wiki.tld/graphql"
WIKI_TOKEN = "your_api_token"
```

---

## 📚 Full Documentation

[https://wiki.blablalinux.be/fr/python-conception-cli-wikijs](https://wiki.blablalinux.be/fr/python-conception-cli-wikijs)  
(English version coming soon)

---

## ⚖️ License

Released under **GPL‑3.0**.