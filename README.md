# SCIO Network — Outils pour l'entrepreneuriat

Produit web unifié regroupant deux outils complémentaires pour les structures d'accompagnement, PME et startups :

| Outil | Rôle | Chemin |
|---|---|---|
| **Accueil** | Page d'entrée commune présentant les deux outils | `/` |
| **SIEVE** | Filtre à idées pour projets agritech : 6 filtres, observations, résumé imprimable | `/idea-filter/` |
| **Toolbox IA & No-code** | 71 outils vérifiés pour le contexte algérien, 9 domaines, parcours guidé + catalogue filtrable | `/AI-nocode/` |

## Caractéristiques communes

- **Bilingue français / anglais** — bascule en un clic, interface et contenu des fiches traduits ; le choix est partagé entre les trois pages (`localStorage scio.lang`)
- **Mode clair / sombre** — bascule partagée également (`localStorage scio.theme`), avec détection de la préférence système au premier chargement
- **Identité visuelle unifiée** — palette « papier » chaleureuse à accent orange issue de SIEVE, déclinée en variante sombre ; typographies **Archivo** (titres, interface) et **Public Sans** (texte) issues de la Toolbox
- **Sans dépendance** — trois pages HTML autonomes (HTML/CSS/JS), aucune bibliothèque externe, hébergeables sur GitHub Pages

## Crédits

- **SIEVE** : Steve Gray ([stvg/SIEVE](https://github.com/stvg/SIEVE)) — adapté ici (polices, navigation commune, préférences partagées)
- **Toolbox IA & No-code** : SCIO Network — données synchronisées depuis la base officielle du projet (classeur « Panorama outils no-code / low-code / IA entrepreneurs 2026 »)

Prototype · novembre 2026
