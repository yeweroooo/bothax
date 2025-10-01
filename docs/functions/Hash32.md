# Hash32

Ringkasan
- `Hash32(text: string[, seed: uint32]) -> number`
- Menghasilkan hash FNV-1a 32-bit.

Parameter
- `text: string` — Input string.
- `seed: uint32 (opsional)` — Seed tambahan.

Nilai kembali
- `number` — Nilai hash 32-bit.

Contoh (Lua)
```lua
local h = Hash32('bothax')
LogToConsole('Hash : ' .. tostring(h))
local hs = Hash32('bothax', 12345)
LogToConsole('Hash w/seed : ' .. tostring(hs))
```

