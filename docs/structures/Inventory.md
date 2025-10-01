# Inventory

Deskripsi singkat
- Entri item di inventaris pemain.

Bidang
- `id: int` — ID item.
- `amount: int` — Jumlah/quantity.
- `flags: int` — Flag item pada slot.

Contoh penggunaan (Lua)
```lua
for _, it in pairs(GetInventory()) do
  LogToConsole(('Item %d jumlah %d'):format(it.id, it.amount))
end
```

Terkait
- `GetInventory()`

