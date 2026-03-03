# Portfolio AGIL/D - Instructions de Déploiement Rapide

## 🚀 Déploiement en 5 minutes avec Netlify (le plus simple)

### Étape 1 : Préparation
1. Assurez-vous que tous vos fichiers sont dans le dossier `agild-portfolio`
2. Vérifiez que les images et vidéos sont dans `src/images/`

### Étape 2 : Déploiement Netlify
1. Allez sur https://netlify.com
2. Créez un compte gratuit
3. Cliquez sur "New site from Git" ou "Drag and drop"
4. Glissez votre dossier `agild-portfolio` sur la page
5. Patientez 30 secondes...

### Étape 3 : C'est fini ! 🎉
- Votre site est en ligne avec une URL comme : `https://amazing-johnson-123456.netlify.app`
- Vous pouvez la personnaliser gratuitement

---

## 🐙 Déploiement avec GitHub Pages (recommandé)

### Étape 1 : Créer le repository GitHub
1. Allez sur https://github.com
2. Créez un nouveau repository : `agild-portfolio`
3. Cochez "Public" et "Add README"

### Étape 2 : Envoyer votre code
Ouvrez un terminal dans votre dossier projet :

```bash
# Initialiser Git
git init
git add .
git commit -m "Portfolio AGIL/D - Initial commit"

# Connecter à GitHub
git remote add origin https://github.com/VOTRE_USERNAME/agild-portfolio.git
git branch -M main
git push -u origin main
```

### Étape 3 : Activer GitHub Pages
1. Dans votre repository GitHub → Settings → Pages
2. Source : "Deploy from a branch"
3. Branch : "main" + dossier "/root"
4. Cliquez "Save"

### Étape 4 : Votre site est en ligne ! 🌐
URL : `https://VOTRE_USERNAME.github.io/agild-portfolio`

---

## ⚡ Vérifications avant déploiement

✅ **Test local** : Ouvrez `index.html` dans votre navigateur
✅ **Images** : Vérifiez que toutes les images s'affichent
✅ **Vidéos** : Testez la lecture des vidéos
✅ **Liens** : Vérifiez tous les liens externes
✅ **Responsive** : Testez sur mobile (redimensionnez la fenêtre)

---

## 🛠️ Si quelque chose ne marche pas

### Images qui ne s'affichent pas :
- Vérifiez les chemins dans `src="src/images/..."`
- Assurez-vous que les fichiers existent bien

### Vidéos qui ne jouent pas :
- Vérifiez les extensions `.mp4`
- Testez avec différents navigateurs

### Formulaire qui ne fonctionne pas :
- Vérifiez l'URL Formspree dans le JavaScript
- Testez avec une vraie adresse email

---

## 🎯 Après déploiement

1. **Partagez votre lien** sur LinkedIn, WhatsApp, etc.
2. **Demandez feedback** à vos contacts
3. **Surveillez les performances** avec Google Analytics
4. **Mettez à jour** régulièrement vos projets

## 🆘 Besoin d'aide ?

Si vous rencontrez un problème :
1. Notez le message d'erreur exact
2. Prenez une capture d'écran
3. Dites-moi l'étape où vous êtes bloqué

Je peux vous aider pour chaque étape du déploiement !
