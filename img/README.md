# img — спрайти SERVER ROOM

Експортовано 1:1 з коду малювання в `index.html` (гра поки не змінена).

- `characters/player/`, `characters/professor/` — нові чібі-персонажі: `{down,left,right,up}_{0-3}.png`, 32×32, кадр 0 = стоїть
- `characters/*_sheet.png` — ті самі кадри одним листом 128×128 (рядки: down, left, right, up)
- `characters/player.png`, `characters/professor.png` — кадр «стоїть, обличчям вниз»
- `items/*.png` — предмети, 24×24
- `objects/` — стійка `server_rack_0…5` (64×128, скільки блоків увімкнено), `desk`, `workbench` (160×64), `computer_ok/bad` (72×36)
- `tiles/` — `wall`, `floor_0…2` (32×32)
- `sprites.json` — розміри й точки прив'язки (персонажі малюються в `x-4, y-8`)

Малювати з `image-rendering: pixelated` і `ctx.imageSmoothingEnabled = false`.
