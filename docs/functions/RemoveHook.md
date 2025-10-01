# RemoveHook

Ringkasan
- `RemoveHook(hook_id: int|string)`
- Menghapus hook berdasarkan ID/label yang dipakai di `AddHook`.

Parameter
- `hook_id: int|string` — Sama dengan label yang diberikan saat `AddHook`.

Nilai kembali
- Tidak ada.

Contoh (Lua)
```lua
AddHook('OnSendPacket', 123, function(_, str) LogToConsole(str) end)
RemoveHook(123)
AddHook('OnSendPacket', 'hai', function(_, str) LogToConsole(str) end)
RemoveHook('hai')
```

Terkait
- `AddHook(event, label, cb)`
- `RemoveHooks()`

