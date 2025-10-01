# World

Deskripsi singkat
- Informasi dunia yang sedang dimuat.

Bidang
- `name: string` — Nama world.
- `width: int` — Lebar (jumlah tile X).
- `height: int` — Tinggi (jumlah tile Y).
- `tilecount: int` — Total tile.
- `objectcount: int` — Total world object aktif.
- `lastoid: int` — OID terakhir.

Contoh penggunaan (Lua)
```lua
local w = GetWorld()
LogToConsole(('World %s (%dx%d)'):format(w.name, w.width, w.height))
```

Terkait
- `GetWorld()`

