# Vec2

Deskripsi singkat
- Vektor 2D sederhana.

Bidang
- `x: float` — Sumbu X.
- `y: float` — Sumbu Y.

Contoh penggunaan (Lua)
```lua
local me = GetLocal()
local pos = me.pos -- Vec2
LogToConsole(('(%d,%d)'):format(pos.x // 32, pos.y // 32))
```

Terkait
- `NetAvatar`, `WorldCamera`, `WorldObject`

