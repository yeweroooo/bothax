# PlayerItems

Deskripsi singkat
- Data item terkait pemain: jumlah gems dan konfigurasi backpack.

Bidang
- `gems: int` — Saldo gems pemain.
- `backpack: table` — Info ransel:
  - `priority: int[]` — Urutan prioritas slot.
  - `size: int` — Ukuran ransel maksimal.
  - `selected: int` — Slot/item terpilih.

Contoh penggunaan (Lua)
```lua
local p = GetPlayerInfo()
LogToConsole(('Gems: %d, Backpack size: %d')
  :format(p.gems, p.backpack.size))
```

Terkait
- `GetPlayerInfo()` / `GetPlayerItems()`

