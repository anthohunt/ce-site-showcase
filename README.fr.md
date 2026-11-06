[English](README.md) · **Français**

**Anthony Hunt** · [Fiche du projet sur ingevision.cloud](https://ingevision.cloud/?p=ce-site) · [LinkedIn](https://www.linkedin.com/in/anthony-hunt-3948a9196) · [Profil GitHub](https://github.com/anthohunt)

> Dépôt vitrine : le code et les données de ce projet sont privés ; ce README le décrit.

# Ce site

Mon site personnel, conçu et construit de bout en bout par ma pipeline de création d'applications web.

## Le problème

Je veux qu'un visiteur comprenne en dix secondes ce que je sais faire : des agents IA qui tournent en production, avec la preuve que ça marche. Le site s'adresse à deux publics : un client potentiel qui arrive depuis LinkedIn et veut savoir en une minute si je peux l'aider, et un développeur d'agents IA qui veut comprendre un projet, voir son code et sa démo. C'est aussi la vitrine du chemin suivi : le site lui-même est un projet de la pipeline.

## Comment ça marche

- La pipeline web app part d'un cahier des charges : trois parcours utilisateur et douze histoires, validés un par un.
- Elle produit une maquette interactive avec un gabarit de revue : parcours à gauche, commentaires partagés ancrés à droite.
- Un script Python assemble la page à partir de ses morceaux (corps HTML, scènes, animations, histoires) et y inscrit un numéro de version.
- Un script de publication met en ligne chaque version sous un nom neuf et fait pointer un lien fixe vers la dernière, pour qu'on ne voie jamais une version en cache.
- Une seconde version, sans les panneaux de revue, montre le site tel qu'un visiteur le verra.

## Ce qui est construit

En ligne depuis le 4 novembre 2026 : Accueil et Portfolio sont publiés ; À propos et Ressources sont en chantier.

- Menu : Accueil, Portfolio, À propos, Ressources.
- Accueil : logo en forme d'œil qui suit la souris, entrée par un zoom dans l'œil, changement d'onglet par un clignement ; trois métiers (développement, formation, consulting), chacun avec sa carte.
- « Derniers projets » : quatre projets phares, chacun avec sa vidéo en tuile (60 s, 30 s, 20 s et 22 s) et une fiche qui s'ouvre au clic (vidéo et carte descriptive, chiffres repris des dépôts).
- Portfolio : 35 projets rangés dans six coffres, ouverts en grille de quatre.
- Ressources : outils gratuits que je partage, et où je publie.
- Bascule français / anglais.

## Ce qui est public

Le site est en ligne : <https://ingevision.cloud>. Le code reste privé.

## Pile technique

- HTML, CSS et JavaScript
- GSAP 3.12.5 pour les animations
- Python pour l'assemblage des pages
- Bash pour la publication
