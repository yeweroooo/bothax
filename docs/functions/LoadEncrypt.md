# LoadEncrypt

Ringkasan
- `LoadEncrypt(encryptedText: string)`
- Menjalankan teks terenkripsi sebagai script Lua.

Parameter
- `encryptedText: string` — String terenkripsi.

Nilai kembali
- Tidak ada (eksekusi terjadi di dalam fungsi).

Contoh (Lua)
```lua
local script = Encrypt("LogToConsole('hello world!')")
LoadEncrypt(script)
```

Terkait
- `Encrypt(text[, key])`
- `LoadEncryptedFile(filename)`

