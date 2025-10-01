# ItemInfo

Deskripsi singkat
- Data lengkap item dari database item game.

Bidang
- `id: int` — ID item.
- `name: string` — Nama item.
- `filename: string` — Nama file/asset.
- `rarity: int` — Tingkat kelangkaan.
- `breakhit: int` — Hit break.
- `growtime: int` — Waktu tumbuh (jika seed/tree).
- `type: int` — Tipe item.
- `coltype: int` — Collision type.
- `clothingtype: int` — Tipe pakaian (jika apparel).
- `visualstyle: int` — Gaya visual.
- `texturex: int` — Koordinat tekstur X.
- `texturey: int` — Koordinat tekstur Y.
- `flags: int` — Flag item.

Contoh penggunaan (Lua)
```lua
local info = GetItemInfo('World Lock')
LogToConsole(('ID %d, rarity %d'):format(info.id, info.rarity))
```

Terkait
- `GetItemInfo(id_or_name)`
- `GetItemByIDSafe(id)`
- `GetItemByName(name)`
- `GetItemInfoList()`

