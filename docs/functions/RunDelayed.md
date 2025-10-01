# RunDelayed

Ringkasan
- `RunDelayed(milliseconds: int, callback: function, ...)`
- Menjalankan fungsi setelah jeda tertentu (ms). Argumen tambahan diteruskan ke callback.

Parameter
- `milliseconds: int` — Lama tunda.
- `callback: function` — Fungsi yang dipanggil.
- `...: any` — Argumen tambahan (opsional).

Nilai kembali
- Tidak ada.

Contoh (Lua)
```lua
RunDelayed(1000, function(name)
  LogToConsole('This Is ' .. name .. '!')
end, 'Bothax')
```

