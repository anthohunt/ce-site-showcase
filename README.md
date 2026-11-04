**English** · [Français](README.fr.md)

> Showcase repository: the code and data of this project are private; this README describes it.

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

Online since 4 November 2026: Home and Portfolio are published; About and Resources are under construction.

- Menu: Home, Portfolio, About, Resources.
- Home: an eye-shaped logo that follows the mouse, an entrance that zooms into the eye, tab changes shown as a blink; three trades (development, training, consulting), each with its own card.
- "Latest projects": four flagship projects, each with its video in a tile (60 s, 30 s, 20 s and 22 s) and a sheet that opens on click (video and descriptive card, figures taken from the repositories).
- Portfolio: 35 projects sorted into six chests, opened as a grid of four.
- Resources: free tools I share, and where I publish.
- French / English switch.

## What is public

The site is online: <https://ingevision.cloud>. The code stays private.

## Tech stack

- HTML, CSS and JavaScript
- GSAP 3.12.5 for animations
- Python to assemble the pages
- Bash for publishing
