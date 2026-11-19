![make.fun](https://make.fun/badge/gta6-cover-art-01.svg)
![rank](https://make.fun/badge/gta6-cover-art-01/lewismarilyn177-spec/gta6-cover-art-selat2/rank.svg)
![reward](https://make.fun/badge/gta6-cover-art-01/lewismarilyn177-spec/gta6-cover-art-selat2/reward.svg)

[https://make.fun/bounty/gta6-cover-art-01](https://make.fun/bounty/gta6-cover-art-01)

Palm Coast Cover Forge is a GTA 6-style multi-panel cover art maker that transforms a photo and caption into a four-panel sunset-graded poster, exporting PNGs at 1080×1080, 1080×1350, and 1920×1080 as a fully offline static web application.

## Run it

```bash
node serve.ts
```

Then open http://localhost:8080 in your browser.

## Build the entry

```bash
MAKEFUN_OUTPUT_DIR=out node main.ts
```

This writes the built application to `out/` and generates `dossier.json`.

## Layout

- app/index.html
- app/style.css
- app/src/main.js
- app/src/cover.js
- app/src/shots.js
- app/fonts/Anton-Regular.ttf (SIL OFL)

## License

MIT