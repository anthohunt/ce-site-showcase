> Showcase repository: the code and data of this project are private; this README describes it. / Dépôt vitrine : le code et les données de ce projet sont privés ; ce README le décrit.

# This site

My personal website, designed and built end to end by my web app pipeline.

## The problem

I want a visitor to understand in ten seconds what I can do: AI agents running in production, with proof that they work. The site serves two audiences: a potential client arriving from LinkedIn who wants to know in one minute whether I can help, and an AI agent developer who wants to understand a project, see its code and its demo. It also shows the path taken: the site itself is a project of the pipeline.

## How it works

- The web app pipeline starts from a specification: three user journeys and twelve stories, approved one by one.
- It produces an interactive mockup with a review layout: journeys on the left, shared comments anchored on the right.
- A Python script assembles the page from its parts (HTML body, scenes, animations, stories) and stamps a version number on it.
- A publishing script puts each version online under a new name and points a fixed link to the latest one, so nobody ever sees a cached version.
- A second version, without the review panels, shows the site as a visitor will see it.

## What is built

In progress: mockup online, not yet published at the domain root.

- Menu: Home, Portfolio, About, Resources.
- Home: an eye-shaped logo that follows the mouse, an entrance that zooms into the eye, tab changes shown as a blink; three trades (development, training, consulting), each with its own card.
- "Latest projects": four flagship projects, each with its video in a tile (60 s, 30 s, 20 s and 22 s) and a sheet that opens on click (video and descriptive card, figures taken from the repositories).
- Portfolio: 35 projects sorted into six chests, opened as a grid of four.
- Resources: free tools I share, and where I publish.
- French / English switch.

## What is public

The site mockup is visible online: <https://projets.ingevision.cloud/design/personal-website-2026-10-27-144755/site.html>. The code stays private until the final launch, when the repository will become public.

## Tech stack

- HTML, CSS and JavaScript
- GSAP 3.12.5 for animations
- Python to assemble the pages
- Bash for publishing

---

## Version française

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

En cours : maquette en ligne, pas encore publiée à la racine du domaine.

- Menu : Accueil, Portfolio, À propos, Ressources.
- Accueil : logo en forme d'œil qui suit la souris, entrée par un zoom dans l'œil, changement d'onglet par un clignement ; trois métiers (développement, formation, consulting), chacun avec sa carte.
- « Derniers projets » : quatre projets phares, chacun avec sa vidéo en tuile (60 s, 30 s, 20 s et 22 s) et une fiche qui s'ouvre au clic (vidéo et carte descriptive, chiffres repris des dépôts).
- Portfolio : 35 projets rangés dans six coffres, ouverts en grille de quatre.
- Ressources : outils gratuits que je partage, et où je publie.
- Bascule français / anglais.

## Ce qui est public

La maquette du site est visible en ligne : <https://projets.ingevision.cloud/design/personal-website-2026-10-27-144755/site.html>. Le code reste privé jusqu'à la mise en ligne finale, où le dépôt deviendra public.

## Pile technique

- HTML, CSS et JavaScript
- GSAP 3.12.5 pour les animations
- Python pour l'assemblage des pages
- Bash pour la publication
