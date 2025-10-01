# HttpResponse

Deskripsi singkat
- Hasil permintaan HTTP dari `MakeRequest`.

Bidang
- `status: int` — Kode status HTTP (200, 404, dst).
- `error: boolean` — Apakah terjadi error.
- `method: string` — Metode yang digunakan (GET/POST/dll.).
- `content: string` — Konten/body respon.

Contoh penggunaan (Lua)
```lua
local res = MakeRequest('https://growtopiagame.com/detail', 'GET')
if not res.error and res.status == 200 then
  LogToConsole('Panjang konten: ' .. #res.content)
end
```

Terkait
- `MakeRequest(url, method, headers, content, timeout)`

