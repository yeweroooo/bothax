# GetTile

Ringkasan
- `GetTile(x: int, y: int) -> Tile`
- Mengambil info tile pada koordinat (x, y).

Parameter
- `x: int` — Tile X.
- `y: int` — Tile Y.

Nilai kembali
- `Tile`

Contoh (Lua)
```lua
local tile = GetTile(12, 12)
if tile.fg == 242 then
  LogToConsole('World Lock Found!')
end
```

Terkait
- `GetTiles()`
- `Tile`

