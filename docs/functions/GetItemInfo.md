# GetItemInfo

Ringkasan
- `GetItemInfo(item: int|string) -> ItemInfo`
- Mengambil data item berdasarkan ID atau nama.

Parameter
- `item: int|string` — ID atau nama item.

Nilai kembali
- `ItemInfo`

Contoh (Lua)
```lua
LogToConsole(GetItemInfo(242).name)
LogToConsole(GetItemInfo('World Lock').id)
```

Terkait
- `ItemInfo`
- `GetItemByIDSafe(id)`
- `GetItemByName(name)`

