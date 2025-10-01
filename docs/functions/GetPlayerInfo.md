# GetPlayerInfo

Ringkasan
- `GetPlayerInfo() -> PlayerItems`
- Mengambil data gem & backpack pemain.

Nilai kembali
- `PlayerItems`

Contoh (Lua)
```lua
local p = GetPlayerInfo()
LogToConsole('Gems: ' .. p.gems)
LogToConsole('Backpack Size: ' .. p.backpack.size)
```

Terkait
- `GetPlayerItems()`
- `PlayerItems`

