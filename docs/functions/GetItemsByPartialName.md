# GetItemsByPartialName

Ringkasan
- `GetItemsByPartialName(partial: string) -> ItemInfo[]`
- Pencarian item berdasarkan nama sebagian (case-insensitive).

Parameter
- `partial: string` — Potongan nama item.

Nilai kembali
- Array `ItemInfo`

Contoh (Lua)
```lua
local items = GetItemsByPartialName('Dirt')
for _, it in pairs(items) do
  LogToConsole('item id => ' .. it.id)
end
```

Terkait
- `ItemInfo`

