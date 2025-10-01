# GetObjectList

Ringkasan
- `GetObjectList() -> WorldObject[]`
- Mengambil daftar objek dunia (drop, dll.) yang aktif.

Nilai kembali
- Array `WorldObject`

Contoh (Lua)
```lua
for _, obj in pairs(GetObjectList()) do
  if obj.id == 242 then
    LogToConsole(('Wolok di (%d,%d), jumlah %d')
      :format(obj.pos.x // 32, obj.pos.y // 32, obj.amount))
  end
end
```

Terkait
- `WorldObject`

