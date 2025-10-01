# GetNPCList

Ringkasan
- `GetNPCList() -> ClientNPC[]`
- Mengambil daftar semua NPC aktif di world.

Nilai kembali
- Array `ClientNPC`

Contoh (Lua)
```lua
for _, npc in pairs(GetNPCList()) do
  LogToConsole('Found NPC id: ' .. npc.id)
end
```

Terkait
- `ClientNPC`
- `GetNPC(id)`

