# NetAvatar

Deskripsi singkat
- Representasi avatar pemain (lokal atau pemain lain) di dunia.

Bidang
- `pos: Vec2` — Posisi (pixel).
- `name: string` — Nama tampilan.
- `isleft: boolean` — Menghadap kiri atau tidak.
- `netid: int` — Net ID unik sesi di dunia.
- `userid: int` — User ID akun.
- `country: string` — Kode negara.
- `invisible: boolean` — Tersembunyi atau tidak.
- `mstate: boolean` — State gerak (makna spesifik bergantung build).
- `smstate: boolean` — State gerak sekunder.

Contoh penggunaan (Lua)
```lua
local me = GetLocal()
LogToConsole(('Halo %s di (%d,%d)')
  :format(me.name, me.pos.x // 32, me.pos.y // 32))
```

Terkait
- `GetLocal()`
- `GetPlayer(netid)`
- `GetPlayerList()`

