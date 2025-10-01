# GetTiles

Ringkasan
- `GetTiles() -> Tile[]`
- Mengambil semua tile di world saat ini.

Nilai kembali
- Array `Tile`

Contoh (Lua)
```lua
for _, tile in pairs(GetTiles()) do
  if tile.fg == 242 then
    LogToConsole('Found WL at '.. tile.x .. ', ' .. tile.y)
  end
end
```

Terkait
- `GetTile(x, y)`
- `Tile`

