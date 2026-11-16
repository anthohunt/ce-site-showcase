[English](README.md) · **Français**

# ingevision.cloud

**Mon site, construit et entretenu par des agents IA.** Chaque changement passe par une maquette que je valide, et cinq agents repassent sur le site en ligne chaque nuit.

[![Arrivée depuis LinkedIn, puis l'accueil, le portfolio, le dépôt d'un projet et la page de l'équipe de nuit (cliquer pour la vidéo complète)](docs/demo.gif)](https://drive.google.com/file/d/1dYCj_mHaxn5QUMNkSFLy1lda-ZtOutVx/view)

*Arrivée depuis un autre site, puis Accueil, Portfolio, le dépôt d'un projet et l'équipe de nuit. [Vidéo complète (1 min 27)](https://drive.google.com/file/d/1dYCj_mHaxn5QUMNkSFLy1lda-ZtOutVx/view)*

## Utilisation

- **Accueil.** Un logo en forme d'œil suit la souris ; le zoom d'ouverture ne joue que pour un visiteur venu d'un autre site. Trois métiers : développement, formation, consulting.
- **Portfolio.** Quatre projets phares, puis 25 projets rangés dans six coffres. Un clic sur un projet ouvre son dépôt GitHub.
- **Agents / IA.** 13 agents Claude Code et un agent local, chacun avec son portrait animé et une scène de son travail. Le compteur d'usage réel de mes skills publics.
- **Services.** Cinq domaines reliés aux projets du portfolio ; quatre étapes qui se déplient.
- **Français et anglais.** Chaque écran a sa propre adresse.

## Architecture

![Architecture de ingevision.cloud : des scripts Python fabriquent le site depuis sa source ; une nouveauté part dans une maquette protégée par mot de passe, puis en ligne après accord ; les visiteurs arrivent sur nginx dans le VPS et ouvrent les dépôts des projets sur GitHub ; cinq agents de nuit rejouent le site et envoient leurs questions dans un mail du matin](docs/architecture.svg)

## Exploitation

- **En ligne** depuis le 4 novembre 2026.
- **Hébergement.** Mon VPS : nginx dans Docker derrière Traefik, HTTPS, compression Brotli, politique de sécurité des contenus sans exception pour les scripts en ligne.
- **Équipe de nuit.** Accessibilité, recherche de clients, qualité, performance et sécurité, l'un après l'autre de 22 h à 4 h (Paris). Chacun corrige ce qui est factuel, le vérifie en ligne et pose le reste en questions dans le mail du matin.
- **Technologies.** HTML, CSS, JavaScript, GSAP, Python, nginx, Claude Code, Playwright.

---

**Anthony Hunt** · [ingevision.cloud](https://ingevision.cloud/) · [LinkedIn](https://www.linkedin.com/in/anthony-hunt-3948a9196) · [GitHub](https://github.com/anthohunt)

Le code du site est privé.
