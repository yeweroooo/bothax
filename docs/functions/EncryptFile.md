# EncryptFile

Ringkasan
- `EncryptFile(filename: string[, key: int])`
- Mengenkripsi file dari folder script. Hasil disimpan sebagai `(filename)_enc`.

Parameter
- `filename: string` — Nama file di folder script.
- `key: int (opsional)` — Kunci enkripsi.

Nilai kembali
- Tidak ada.

Contoh (Lua)
```lua
EncryptFile('script.lua')
EncryptFile('script.lua', 123)
```

Terkait
- `LoadEncryptedFile(filename)`
- `Encrypt(text[, key])`

