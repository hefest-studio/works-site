**English** | [Русский](README.ru.md)

<p align="center"><img src="docs/cover.png" alt="works-site" width="100%"></p>

[![Website](https://img.shields.io/website?url=https://works.hefest.ru&label=site&up_message=online&down_message=offline)](https://works.hefest.ru)
![Deploy](https://img.shields.io/badge/deploy-Vercel-000000?logo=vercel)
![Stack](https://img.shields.io/badge/HTML%20%C2%B7%20CSS%20%C2%B7%20JS-no%20build-E34F26?logo=html5&logoColor=white)
[![Hefest](https://img.shields.io/badge/made%20by-Hefest%20AI%20studio-EA6A12)](https://hefest.ru)

# works-site — the Hefest studio portfolio

A public one-page portfolio: `works.hefest.ru` and `works.hefest.online` (both domains serve the same
Russian page for now; an English version is on the [roadmap](ROADMAP.md)). Static files, deployed to
Vercel (automatic HTTPS). A work of the Hefest studio.

## Contents
- `index.html` — the showcase: cards of the studio's works (Polyinstrumental Workshop, Retro Games, Tab Forge) and an "Examples" section.
- `examples/` — curated public example deliverables (from the reports project; personal items excluded).

## Deploy
Vercel → project `works-site` → domains `works.hefest.ru` + `works.hefest.online`.
The work cards link to the subdomains `workshop.hefest.ru` (music-book) and `arcade.hefest.ru` (retro-games); Tab Forge links to its repository / store.

## Privacy
A static showcase that collects no personal data. If a request form is ever added, personal data of Russian
citizens must go to an endpoint in Russia (not to Vercel).
