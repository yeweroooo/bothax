# SendVariantList

Ringkasan
- `SendVariantList(var: VariantList[, netid: int][, delay: int])`
- Mengirim VariantList.

Parameter
- `var: VariantList` — Isi varian (tabel numerik berindeks 0..n).
- `netid: int (opsional)` — NetID target.
- `delay: int (opsional)` — Delay pengiriman (ms).

Nilai kembali
- Tidak ada.

Contoh (Lua)
```lua
SendVariantList({
  [0] = 'OnTextOverlay',
  [1] = 'BothaxYT!'
}, -1, 1000)
```

