# 🌬️ Auto-updating Air Quality Website

Une série de tutoriels pour créer des graphiques qui se mettent à jour automatiquement en utilisant **GitHub Actions**, **GitHub Pages** et **Datawrapper**. Un jour, il y aura même un lien vers la vidéo YouTube ! 🎥

---

## ❓ Le Problème

Il existe un site web avec des données intéressantes ! Les données sont excellentes, mais la présentation laisse à désirer... 😕

---

## 🛠️ Les Étapes

### 1. Extraire les données 🕵️‍♂️

- Utiliser `pd.read_html` pour trouver tous les éléments `<table>` du site web.
- Sélectionner la première table comme source de données.
- Nettoyer les données pour les rendre exploitables.
- Enregistrer le tout dans un fichier `air-quality.csv`.

### 2. Automatiser la mise à jour 🔄

- Créer un dépôt GitHub pour le projet.
- Activer **GitHub Actions**.
- Configurer le fichier `.yml` pour définir le workflow.
- **Assurez-vous que le nom du notebook correspond exactement !**

### 3. Créer un site web 🌐

- Créer un fichier `index.html`.
- L'ajouter au dépôt et le pousser sur GitHub.
- Activer **GitHub Pages** en cliquant sur les bons boutons.
- Vérifier que `index.html` fonctionne en visitant la page.

### 4. Ajouter une visualisation 📊

- Utiliser **Datawrapper** pour créer des graphiques.
- S'assurer de **lier** les données au lieu de les **téléverser**.
- Utiliser la version **iframe responsive** pour l'intégration.

### 5. Mettre à jour le site 🚀

- Ajouter le code d'intégration dans `index.html`.
- Pousser les modifications sur GitHub Pages.
- Attendre que GitHub Actions termine le déploiement du site web.

### 6. 🎉 Célébration !

- Profiter du site web qui se met à jour automatiquement avec des visualisations élégantes !
