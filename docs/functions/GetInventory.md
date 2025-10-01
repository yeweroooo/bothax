# GetInventory

Ringkasan
- `GetInventory() -> Inventory[]`
- Mengambil daftar item di inventaris pemain.

Nilai kembali
- Array `Inventory` — setiap entri berisi `id`, `amount`, `flags`.

Contoh (Lua)
```lua
for _, item in pairs(GetInventory()) do
  LogToConsole('item id '.. item.id ..', amount '.. item.amount ..', flags '.. item.flags)
end
```

Terkait
- `Inventory`

