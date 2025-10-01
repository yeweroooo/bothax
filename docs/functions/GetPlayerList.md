# GetPlayerList

Ringkasan
- `GetPlayerList() -> NetAvatar[]`
- Mengambil daftar pemain lain yang terlihat/terload di world.

Nilai kembali
- Array `NetAvatar`

Contoh (Lua)
```lua
for _, plr in pairs(GetPlayerList()) do
  LogToConsole(('player %s at %d,%d')
    :format(plr.name, plr.pos.x // 32, plr.pos.y // 32))
end
```

Terkait
- `NetAvatar`
- `GetPlayer(netid)`

