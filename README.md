# Vital Fisher · Depth studio

Prohlížečový editor, který mapuje cyklický gradient na jas a hloubku fotky, nechá ho projít fotkou vlnou s organickou maskou a přes barevnou část propíše žebrované matné sklo a zrno.

## Spuštění
Otevři `index.html` v prohlížeči, nebo zapni GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

## Vstupy
- **Fotka** (JPG/PNG), zpracuje se až 1600 px na delší straně.
- **Depth mapa** (volitelná): černá = blízko, bílá = daleko. Lze vytvořit ve Weavy (depth node) nebo v [Depth Anything V2](https://huggingface.co/spaces/depth-anything/Depth-Anything-V2).

## Ovládání
- Klik nebo tah v obraze nastaví střed vlny, mezerník pozastaví animaci.
- Předvolby gradientu: Termo, Magnesium, Vitamin C, Řeka.

## Export
„Stáhnout snímek“ uloží aktuální snímek jako PNG, „Stáhnout video“ nahraje jeden cyklus animace (MP4 v Safari, WebM v Chromu) a stáhne ho. V claude.ai se před uložením zobrazí potvrzení, na GitHub Pages se soubor stáhne rovnou.
