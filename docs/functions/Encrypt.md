# Encrypt

Ringkasan
- `Encrypt(text: string[, key: int]) -> string`
- Mengenkripsi teks menjadi string terenkripsi.

Parameter
- `text: string` — Teks yang akan dienkripsi.
- `key: int (opsional)` — Kunci enkripsi.

Nilai kembali
- `string` — Hasil teks terenkripsi.

Contoh (Lua)
```lua
local secret = Encrypt('assalamualaikum')
LogToConsole(secret)

local withKey = Encrypt('assalamualaikum', 123)
LogToConsole(withKey)
```

Terkait
- `LoadEncrypt(encText)`
- `EncryptFile(filename[, key])`

