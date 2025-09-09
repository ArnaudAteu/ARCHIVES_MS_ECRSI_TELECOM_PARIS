# Guide de contribution


Merci de contribuer à l'archive du MS Cybersécurité ! Voici les règles pour garder un dépôt clair, durable et sûr.


## Qui peut contribuer ?
Étudiant·es, alumni, équipes pédagogiques, invité·es — tant que le contenu est **diffusable publiquement** et respecte les licences.


## Types de contributions
- Notes de cours, fiches de révision, mindmaps
- Rapports de projets (avec code si open-source)
- Mémoires (si autorisation explicite de diffusion)
- Bibliographies commentées, liens de veille, jeux de données publics
- Modèles (LaTeX/Word/Marp), scripts utilitaires non sensibles


## Nommage & formats
- Dossiers : `promotions/2025/cours/cryptographie/`
- Fichiers : `YYYY-MM-Titre-court.md` ou `YYYY-MM-Titre-court.pdf`
- Mémoire : créer un dossier `NomPrenom-TitreCourt/` avec `memoire.pdf` et `metadata.yaml`
- Formats recommandés : **Markdown** pour texte, **PDF/A** pour documents finalisés
- Éviter les binaires lourds (>50 Mo). Utiliser **Git LFS** si nécessaire.


## Métadonnées (exemple `metadata.yaml` pour un mémoire)
```yaml
promotion: 2025
auteur: "Nom Prénom"
titre: "Titre du mémoire"
encadrants: ["Encadrant 1", "Encadrant 2"]
mots_cles: [crypto, sécurité]
licence: CC-BY-SA-4.0
url: "(optionnel)"
