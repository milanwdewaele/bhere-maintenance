# b/here • Temporary Maintenance Page

Tijdelijke onderhoudspagina voor **b/here** om downtime op te vangen tijdens database- en platformmigraties.

## 🚀 Eigenschappen

- **Huisstijl**: Conform het **Vlaanderen Design System (VDS)** en de b/here huisstijl (dual accent stripe `#14B5E4` / `#e00020`, 4px radii, donkere modus `#11151c`, VDS typografie en hierarchy).
- **Meertalig (7 talen)**: Automatische taaldetectie op basis van de browser (`navigator.languages` / `navigator.language`) met een handmatige taalswitcher bar:
  - 🇳🇱 Nederlands (`nl`)
  - 🇬🇧 Engels (`en`)
  - 🇫🇷 Frans (`fr`)
  - 🇪🇸 Spaans (`es`)
  - 🇯🇵 Japans (`ja`)
  - 🇷🇺 Russisch (`ru`)
  - 🇨🇳 Chinees (`zh`)
- **Directe Nood- & Coachcontacten**: Residenten behouden toegang tot de studentencoach (Jeroen Guns) en officiële nooddiensten (112, 101, 1733, 106).
- **Vercel Ready**: `vercel.json` geconfigureerd met catch-all rewrites en strikte `Cache-Control: no-cache, no-store` headers zodat browsers na de migratie direct de live website weer tonen.
- **Auto-check**: Periodieke achtergrondcontrole en automatische herlaad-trigger zodra de verbinding herstelt.

## 📦 Deployen op Vercel

1. Ga naar [Vercel Dashboard](https://vercel.com/new).
2. Importeer de repository `milanwdewaele/bhere-maintenance`.
3. Klik op **Deploy** (geen build-commando nodig, pure statische HTML).
4. Koppel optioneel het gewenste domein of subdomein in het Vercel project settings tabje.
