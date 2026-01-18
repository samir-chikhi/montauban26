# MGEC - Montauban 2026

**Site de campagne pour les élections municipales de mars 2026**

🗳️ *Montauban de Gauche, Écologiste et Citoyenne*

---

## 🌐 Présentation

Ce site web présente le programme et l'équipe de la coalition MGEC pour les élections municipales de Montauban en mars 2026.

## 📁 Structure du projet

```
mgec-site/
├── index.html              # Page d'accueil
├── programme.html          # Programme détaillé
├── mentions-legales.html   # Mentions légales
├── css/
│   └── style.css          # Styles CSS
├── js/
│   └── main.js            # JavaScript
└── assets/
    └── images/
        ├── logo-rectangle.jpg
        ├── logo-carre.jpg
        └── candidats/     # Photos des candidats
```

## 🚀 Déploiement sur GitHub Pages

### Étape 1 : Créer le dépôt GitHub

1. Allez sur [github.com](https://github.com) et connectez-vous
2. Cliquez sur "New repository"
3. Nommez le dépôt (ex: `montauban2026`)
4. Laissez en "Public"
5. Cliquez sur "Create repository"

### Étape 2 : Uploader les fichiers

**Option A - Via l'interface web GitHub :**
1. Dans votre nouveau dépôt, cliquez sur "uploading an existing file"
2. Glissez-déposez tous les fichiers du dossier `mgec-site`
3. Cliquez sur "Commit changes"

**Option B - Via Git en ligne de commande :**
```bash
cd mgec-site
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/VOTRE-USERNAME/montauban2026.git
git push -u origin main
```

### Étape 3 : Activer GitHub Pages

1. Allez dans les "Settings" du dépôt
2. Dans le menu latéral, cliquez sur "Pages"
3. Sous "Source", sélectionnez "Deploy from a branch"
4. Sélectionnez la branche "main" et le dossier "/ (root)"
5. Cliquez sur "Save"

Votre site sera accessible à : `https://VOTRE-USERNAME.github.io/montauban2026/`

### Étape 4 : Configurer un nom de domaine personnalisé (optionnel)

1. Achetez un domaine (ex: montauban2026.fr)
2. Dans les DNS du domaine, ajoutez un CNAME pointant vers `VOTRE-USERNAME.github.io`
3. Dans les settings GitHub Pages, ajoutez votre domaine dans "Custom domain"

## 🎨 Personnalisation

### Modifier les couleurs

Les couleurs sont définies dans `css/style.css` en variables CSS :

```css
:root {
    --jaune-mgec: #F5B81C;
    --rouge-mgec: #E63329;
    --vert-mgec: #2D8C4E;
    --violet-mgec: #6B3FA0;
}
```

### Ajouter des candidats

1. Ajoutez les photos dans `assets/images/candidats/`
2. Dans `index.html`, modifiez les blocs `.candidat-card`
3. Remplacez le placeholder par la balise `<img>`

Exemple :
```html
<div class="candidat-photo">
    <img src="assets/images/candidats/nom-candidat.jpg" alt="Nom du candidat">
</div>
<div class="candidat-info">
    <h3>Prénom NOM</h3>
    <p class="role">Tête de liste</p>
    <p class="description">Description du candidat.</p>
</div>
```

### Ajouter des événements

Dans `index.html`, dupliquez un bloc `.event-card` et modifiez les informations.

### Intégrer des vidéos Instagram

Remplacez le placeholder dans la section médias par :
```html
<iframe 
    src="https://www.instagram.com/p/CODE_DE_LA_VIDEO/embed" 
    frameborder="0" 
    allowfullscreen>
</iframe>
```

### Modifier l'adresse email

Recherchez et remplacez `gauche-ecolo-citoyenne@montauban26.fr` dans tous les fichiers.

## 📱 Réseaux sociaux

- Facebook : [facebook.com/montauban2026](https://www.facebook.com/montauban2026)
- Instagram : [@montauban2026](https://www.instagram.com/montauban2026)

## 📄 Licence

Ce site est créé pour la campagne MGEC. Tous droits réservés.

---

*Ensemble, construisons une ville plus juste, plus verte et plus démocratique !*
