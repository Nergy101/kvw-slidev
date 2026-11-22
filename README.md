# 🚀 KVW De Meern — Presentatie "Ruimte"

Slidev-presentatie voor de KinderVakantieWeek De Meern, thema **Ruimte**, geschikt voor kinderen van 4 t/m 12 jaar.

## Starten

```bash
cd /root/code-repos/kvw-ruimte
npm install
npm run dev
```

Open daarna http://localhost:3030 in je browser.

## Handige knoppen tijdens de presentatie

| Knop | Actie |
|------|-------|
| `→` / spatie | Volgende slide / volgende stap (v-click) |
| `←` | Vorige slide |
| `o` | Overzicht van alle slides |
| `d` | Donkere modus aan/uit |
| `f` | Volledig scherm |
| `p` | Presentermodus (met sprekersnotities) |

## Exporteren naar PDF

```bash
npm run export
```

## Fancy visuals

- **Geanimeerde achtergrond**: twee driftende sterrenlagen die twinkelen + een vallende ster (pure CSS in `slides.md`).
- **Per-slide overgangen**: `fade`, `slide-left`, `slide-up` en `zoom` — ingesteld per slide in de frontmatter.
- **Nevels**: elke slide heeft een `<div class="nebula">` met eigen kleuren via `--c1/--c2/--c3`.
- **Zelfgemaakte SVG-assets** in `public/assets/` (zon, aarde, maan, Saturnus, raket, astronaut, alien, UFO, satelliet, galaxy, ster, trofee) — met zweef-/draai-/zwaai-animaties.

## Aanpassen

- Alle slides staan in `slides.md` — elke slide start na `---`.
- `<div v-click>` laat tekst stap voor stap verschijnen (handig voor de quiz en de aftelling).
- Sprekersnotities staan in `<!-- ... -->` onder een slide (zichtbaar in presentermodus met `p`).
