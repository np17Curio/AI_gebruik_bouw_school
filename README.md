# AI-gebruik in de bouw

Een ochtendmasterclass voor BOL4-studenten over effectief en verantwoord
gebruik van AI (zoals ChatGPT) in hun toekomstige werk als uitvoerder of
leidinggevende in de bouw. Onderdeel van de voorbereiding op challenge 2
(practoraat Klimaat Positief Gebouwde Omgeving).

De module behandelt waarom AI niet altijd betrouwbare informatie geeft,
waarom controle van AI-antwoorden noodzakelijk is, en hoe je een effectieve
prompt opbouwt volgens een vaste structuur — gevolgd door acht praktijkgerichte
opdrachten die studenten zelfstandig in duo's uitvoeren.

Gebouwd met [`curio-team/e-module-builder`](https://github.com/curio-team/e-module-builder).

## Lokaal draaien

```bash
npm install
npm run dev
```

Open daarna [http://localhost:5173](http://localhost:5173).

## Commando's

| Commando | Omschrijving |
| --- | --- |
| `npm run dev` | Start de ontwikkelserver op `localhost:5173` |
| `npm run build` | Productie-build naar `dist/` |
| `npm run preview` | Preview van de `dist/` build lokaal |

## Content bewerken

Alleen de `content/` map hoef je te bewerken:

```text
content/
  module.md             ← module-metadata
  ai-basis/
    theory.md            ← theorie (sort: 1)
    quiz.md               ← korte zelfcheck
    exercises/            ← de 8 opdrachten
      _meta.md
      1.md … 8.md
```

Zie de documentatie van [`e-module-builder`](https://github.com/curio-team/e-module-builder)
voor het volledige content-formaat.

## Publiceren (GitHub Pages)

Push naar `main` — de GitHub Actions workflow bouwt automatisch en publiceert
naar GitHub Pages. Zorg dat in de repo-instellingen **Settings → Pages →
Source: GitHub Actions** is ingesteld.
