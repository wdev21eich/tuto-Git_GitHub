# Git & GitHub pour les débutants 🚀

Ce tutoriel vous guidera à travers les étapes de base pour démarrer avec Git et GitHub.

## 1\. Installation de Git

Pour commencer, vous devez installer Git sur votre machine.

  * **Linux** : `sudo apt-get install git` (ou équivalent pour votre distribution)
  * **macOS** : Installez Xcode Command Line Tools ou téléchargez Git depuis [git-scm.com](https://git-scm.com/).
  * **Windows** : Téléchargez l'installeur depuis [git-scm.com](https://git-scm.com/).

## 2\. Configuration de Git

Une fois Git installé, configurez votre nom et votre adresse e-mail. C'est essentiel pour identifier vos contributions.

```bash
git config --global user.name "Votre Nom"
git config --global user.email "votre.email@example.com"
```

## 3\. Création d'un premier dépôt (Repository)

Un dépôt Git est un dossier qui contient votre projet et son historique de versions.

  * Créez un nouveau dossier pour votre projet : `mkdir mon-projet`
  * Naviguez dans le dossier : `cd mon-projet`
  * Initialisez un dépôt Git : `git init`

## 4\. Les commandes de base

  * **Ajouter des fichiers** : Pour suivre les modifications, vous devez "ajouter" vos fichiers à la zone de staging.
    `git add .` (ajoute tous les fichiers modifiés)

  * **Faire un "commit"** : C'est comme une "sauvegarde" de votre travail. Chaque commit a un message pour décrire les changements.
    `git commit -m "Mon premier commit"`

  * **Vérifier le statut** : Affiche les fichiers modifiés et non-suivis.
    `git status`

## 5\. Connexion à GitHub

GitHub est une plateforme pour héberger vos dépôts.

  * Créez un nouveau dépôt sur GitHub (sans cocher l'option `Initialize this repository with a README`).

  * Copiez l'URL de votre dépôt.

  * Liez votre dépôt local au dépôt distant :
    `git remote add origin URL_DE_VOTRE_DEPOT`

  * **Pousser sur GitHub** : Envoyez vos commits locaux vers le dépôt distant.
    `git push -u origin main` (ou `master` si c'est le cas)

![Screenshot](versionner-GitHub.png)