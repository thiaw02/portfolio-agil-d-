# Déploiement du Portfolio AGIL/D

## 🚀 Méthodes de déploiement

### Option 1 : GitHub Pages (Recommandé - Gratuit)

1. **Créer un compte GitHub** si vous n'en avez pas
2. **Créer un nouveau repository** : `agild-portfolio`
3. **Initialiser Git** dans votre projet :
```bash
git init
git add .
git commit -m "Initial commit - Portfolio AGIL/D"
```

4. **Connecter votre repository** :
```bash
git remote add origin https://github.com/votre-username/agild-portfolio.git
git branch -M main
git push -u origin main
```

5. **Activer GitHub Pages** :
   - Allez dans Settings → Pages
   - Source : "Deploy from a branch"
   - Branch : "main" et dossier "/root"
   - Save

6. **Votre site sera disponible** : `https://votre-username.github.io/agild-portfolio`

### Option 2 : Netlify (Très facile - Gratuit)

1. **Créer un compte Netlify** : https://netlify.com
2. **Glisser-déposer votre dossier** `agild-portfolio` sur Netlify
3. **Votre site est immédiatement en ligne** avec une URL aléatoire
4. **Personnaliser le domaine** si souhaité

### Option 3 : Vercel (Moderne - Gratuit)

1. **Créer un compte Vercel** : https://vercel.com
2. **Importer votre projet** depuis GitHub ou glisser-déposer
3. **Déploiement automatique** à chaque modification

### Option 4 : Firebase Hosting (Google - Gratuit)

1. **Installer Firebase CLI** :
```bash
npm install -g firebase-tools
```

2. **Initialiser Firebase** :
```bash
firebase login
firebase init hosting
```

3. **Déployer** :
```bash
firebase deploy
```

## 📋 Avant de déployer

### Vérifications importantes :
- ✅ Toutes les images et vidéos sont dans `src/images/`
- ✅ Les liens vers les médias sont corrects
- ✅ Le formulaire de contact fonctionne
- ✅ Le responsive design fonctionne sur mobile
- ✅ Les animations et interactions fonctionnent

### Optimisations recommandées :
- Compresser les images (WebP si possible)
- Minifier le CSS/JS
- Ajouter un favicon
- Configurer le SEO (meta tags)

## 🔧 Configuration recommandée

### Pour GitHub Pages :
Ajouter un fichier `.nojekyll` vide à la racine pour éviter les problèmes de traitement Jekyll.

### Pour tous les hébergeurs :
- Assurez-vous que les chemins des ressources sont relatifs
- Vérifiez que les vidéos peuvent être lues en streaming

## 🌐 Domaine personnalisé (Optionnel)

Après déploiement, vous pouvez :
- Acheter un domaine (.sn, .com, etc.)
- Configurer les DNS vers votre hébergeur
- Mettre en place HTTPS (généralement gratuit)

## 📊 Monitoring

Utilisez Google Analytics pour suivre :
- Nombre de visiteurs
- Pages les plus vues
- Temps de chargement
- Sources de trafic

## 🎯 Prochaines étapes

1. **Choisir une méthode** (GitHub Pages recommandé)
2. **Suivre les étapes** ci-dessus
3. **Tester le site** en ligne
4. **Partager le lien** avec vos contacts
5. **Mettre à jour** régulièrement

Besoin d'aide pour une étape spécifique ? Dites-moi quelle méthode vous préférez !
