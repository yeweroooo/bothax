# RunThread

Ringkasan
- `RunThread(callback: function, ...)`
- Menjalankan fungsi secara asynchronous (thread terpisah), tidak memblokir thread utama.

Parameter
- `callback: function` — Fungsi yang dieksekusi di thread baru.
- `...: any` — Argumen tambahan (opsional).

Nilai kembali
- Tidak ada.

Contoh (Lua)
```lua
RunThread(function(id)
  LogToConsole('Running Thread For ID : ' .. id)
  Sleep(2000)
  LogToConsole('Finished Thread For ID : ' .. id)
end, 1)
```

