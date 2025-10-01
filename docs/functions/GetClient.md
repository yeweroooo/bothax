# GetClient

Ringkasan
- `GetClient() -> ENetClient`
- Mendapatkan info koneksi ENet saat ini.

Nilai kembali
- `ENetClient` — address, port, ping.

Contoh (Lua)
```lua
local client = GetClient()
LogToConsole("Connected to: " .. client.address .. ":" .. client.port)
LogToConsole("Ping: " .. client.ping .. "ms")
```

Terkait
- `ENetClient`

