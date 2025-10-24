# AMELIORATIONS.md

Liste argumentée de 10 améliorations proposées (priorité & raison)

### 1.  Mise en place d’un mode sombre / clair automatique
**Problème d’origine :** La page initiale n’avait qu’un thème clair, peu agréable en environnement sombre.  
**Amélioration :** Ajout d’un bouton de bascule de thème avec conservation de l’état via JavaScript.  
**Impact :** Amélioration de l’ergonomie et du confort visuel pour tous les utilisateurs, surtout sur mobile.

---

### 2. Amélioration de l’accessibilité (ARIA, contrastes, navigation clavier)
**Problème d’origine :** Manque de balises ARIA et contraste insuffisant entre texte et fond.  
**Amélioration :** Ajout d’`aria-labels`, de texte alternatif sur les images, et d’un lien “Aller au contenu principal”.  
**Impact :** Meilleure accessibilité pour les utilisateurs en situation de handicap et conformité avec les bonnes pratiques RGAA.

---

### 3. Réorganisation sémantique du code HTML
**Problème d’origine :** Structure désordonnée (divs sans rôle, titres non hiérarchisés).  
**Amélioration :** Utilisation correcte des balises `<header>`, `<main>`, `<section>`, `<footer>` et hiérarchie H1→H3.  
**Impact :** Amélioration de la compréhension du contenu par les moteurs de recherche et les lecteurs d’écran.

---

### 4. Mettre en place une gestion d’erreurs et de validation serveur
**Problème :** La validation du formulaire est uniquement côté client.  
**Amélioration proposée :** Ajouter un contrôle serveur ou une gestion d’erreurs simulée dans le fallback.  
**Impact :** Plus de fiabilité et prévention des soumissions incomplètes ou erronées.

---

### 5. Optimisation SEO et données structurées
**Problème d’origine :** Absence de balisage JSON-LD et balises meta incomplètes.  
**Amélioration :** Ajout de balises `meta title`, `meta description` et d’un script `FAQPage` conforme à Schema.org.  
**Impact :** Meilleure indexation Google et affichage enrichi dans les résultats de recherche.

---

### 6. Mise en place d’un plan de marquage et d’événements de tracking
**Problème d’origine :** Aucun suivi des interactions utilisateur.  
**Amélioration :** Ajout d’événements pour les clics sur les CTA (“Déposer une offre”, “Être rappelé”) et les questions de la FAQ.  
**Impact :** Meilleure mesure de l’engagement et des performances marketing.

---

### 7. Sécurisation basique des formulaires
**Problème d’origine :** Le formulaire initial n’avait pas de vérification côté client.  
**Amélioration :** Ajout d’une validation JavaScript et d’un fallback HTML pour garantir une soumission propre même hors HubSpot.  
**Impact :** Réduction des erreurs de saisie et amélioration de la fiabilité des données collectées.

---

### 8. Amélioration de la responsivité et de l’expérience mobile
**Problème d’origine :** Disposition fixe et mauvaise lisibilité sur écrans étroits.  
**Amélioration :** Réécriture des media queries pour adapter les blocs, boutons et tableaux sur mobile.  
**Impact :** Meilleure expérience utilisateur sur tous les supports (desktop, tablette, smartphone).

---

### 9. Réduction de la dette technique et standardisation du code
**Problème d’origine :** Code dispersé, non commenté, et difficile à maintenir.  
**Amélioration :** Nettoyage global, commentaires clairs et cohérence syntaxique (indentation, noms de classes).  
**Impact :** Code plus lisible, facile à faire évoluer et conforme aux bonnes pratiques front-end.

---

### 10. ♿ Mieux gérer les contrastes en mode sombre
**Problème :** Le gris du texte secondaire est un peu faible sur fond sombre.  
**Amélioration proposée :** Augmenter légèrement la luminosité des teintes (#9ca3af → #b0b6c2 par exemple).  
**Impact :** Meilleure lisibilité et conformité avec les ratios de contraste WCAG.
