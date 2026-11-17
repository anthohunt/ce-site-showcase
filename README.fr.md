[English](README.md) · **Français**

# ingevision.cloud

**Mon site, construit et entretenu par des agents IA.** Chaque changement passe par une maquette que je valide, et six agents repassent sur le site en ligne chaque nuit.

[![L'accueil, le portfolio, le dépôt d'un projet, la page des agents et les Services, sur le site en anglais (version anglaise, cliquer pour la vidéo complète)](docs/demo.webp)](https://drive.google.com/file/d/1dYCj_mHaxn5QUMNkSFLy1lda-ZtOutVx/view)

<details><summary>Version française</summary>

[![L'accueil, le portfolio, le dépôt d'un projet, la page de l'équipe de nuit et l'animation d'ouverture (cliquer pour la vidéo complète)](docs/demo.fr.webp)](https://drive.google.com/file/d/1Va1JfjYJnmLrFipZOO_hmHsMxAhPU19T/view)

</details>

*Accueil, Portfolio, le dépôt d'un projet, l'équipe de nuit, puis l'ouverture vue en arrivant d'un autre site. [Vidéo complète (1 min 27)](https://drive.google.com/file/d/1Va1JfjYJnmLrFipZOO_hmHsMxAhPU19T/view)*

## Utilisation

- **Accueil.** Un logo en forme d'œil suit la souris ; le zoom d'ouverture ne joue que pour un visiteur venu d'un autre site. Trois métiers : développement, formation, consulting.
- **Portfolio.** Quatre projets phares, puis 25 projets rangés dans six coffres. Un clic sur un projet ouvre son dépôt GitHub.
- **Agents / IA.** 14 agents Claude Code et un agent local, chacun avec son portrait animé et une scène de son travail. Le compteur d'usage réel de mes skills publics.
- **Services.** Cinq domaines reliés aux projets du portfolio ; quatre étapes qui se déplient.
- **Français et anglais.** Chaque écran a sa propre adresse.

## Architecture

![Architecture de ingevision.cloud : des scripts Python fabriquent le site depuis sa source ; une nouveauté part dans une maquette protégée par mot de passe que je relis, puis en ligne après mon oui ; les visiteurs arrivent sur nginx dans le VPS et ouvrent les dépôts des projets sur GitHub ; six agents de nuit rejouent le site, corrigent ce qui est factuel et posent leurs questions pour le matin](docs/architecture.svg)

<details><summary>Diagramme en français</summary>

![Architecture de ingevision.cloud : des scripts Python fabriquent le site depuis sa source ; une nouveauté part dans une maquette protégée par mot de passe que je relis, puis en ligne après mon oui ; les visiteurs arrivent sur nginx dans le VPS et ouvrent les dépôts des projets sur GitHub ; six agents de nuit rejouent le site, corrigent ce qui est factuel et posent leurs questions pour le matin](docs/architecture.fr.svg)

</details>

## Exploitation

- **En ligne** depuis le 4 novembre 2026.
- **Hébergement.** Mon VPS : nginx dans Docker derrière Traefik, HTTPS, compression Brotli, politique de sécurité des contenus sans exception pour les scripts en ligne.
- **Équipe de nuit.** Accessibilité, recherche de clients, qualité, performance et sécurité, lancés l'un après l'autre entre 22 h et 4 h (Paris). Chacun corrige ce qui est factuel, le vérifie en ligne et pose le reste en questions dans le mail du matin.
- **Technologies.** HTML, CSS, JavaScript, GSAP, Python, Claude Code, Playwright.

---

**Anthony Hunt** · [ingevision.cloud](https://ingevision.cloud/) · [LinkedIn](https://www.linkedin.com/in/anthony-hunt-3948a9196) · [GitHub](https://github.com/anthohunt)

Le code du site est privé.
