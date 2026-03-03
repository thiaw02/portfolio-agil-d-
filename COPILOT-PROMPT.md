# 🚀 PROMPT COMPLET GITHUB COPILOT - Portfolio Cabinet Consultance

**Utilisation:** Copiez ce prompt dans GitHub Copilot (ou ChatGPT) pour générer un site portfolio complet.

---

## PROMPT COPILOT COMPLET

```
Je veux créer un site portfolio professionnel pour un cabinet de consultance.

INFORMATIONS GÉNÉRALES:
- Nom du cabinet: AGIL/D (Appui à la Gestion des Initiatives Locales pour le Développement)
- Directeur: Ousmane Thiaw
- Localisation: Dakar, Sénégal
- Email: agildev65@gmail.com
- Téléphone WhatsApp: +221 775264241
- Spécialisations: Étude & Diagnostic, Planification, Mise en œuvre, Suivi & Évaluation, Formation, Ingénierie sociale et économique

EXIGENCES TECHNIQUES:
- HTML5 + Tailwind CSS via CDN (https://cdn.tailwindcss.com)
- Pas de frameworks JavaScript (vanilla JS seulement pour menu mobile)
- Pas de npm, pas d'outils de build
- 100% responsive (mobile, tablette, desktop)
- Smooth scroll sur la navigation
- Effets hover subtils et transitions 300ms
- Palette couleurs: Bleu (#1e3a8a, #2563eb) et blanc uniquement
- Typographie professionnelle sans serif

STRUCTURE DU SITE:

### 1. NAVBAR (Sticky)
- Fond blanc, ombre légère
- Logo "AGIL/D" en bleu foncé, cliquable vers #hero
- Navigation horizontale: À propos | Services | Projets | Témoignages | Contact
- Underline blue hover effect sur les liens
- Menu burger responsive sur mobile
- Smooth scroll CSS (scroll-behavior: smooth)

### 2. HERO SECTION
- Titre gros et gras: "AGIL/D"
- Sous-titre: "Appui à la Gestion des Initiatives Locales pour le Développement"
- Description professionnelle du cabinet
- Bouton CTA: "Télécharger le CV" → /cv-ousmane-thiaw.pdf
- Fond bleu (#2563eb), texte blanc
- Padding py-32
- Texte centré
- Bouton avec hover effect (darker color + elevation)

### 3. SECTION À PROPOS
- Titre centré: "À propos"
- Grid 2 colonnes desktop, 1 mobile
- Colonne 1: Présentation du cabinet AGIL/D et expertise
- Colonne 2: Information sur le directeur Ousmane Thiaw avec accent bleu
- Fond blanc, padding py-20
- Texte gris foncé (#1f2937)

### 4. SECTION SERVICES
- Titre centré: "Services"
- 6 cartes services en grille responsive (3 colonnes desktop, 1 mobile)
- Chaque carte contient:
  - Icône SVG inline (48x48px, bleu)
  - Titre en bleu gras
  - Description détaillée et explicite (3-4 lignes valorisant le cabinet)
  - Fond blanc, shadow-md, rounded-xl
  - Hover effect: translateY(-4px) + shadow augmentée
- Fond gris clair (bg-gray-50), padding py-20
- Services:
  1. Étude & Diagnostic - Analyses approfondies des contextes locaux
  2. Planification - Plans stratégiques et planification participative
  3. Mise en œuvre - Accompagnement opérationnel des projets
  4. Suivi & Évaluation - Systèmes de suivi et évaluations d'impact
  5. Formation - Renforcement des capacités et formations techniques
  6. Ingénierie S&E - Structuration de filières et création d'emplois

### 5. SECTION PROJETS/RÉALISATIONS
- Titre centré: "Projets"
- Grid 3 colonnes desktop, 1 mobile
- 3 cartes de projets avec:
  - Image placeholder (dégradé bleu from-blue-400 to-blue-600, h-48) avec icône SVG
  - Titre du projet (font-bold)
  - Description courte mais impactante avec chiffres et résultats
  - Bouton "Voir plus" (btn-primary)
  - Border gris léger
  - Hover effect: scale(1.02) + shadow
- Fond blanc, padding py-20
- Projets:
  1. "Diagnostic & Planification Stratégique - Sine Saloum"
     Description: "Intervention complète d'analyse des potentialités de développement dans la région du Sine Saloum. AGIL/D a conduit des études multidisciplinaires (agriculture, tourisme, artisanat, peche) avec implication des communautés locales. Production d'un plan de développement territorial participatif sur 5 ans, intégrant les priorités des jeunes et des femmes. Ce projet a permis la mobilisation de financement pour les initiatives prioritaires identifiées."
  
  2. "Structuration de Filière Agricole - Casamance"
     Description: "Project d'envergure visant la structuration d'une filière maraîchère et d'agro-transformation en Casamance. AGIL/D a facilité l'organisation de 450 producteurs en GIE, conduit des formations techniques en production durable et transformation de produits, et accompagné l'accès aux marchés. Augmentation de 35% des revenus des producteurs et création de 120 emplois directs. Le cabinet assure maintenant le suivi-évaluation et l'appui à la pérennité des structures mises en place."
  
  3. "Programme d'Appui à la Gouvernance Locale - Niani"
     Description: "Intervention dans le renforcement des capacités des collectivités territoriales dans le Niani. AGIL/D a appuyé l'elaboration de plans de développement local participatifs, le renforcement des systèmes de planification budgétaire, et conduit des formations en gouvernance et gestion transparente de ressources. Création de mécanismes de suivi participatif et d'espaces de dialogue. 12 collectivités ont amélioré leur capacité de gestion et leur impact en termes de services publics locaux."

### 6. SECTION TÉMOIGNAGES
- Titre centré: "Témoignages"
- Grid 2 colonnes desktop, 1 mobile
- 2 cartes témoignages avec:
  - Avatar circulaire (w-12 h-12, fond bleu avec initiales en blanc)
  - Nom et titre du client
  - Citation en italique
  - 5 étoiles jaunes (★★★★★)
  - Border gauche bleu (border-l-4 border-blue-600)
  - Fond blanc, shadow-md, rounded-xl
  - Hover effect: translateY(-4px)
- Fond gris clair, padding py-20
- Témoignage 1:
  - Nom: Jean Dupuis
  - Titre: Responsable Projet
  - Citation: "AGIL/D a été un partenaire strategic essentiel dans la réussite de notre initiative de développement local. Leur expertise en diagnostic et planification a transformé notre approche."
  
- Témoignage 2:
  - Nom: Marie Martin
  - Titre: Directrice ONG
  - Citation: "L'accompagnement fourni par AGIL/D en ingénierie sociale a permis une vraie structuration de nos activités. Résultats probants et équipe professionnelle."

### 7. SECTION CONTACT
- Titre centré: "Contact"
- Grid 2 colonnes desktop, 1 mobile
- Colonne 1: "Prenons contact" avec 3 blocs info:
  - Email (icône envelope) - agildev65@gmail.com
  - Téléphone (icône phone) - +221 775264241
  - Localisation (icône map pin) - Dakar, Sénégal
  - Icônes SVG bleu
- Colonne 2: Formulaire de contact
  - Champs: Nom, Email, Sujet, Message (textarea)
  - Bouton "Envoyer le message" (full width, btn-primary)
  - Fond gris clair (bg-gray-50)
  - Inputs avec focus border-blue-600
- Fond blanc, padding py-20

### 8. FOOTER
- Fond bleu très foncé (bg-blue-900)
- Texte blanc
- Grid 3 colonnes desktop, 1 mobile:
  - Colonne 1: Logo AGIL/D + description courte
  - Colonne 2: Liens "Services" (Étude & Diagnostic, Planification, Mise en œuvre, Suivi & Évaluation)
  - Colonne 3: Liens "Légal" (Politique de confidentialité, Conditions d'utilisation, Mentions légales)
- En bas: ligne de copyright avec bordure top blue-800
- Padding py-12
- Liens hover: text-white transition

STYLES GLOBAUX:
- Body: bg-white, text-gray-900, font-sans
- Container max width: max-w-6xl, centered avec mx-auto
- Responsive padding: px-4 sm:px-6 lg:px-8
- Cartes: rounded-xl, shadow-md
- Border gris: border-gray-200, border-gray-300
- Transitions: duration-300, ease
- Titles: font-bold, text-gray-900
- Accent color: #2563eb (bleu)

JAVASCRIPT REQUIS:
- Menu mobile toggle (burger button + click handler)
- Fermeture auto du menu au clic sur un lien
- Smooth scroll natif CSS (scroll-behavior: smooth)

DESIGN RECOMMANDATIONS:
- Design minimaliste et épuré
- Style professionnel type cabinet consultance
- Espacement propre et harmonieux
- Pas d'animations trop complexes
- Contraste texte/fond optimal pour accessibilité
- Mobile-first responsive design

RETOURNER:
Code HTML5 complet et unique, prêt à copier-coller, sans dépendances externes sauf Tailwind CDN via <script>.
```

---

## COMMENT UTILISER CE PROMPT

### Option 1: GitHub Copilot (VS Code)
1. Ouvrez VS Code
2. Appuyez sur `Ctrl+Shift+P` (Cmd+Shift+P sur Mac)
3. Tapez "Copilot: Open Prompt"
4. Collez le prompt ci-dessus
5. Cliquez sur "Generate" ou appuyez sur Enter

### Option 2: ChatGPT / Claude
1. Allez sur chat.openai.com ou claude.ai
2. Ouvrez un nouveau chat
3. Collez le prompt complet
4. Attendez que l'IA génère le code HTML
5. Copiez le code généré dans votre fichier index.html

### Option 3: Copilot Chat (VS Code - Plus efficace)
1. Ouvrez VS Code
2. Cliquez sur l'icône Copilot en bas à droite
3. Ouvrez la fenêtre "Copilot Chat"
4. Collez le prompt
5. Let Copilot generate le code

---

## PROMPT MODIFICATIONS POSSIBLES

### Si vous voulez personnaliser:

**Pour changer les couleurs:**
```
Remplacez définition couleur bleu par votre teinte préférée
Ex: bleu → vert, rouge, purple, etc.
```

**Pour ajouter plus de projets:**
```
Ajoutez des cartes projet selon même structure (titre + description + chiffres clés)
```

**Pour changer le nombre de services:**
```
Modifiez la liste des 6 services à votre convenance
Gardez descriptif détaillé et valorisant
```

**Pour ajouter/retirer des sections:**
```
Demandez dans le prompt: "Ajoute une section Blog" ou "Retire la section Témoignages"
Spécifiez la structure et le contenu souhaité
```

---

## INTÉGRATION AVEC VOS DONNÉES

Après génération du code, vous devez:

1. **Télécharger CV**
   - Mettez votre CV dans `/public/cv-ousmane-thiaw.pdf`
   - Ou mettez le PDF dans le même dossier et changez la route dans le bouton CTA

2. **Images réelles**
   - Remplacez les placeholders gradient par des images réelles
   - Optimisez les images (JPEG/WebP compressés)

3. **Contenu dynamique**
   - Finalisez les textes des services
   - Ajoutez plus de projets si nécessaire
   - Mettez à jour les témoignages

4. **Formulaire de contact**
   - Intégrez un service backend (Formspree, Netlify Forms, EmailJS, etc.)
   - Ou utilisez un formulaire statique avec redirection email

5. **Déploiement**
   - Hébergez sur Netlify, Vercel, GitHub Pages, ou autre
   - Configurez domaine custom
   - Activez HTTPS

---

## CHECKLIST APRÈS GÉNÉRATION

- ✅ Code généré et copié dans index.html
- ✅ Tailwind CDN chargé correctement
- ✅ Site s'affiche sans erreur dans le navigateur
- ✅ Navigation smooth scroll fonctionne
- ✅ Menu mobile responsive
- ✅ Tous les effets hover et transitions fonctionnent
- ✅ Contenu révisé et validé
- ✅ Liens fonctionnels
- ✅ Formulaire contact intégré (backend)
- ✅ CV téléchargeable
- ✅ Testé sur mobile, tablette, desktop
- ✅ Prêt pour déploiement

---

## RESOURCES UTILES

**Tailwind CSS:**
- Documentation: https://tailwindcss.com/docs
- Color Palette: https://tailwindcss.com/docs/customizing-colors
- Responsive: https://tailwindcss.com/docs/responsive-design

**Icônes SVG (Heroicons):**
- Library: https://heroicons.com/
- Tous les icônes utilisés sont gratuits et open-source

**Déploiement gratuit:**
- Netlify: https://www.netlify.com/
- Vercel: https://vercel.com/
- GitHub Pages: https://pages.github.com/

**Formulaire Contact (Service gratuit):**
- Formspree: https://formspree.io/
- Netlify Forms: https://www.netlify.com/products/forms/
- EmailJS: https://www.emailjs.com/

---

**Créé:** 25 février 2026  
**Prompt Version:** 1.0  
**Langage:** Français
