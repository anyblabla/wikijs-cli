# Wiki.js CLI Manager by BlablaLinux

Un outil en ligne de commande (CLI) simple et efficace pour gérer votre instance [Wiki.js](https://js.wiki/) directement depuis le terminal.

## ✨ Fonctionnalités

- **Lister / Rechercher** : Affiche vos pages avec leur statut (publié/brouillon) et leur langue.  
- **Créer** : Crée des pages en Markdown avec gestion automatique de la langue via le slug.  
- **Modifier** : Édition rapide du contenu via votre éditeur local (Nano, Vim, etc.).  
- **Supprimer** : Suppression sécurisée avec confirmation.

## 🚀 Installation rapide

1. **Cloner le dépôt** :

   ```bash
   git clone https://github.com/anyblabla/wikijs-cli.git
   cd wikijs-cli
   ```

2. **Installer les dépendances** :

   ```bash
   pip3 install -r requirements.txt
   ```

3. **Configuration**  
   Ouvrez `wiki_cli.py` et renseignez vos variables `WIKI_URL` et `WIKI_TOKEN`.

## 📖 Documentation complète

Retrouvez le tutoriel détaillé sur mon wiki :  
👉 [https://wiki.blablalinux.be/fr/python-conception-cli-wikijs](https://wiki.blablalinux.be/fr/python-conception-cli-wikijs)

## ⚖️ Licence

Distribué sous licence **GPL-3.0**.  
Voir le fichier `LICENSE` pour plus d'informations.
