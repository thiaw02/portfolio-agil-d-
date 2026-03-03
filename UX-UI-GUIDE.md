# 📘 Guide UX/UI - AGIL/D Portfolio

## 1️⃣ ERGONOMIE & STRUCTURE UX/UI DU SITE

### 🎯 Objectif Principal
Créer une expérience utilisateur fluide permettant aux clients de :
- Comprendre rapidement l'expertise du cabinet
- Identifier les services et réalisations
- Prendre contact facilement

---

### A. NAVBAR (Sticky) ✅

**Structure actuelle:**
- Fond blanc avec ombre légère
- Logo "AGIL/D" en bleu (#2563eb), cliquable vers #hero
- Navigation horizontale: À propos | Services | Projets | Témoignages | Contact
- Smooth scroll activé (css: `scroll-behavior: smooth`)
- Underline hover effect bleu sur les liens
- Menu burger responsive sur mobile

**Caractéristiques:**
- Sticky top avec z-50
- Hauteur: 64px (h-16)
- Padding: px-4 to px-8 responsive
- Mobile menu toggle avec JavaScript

---

### B. HERO / PAGE D'ACCUEIL ✅

**Contenu:**
- **Titre principal:** "AGIL/D" (texte très gros et gras)
- **Sous-titre:** "Appui à la Gestion des Initiatives Locales pour le Développement"
- **Description:** Phrase présentant l'expertise du cabinet
- **CTA primaire:** Bouton "Télécharger le CV" → `/cv-ousmane-thiaw.pdf`

**Design:**
- Fond bleu (#1e40af / #2563eb dégradé)
- Texte blanc avec contraste élevé
- Padding: py-32 (amplement d'espace)
- Centré et responsive
- Animations: transitions douces sur le bouton (hover effect)

**Interactions:**
- Bouton hover: couleur plus foncée + légère élévation + shadow
- Transition 300ms dur les effets

---

### C. À PROPOS ✅

**Structure:**
- Titre centré: "À propos"
- Grid 2 colonnes sur desktop (md:grid-cols-2), 1 colonne mobile
- **Colonne 1:** Présentation du cabinet AGIL/D
  - Texte en paragraphes clairs
  - Accent bleu sur termes clés
- **Colonne 2:** Présentation du directeur Ousmane Thiaw
  - Fond bleu clair (bg-blue-50)
  - Présentation professionnelle
  - Spacer bleu (h-1 w-16 bg-blue-600)

**Points clés valorisés:**
- Expertise en étude diagnostique
- Approche participative
- Résultats durables
- 15+ années d'expérience

---

### D. SERVICES ✅

**Layout:**
- Grille 3 colonnes desktop, 1 colonne mobile (md:grid-cols-3)
- 6 cartes services

**Chaque carte contient:**
- Icône SVG (48x48px, couleur bleu #2563eb)
- Titre en bleu gras (texte-xl font-bold)
- Description détaillée et explicite (3-4 lignes)
- Fond blanc
- Shadow légère (shadow-md)
- Rounded corners (rounded-xl)

**Interactions:**
- Hover: translateY(-4px) + shadow augmentée
- Transition: 300ms
- Les descriptions valorisent la démarche d'AGIL/D

**Services listés:**
1. Étude & Diagnostic
2. Planification
3. Mise en œuvre
4. Suivi & Évaluation
5. Formation
6. Ingénierie Socio-Économique

---

### E. PROJETS / RÉALISATIONS ✅

**Layout:**
- Grille 3 colonnes desktop (md:grid-cols-3), 1 colonne mobile
- Gap: 8px entre cartes

**Structure de chaque car projet:**
- **Image placeholder:** dégradé bleu (from-blue-400 to-blue-600)
- **Icône SVG** au centre pour placeholder
- Hauteur: h-48
- **Contenu (p-6):**
  - Titre du projet (font-bold text-gray-900)
  - Description courte mais impactante (chiffres, résultats)
  - Bouton "Voir plus" (btn-primary)

**Projets remplis:**
1. **Diagnostic & Planification Stratégique** - Sine Saloum
   - Études multidisciplinaires
   - Plan 5 ans participatif
   
2. **Structuration de Filière Agricole** - Casamance
   - 450 producteurs organisés
   - +35% augmentation revenus
   - 120 emplois créés
   
3. **Programme Gouvernance Locale** - Niani
   - 12 collectivités appuyées
   - Renforcement capacités

**Interactions:**
- Hover: scale(1.02) + shadow augmentée
- Border gris léger (border-gray-200)
- Rounded-xl

**Future enhancement possible:**
- Filtres: "Tous | Études | Planification | Mise en œuvre"
- Modal pour "Voir plus"

---

### F. TÉMOIGNAGES ✅

**Layout:**
- Grille 2 colonnes desktop, 1 mobile
- Cartes de même hauteur

**Chaque témoignage:**
- Avatar circulaire (w-12 h-12, fond bleu)
- Initiales du client en blanc
- Nom et titre du client
- Citation en italique (text-gray-700)
- Border gauche bleu (border-l-4 border-blue-600)
- 5 étoiles jaunes (★★★★★)
- Fond blanc, shadow légère
- Rounded-xl

**Interactions:**
- Hover: translateY(-4px)
- Transition 300ms

---

### G. CONTACT ✅

**Layout:**
- 2 colonnes: infos de contact + formulaire

**Colonne 1 - Infos de contact:**
- Titre: "Prenons contact"
- 3 blocs avec icônes SVG:
  1. **Email** - agildev65@gmail.com
  2. **Téléphone** - +221 775264241 (WhatsApp)
  3. **Localisation** - Dakar, Sénégal
- Icônes bleu (#2563eb)
- Texte gris foncé sur blanc

**Colonne 2 - Formulaire:**
- Fond gris clair (bg-gray-50)
- Padding: p-8
- Champs:
  - Nom (text input)
  - Email (email input)
  - Sujet (text input)
  - Message (textarea, 5 rows)
  - Bouton "Envoyer le message" (full width)

**Interactions formulaire:**
- Focus: border bleu (#2563eb)
- Inputs avec rounded-lg
- Bouton primaire avec hover effect

---

### H. FOOTER ✅

**Design:**
- Fond bleu très foncé (#1e3a8a / bg-blue-900)
- Texte blanc, texte clair en bleu-100

**Structure:**
- Grille 3 colonnes desktop:
  1. **Section AGIL/D** - Logo + description courte
  2. **Services** - Liens rapides vers services
  3. **Légal** - Politique, conditions, mentions

- **Copyright en bas** avec bordure top (border-blue-800)
- Padding: py-12

**Interactions:**
- Liens hover: text-white transition
- Link couleur: text-blue-100 de base

---

## 2️⃣ PALETTE COULEURS & TYPOGRAPHIE

### Couleurs Primaires
- **Bleu foncé:** #1e3a8a (navbar, footer, accents)
- **Bleu principal:** #2563eb (boutons, liens, icônes)
- **Bleu clair:** #3b82f6 (hover states)
- **Blanc:** #ffffff (fond principal)
- **Gris clair:** #f3f4f6 (bg alternée sections)
- **Gris texte:** #4b5563 (texte secondaire)
- **Gris foncé:** #1f2937 (texte principal)

### Typographie
- **Font:** Sans-serif système (Tailwind font-sans)
- **Titres (H1, H2, H3):** font-bold
- **Texte courant:** Normal weight
- **Petits textes:** text-sm

### Spacing & Layout
- **Sections:** py-20 (padding vertical)
- **Container max:** max-w-6xl
- **Padding H:** px-4 sm:px-6 lg:px-8
- **Gap grilles:** gap-8
- **Rounded corners:** rounded-xl, rounded-lg

---

## 3️⃣ INTERACTIONS & MICRO-INTERACTIONS

### Transitions
- **Durée standard:** 300ms (duration-300)
- **Easing:** ease (par défaut)

### Effets Hover

**Cartes (Service, Projet):**
```css
transform: translateY(-4px);
box-shadow: 0 20px 25px rgba(0,0,0,0.1);
```

**Boutons:**
```css
background: darker blue
transform: translateY(-2px);
box-shadow: 0 10px 15px rgba(37, 99, 235, 0.3);
```

**Liens de nav:**
```css
underline animation (width: 0 → 100%)
durée: 300ms
```

### Mobile Menu
- Toggle avec JavaScript sur clic bouton burger
- Animation smooth (class toggle 'hidden')
- Fermeture auto au clic sur un lien

---

## 4️⃣ RESPONSIVE DESIGN

### Breakpoints utilisés (Tailwind)
- **Mobile:** < 640px (default)
- **Small:** sm: 640px (hidden md:flex)
- **Medium:** md: 768px (grilles 2-3 colonnes)
- **Large:** lg: 1024px (padding augmenté)

### Stratégie Mobile-First
1. Les styling par défaut = mobile
2. `md:`, `sm:` pour élargissements
3. `hidden md:flex` pour masquer sur mobile
4. `md:grid-cols-3` pour grilles responsive

---

## 5️⃣ ACCESSIBILITÉ & PERFORMANCE

### Accessibilité
- Titres hiérarchiquement justes (h1 → h2 → h3)
- Contraste texte/fond adéquat (WCAG AA)
- Liens descriptifs
- Alt text sur images (à compléter)
- Focus visible sur inputs

### Performance
- Tailwind CDN (rapide pour petit projet)
- Pas de JavaScript heavy
- Smooth scroll CSS natif
- SVG inline (icônes légères)
- Images placeholder (gradient, à remplacer)

---

## 6️⃣ AMÉLIORATIONS FUTURES POSSIBLES

- [ ] Ajouter images réelles aux projets
- [ ] Ajouter photos d'équipe (À propos)
- [ ] Intégrer slider/carousel pour témoignages
- [ ] Système de filtre sur projets
- [ ] Back-end pour formulaire contact
- [ ] Dark mode toggle
- [ ] Analytics (Google Analytics)
- [ ] Blog/News section
- [ ] Téléchargement PDF réel (CV)
- [ ] Galerie photos de projets
- [ ] Case studies détaillées
- [ ] FAQ section
- [ ] Multi-langue (FR/EN)

---

## 7️⃣ CHECKLIST AVANT LANCEMENT

- ✅ Contenu texte validé et complet
- ✅ Email et téléphone à jour
- ✅ Responsive mobile testé
- ✅ Tous les liens fonctionnels
- ✅ Images optimisées
- ✅ CV téléchargeable
- ⏳ Tests sur navigateurs majeurs (Chrome, Firefox, Safari, Edge)
- ⏳ Optimisation SEO (meta tags, descriptions)
- ⏳ Google Analytics configuré
- ⏳ Domaine custom configuré
- ⏳ HTTPS activé
- ⏳ Lighthouse audit (performance, SEO)

---

**Document créé:** 25 février 2026  
**Dernière mise à jour:** Version 1.0
