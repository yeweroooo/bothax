# SendPacket

Ringkasan
- `SendPacket(type: int, packet: string)`
- Mengirim paket teks ke server.

Parameter
- `type: int` — Tipe paket (mis. 2/3 umum dipakai).
- `packet: string` — Isi paket teks.

Nilai kembali
- Tidak ada.

Contoh (Lua)
```lua
SendPacket(2, 'action|respawn')
```

