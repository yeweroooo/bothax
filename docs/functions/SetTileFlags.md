# SetTileFlags

Ringkasan
- `SetTileFlags(tileX: int, tileY: int, flags: int | TileFlags)`
- Mengatur flag tile pada koordinat tertentu.

Parameter
- `tileX: int` — Koordinat X tile.
- `tileY: int` — Koordinat Y tile.
- `flags: int | TileFlags` — Bitmask integer atau tabel `TileFlags`.

Nilai kembali
- Tidak ada.

Contoh (Lua)
```lua
-- Dengan bitmask
SetTileFlags(10, 5, 16384)

-- Dengan tabel flag
SetTileFlags(15, 8, {
  locked = true,
  public = true,
  water = true
})
```

Terkait
- `TileFlags`
- `GetTile(x, y)`

