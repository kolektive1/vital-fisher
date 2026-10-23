# Vital Fisher · Depth studio

Prohlížečový editor, který mapuje cyklický gradient na jas a hloubku fotky, nechá ho projít fotkou vlnou s organickou maskou a přes barevnou část propíše žebrované matné sklo a zrno.

## Spuštění
Otevři `index.html` v prohlížeči, nebo zapni GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

## Vstupy
- **Fotka** (JPG/PNG). Náhled běží v 1600 px na delší straně, export snímku může být ve 4K nebo v plném rozlišení fotky.
- **Depth mapa** (volitelná): černá = blízko, bílá = daleko. Lze vytvořit ve Weavy (depth node) nebo v [Depth Anything V2](https://huggingface.co/spaces/depth-anything/Depth-Anything-V2).

## Ovládání
- Klik nebo tah v obraze nastaví střed vlny, mezerník pozastaví animaci.
- Předvolby gradientu: Termo, Magnesium, Vitamin C, Řeka.

## Export
„Stáhnout snímek“ uloží aktuální snímek jako PNG v kvalitě zvolené vedle tlačítka: **1600** (jako náhled), **4K** (3840 px na delší straně) nebo **Originál** (rozlišení nahrané fotky, max. 8192 px). Snímek se vykreslí znovu ve vyšším rozlišení, zrno a zrnitost skla se přepočítají tak, aby vypadaly stejně jako v náhledu. Pod náhledem je vidět výsledná velikost v px i v cm při 300 DPI. Velké exporty (nad 4K) dělej v Chromu na počítači.

„Stáhnout video“ nahraje (stále v rozlišení náhledu) jeden cyklus animace (MP4 v Safari, WebM v Chromu) a stáhne ho. V claude.ai se před uložením zobrazí potvrzení, na GitHub Pages se soubor stáhne rovnou.
