# GetItemByIDSafe

Ringkasan
- `GetItemByIDSafe(itemid: int) -> ItemInfo`
- Mengambil data item berdasarkan ID dengan aman dari database item.

Parameter
- `itemid: int` — ID item.

Nilai kembali
- `ItemInfo`

Contoh (Lua)
```lua
LogToConsole(GetItemByIDSafe(242).name)
```

Terkait
- `ItemInfo`
- `GetItemInfo(id_or_name)`

