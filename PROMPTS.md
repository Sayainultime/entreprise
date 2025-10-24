# PROMPTS.md

## Prompts utilisés avec ChatGPT
1) Génération de la structure HTML principale (sections entreprises).
Prompt résumé :
- "Transforme cette page étudiants en une page dédiée aux entreprises immobilières qui recrutent des alternants. Inclure : sommaire ancres, pourquoi recruter (3 preuves), tableau filières, formulaire HubSpot adapté pour entreprises (libellés), processus, FAQ 3 Q/R, JSON-LD, title/meta orientés SEO, plan de marquage minimal, accessibilité minimale."

2) Génération du JSON-LD FAQ.
Prompt résumé :
- "Génère un bloc JSON-LD FAQPage pour les 3 Q/R de la FAQ entreprises."

3) Rédaction du README.md et AMELIORATIONS.md (liste d'améliorations).

## Retour critique sur les sorties de l'IA

**Ce que j’ai accepté :**  
  La structure globale du code HTML, l’organisation hiérarchique des sections et la cohérence du contenu du site.  
  J’ai conservé la mise en page générale proposée, le sommaire avec ses ancres internes, la logique du formulaire Hubspot,  
  les tableaux descriptifs (matières, examens, rythme, débouchés) ainsi que la structure textuelle complète du BTS PI.  
  Sur le rendu site, j’ai gardé la présentation claire et le ton informatif d’origine, tout en validant les propositions cohérentes  
  comme l’ajout du balisage sémantique (titres structurés, listes bien hiérarchisées, cohérence du `<head>` et du `<body>`).

- **Ce que j’ai corrigé :**  
  J’ai supprimé ou reformulé les contenus trop lourds ou redondants (multiples `<strong>`, `<br>` inutiles, styles inline).  
  J’ai amélioré l’accessibilité du code (ajout d’un `noscript` pour Hubspot, vérification des balises ARIA, titres logiques).  
  Sur le rendu du site, j’ai ajusté les espacements, la hiérarchie des blocs et la lisibilité des tableaux pour éviter les décalages.  
  Le ton général a été harmonisé : phrases simplifiées, uniformisation du vocabulaire et meilleure cohérence visuelle sur le site.

- **Ce que j’ai rejeté :**  
  J’ai retiré les éléments trop promotionnels ou non vérifiables (ex. chiffres invérifiés, formulations trop commerciales).  
  Certains styles et classes décoratives non utiles à la structure ont été supprimés.  
  J’ai également écarté les répétitions d’appels à l’action ou de liens redondants.  
  Sur la partie affichée du site, j’ai éliminé tout ce qui perturbait la lecture (boutons en doublon, blocs trop chargés).  