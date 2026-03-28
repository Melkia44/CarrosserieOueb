Tu es un designer frontend senior et expert UX/UI. Crée un site vitrine 
one-page en HTML/CSS/JS pour un garage carrossier indépendant français.

---

### CONTEXTE MÉTIER
- Garage artisanal, spécialisé en carrosserie, peinture et remise en état
- Clientèle locale : particuliers et professionnels
- Valeurs à transmettre : savoir-faire, fiabilité, transparence, proximité
- Ton : professionnel mais accessible, pas corporate

---

### HEURISTIQUES DE NIELSEN (à respecter impérativement)
1. Visibilité de l'état du système → feedback visuels sur les interactions 
   (hover, focus, états actifs)
2. Correspondance avec le monde réel → langage clair, icônes reconnaissables, 
   pas de jargon
3. Contrôle utilisateur → navigation accessible depuis n'importe quelle section, 
   lien retour haut de page
4. Cohérence et standards → design system uniforme (couleurs, typo, espacements)
5. Prévention des erreurs → formulaire de contact avec validation inline
6. Reconnaissance plutôt que rappel → menu sticky, labels visibles, CTA explicites
7. Flexibilité → accessible mobile-first, touch-friendly
8. Esthétique et design minimaliste → chaque élément a un rôle, rien de décoratif inutile
9. Aide à la récupération d'erreurs → messages d'erreur formulaire clairs et humains
10. Aide et documentation → section FAQ courte ou tooltip sur les services

---

### SECTIONS DU SITE (dans cet ordre)
1. **Hero** — Image plein écran ambiance garage/atelier, titre accrocheur, 
   CTA "Demander un devis gratuit"
2. **Services** — Carrosserie, peinture, débosselage, remise en état après 
   sinistre (4 cards avec icônes)
3. **Pourquoi nous choisir** — 3 arguments chocs : rapidité, garantie travaux, 
   devis transparent
4. **Galerie avant/après** — 4 exemples avec slider ou toggle 
   (effet "reveal" avant/après)
5. **Témoignages clients** — 3 avis avec note étoiles
6. **Contact & Devis** — Formulaire simple (nom, téléphone, type de réparation, 
   message) + adresse + Google Maps embed placeholder
7. **Footer** — Horaires, réseaux sociaux, mentions légales

---

### DIRECTION ESTHÉTIQUE
- Style : industriel-moderne avec une touche premium (pas cheap, pas clinique)
- Typographie : titre display percutant (ex: Bebas Neue, Barlow Condensed) 
  + corps lisible (ex: DM Sans, Figtree) — charger via Google Fonts
- Animations : reveal au scroll (Intersection Observer), hover sur les cards, 
  parallaxe légère sur le hero
- Mobile-first, responsive breakpoints à 768px et 1200px
- Fond hero : gradient sombre ou image placeholder avec overlay

---

### CONTRAINTES TECHNIQUES
- Un seul fichier HTML autonome (CSS et JS inline ou en balises <style>/<script>)
- Pas de framework externe (vanilla JS uniquement)
- Les images utilisent des placeholders réalistes (picsum.photos ou unsplash source)
- Le formulaire fait une validation JS côté client avec feedback visuel
- Accessibilité de base : balises sémantiques, aria-labels sur les boutons, 
  contraste WCAG AA minimum

---

### CE QUI DOIT RENDRE LE SITE MÉMORABLE
- L'effet avant/après sur la galerie (slider drag ou toggle button)
- Un compteur animé (ex: "+500 véhicules remis en état", "15 ans d'expérience")
- Le CTA "Devis gratuit" visible en permanence (sticky bar ou bouton flottant)
- Une typographie display XL dans le hero qui impose l'autorité du garage

---

Génère le code complet, commenté aux endroits clés, 
prêt à être ouvert dans un navigateur.