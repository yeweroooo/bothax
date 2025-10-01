# RemoveHooks

Ringkasan
- `RemoveHooks()`
- Menghapus semua hook yang terdaftar.

Nilai kembali
- Tidak ada.

Contoh (Lua)
```lua
AddHook('OnSendPacket', 1, function(_, s) LogToConsole(s) end)
AddHook('OnSendPacketRaw', '1', function(p) LogToConsole(p.type) end)
RemoveHooks()
```

Terkait
- `RemoveHook(id)`
- `AddHook(event, label, cb)`

