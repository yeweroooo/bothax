# Sleep

Ringkasan
- `Sleep(milliseconds: int)`
- Menghentikan eksekusi thread saat ini sementara (blocking) selama ms.

Parameter
- `milliseconds: int`

Nilai kembali
- Tidak ada.

Contoh (Lua)
```lua
LogToConsole('Hai')
Sleep(1000)
LogToConsole('Hai Juga')
```

