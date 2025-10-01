# GetPlayer

Ringkasan
- `GetPlayer(netid: int) -> NetAvatar | nil`
- Mengambil info pemain lain berdasarkan netid.

Parameter
- `netid: int` — Net ID pemain.

Nilai kembali
- `NetAvatar` jika ditemukan, `nil` jika tidak.

Contoh (Lua)
```lua
local p = GetPlayer(2)
if p then LogToConsole(p.name) end
```

Terkait
- `GetPlayerList()`
- `NetAvatar`

