# Tile

Deskripsi singkat
- Informasi tile (blok) di dunia.

Bidang
- `fg: int` — Foreground ID.
- `bg: int` — Background ID.
- `collidable: boolean` — Apakah bisa ditabrak/dipijak.
- `x: int` — Koordinat tile X.
- `y: int` — Koordinat tile Y.
- `coltype: int` — Collision type.
- `locktile: int` — Info lock (jika ada).
- `flags: TileFlags` — Kumpulan flag tile.
- `extra: TileExtra | nil` — Data tambahan (bisa `nil`).

Catatan
- Beberapa contoh menggunakan `tile.pos.x`/`tile.pos.y`. Jika tidak ada field `pos`, gunakan `x` dan `y` langsung.

Contoh penggunaan (Lua)
```lua
local t = GetTile(12, 12)
if t.fg == 242 then
  LogToConsole('World Lock ditemukan!')
end
```

Terkait
- `GetTile(x, y)`
- `GetTiles()`
- `TileFlags`
- `TileExtra`

