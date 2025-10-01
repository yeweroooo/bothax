# ClientNPC

Deskripsi singkat
- Representasi NPC (Non-Player Character) yang terlihat di sisi klien.
- Berguna untuk membaca posisi, tipe, dan target pergerakan NPC.

Bidang
- `id: int` — ID unik NPC di dunia saat ini.
- `type: int` — Tipe/jenis NPC.
- `pos: Vec2` — Posisi NPC dalam koordinat pixel.
- `target: Vec2` — Posisi tujuan NPC (pixel).

Contoh penggunaan (Lua)
```lua
local npc = GetNPC(1)
if npc then
  LogToConsole(('NPC %d tipe %d di (%d,%d)')
    :format(npc.id, npc.type, npc.pos.x // 32, npc.pos.y // 32))
else
  LogToConsole('NPC tidak ditemukan')
end
```

Terkait
- `GetNPC(id)`
- `GetNPCList()`
- `Vec2`

