### Bothax Lua Documentation
Dokumentasi API Lua untuk executor/mod Growtopia (Bothax). Berisi daftar fungsi, struktur data, dan contoh pemakaian dalam bahasa Indonesia agar mudah dipahami.

Tujuan
- Menjelaskan kegunaan setiap fungsi/struktur dengan contoh nyata.
- Mempermudah penempatan file script di Android/Windows.
- Memberikan titik awal cepat (Quick Start) untuk membuat script.

Quick Start (contoh singkat)
```lua
AddHook('OnVariant', 'block_dialog', function(var)
  if var[0] == 'OnDialogRequest' then
    LogToConsole('Dialog diblokir oleh script')
    return true
  end
end)
```

## Informasi Server
* `Bothax Server :`
[![BothaxYT Community](https://invite.casperiv.dev?inviteCode=jFWte2Gu9z)](https://discord.gg/jFWte2Gu9z)

* `Satan Server :`
[![Satan Community](https://invite.casperiv.dev?inviteCode=dbqgG2FySZ)](https://discord.gg/dbqgG2FySZ)

* `Rvnaa A.K.A Yasugami Server :`
[![Rvnaa Community](https://invite.casperiv.dev?inviteCode=5CAYpDCmSg)](https://discord.gg/5CAYpDCmSg)

Lihat juga: docs/SERVER_INFO.md

Penempatan Script
* `Script Path for Android :`
```
Android/media/com.rtsoft.growtopia/scripts/file.lua
```

* `Script Path for Windows :`
Win + R dan ketik
```
%appdata%\Growtopia\scripts
```

`kalo ada yang salah atau kurang mohon dimaafkan, tag aku aja di discord emuach :)`

## Hak Cipta & Lisensi
- Hak cipta konten dari repo/proyek asli tetap milik pemiliknya masing-masing.
- Rujuk file COPYRIGHT.md untuk catatan hak cipta dan atribusi.
- Jika repo asli memiliki lisensi, ikuti ketentuan lisensi tersebut untuk bagian yang digunakan di sini.

## Kontributor
- Kontributor lama/terkait: `@bawt`, `@rvna__` (lihat juga file CONTRIBUTORS.md).

## Index Fungsi
- [BothaxHook](docs/functions/BothaxHook.md)
- [AddHook](docs/functions/AddHook.md)
- [ChangeValue](docs/functions/ChangeValue.md)
- [CheckPath](docs/functions/CheckPath.md)
- [Encrypt](docs/functions/Encrypt.md)
- [EncryptFile](docs/functions/EncryptFile.md)
- [LoadEncrypt](docs/functions/LoadEncrypt.md)
- [LoadEncryptedFile](docs/functions/LoadEncryptedFile.md)
- [FindPath](docs/functions/FindPath.md)
- [GetCamera](docs/functions/GetCamera.md)
- [GetClient](docs/functions/GetClient.md)
- [GetInventory](docs/functions/GetInventory.md)
- [GetItemByIDSafe](docs/functions/GetItemByIDSafe.md)
- [GetItemByName](docs/functions/GetItemByName.md)
- [GetItemInfo](docs/functions/GetItemInfo.md)
- [GetItemInfoList](docs/functions/GetItemInfoList.md)
- [GetItemsByPartialName](docs/functions/GetItemsByPartialName.md)
- [GetLocal](docs/functions/GetLocal.md)
- [GetNPC](docs/functions/GetNPC.md)
- [GetNPCList](docs/functions/GetNPCList.md)
- [GetObjectList](docs/functions/GetObjectList.md)
- [GetPlayer](docs/functions/GetPlayer.md)
- [GetPlayerInfo](docs/functions/GetPlayerInfo.md)
- [GetPlayerItems](docs/functions/GetPlayerItems.md)
- [GetPlayerList](docs/functions/GetPlayerList.md)
- [GetTile](docs/functions/GetTile.md)
- [GetTiles](docs/functions/GetTiles.md)
- [GetWorld](docs/functions/GetWorld.md)
- [Hash32](docs/functions/Hash32.md)
- [Hash64](docs/functions/Hash64.md)
- [MakeRequest](docs/functions/MakeRequest.md)
- [RemoveHook](docs/functions/RemoveHook.md)
- [RemoveHooks](docs/functions/RemoveHooks.md)
- [RequestJoinWorld](docs/functions/RequestJoinWorld.md)
- [RunDelayed](docs/functions/RunDelayed.md)
- [RunThread](docs/functions/RunThread.md)
- [SendPacket](docs/functions/SendPacket.md)
- [SendPacketRaw](docs/functions/SendPacketRaw.md)
- [SendVariantList](docs/functions/SendVariantList.md)
- [SetItemSelected](docs/functions/SetItemSelected.md)
- [SetTileFlags](docs/functions/SetTileFlags.md)
- [Sleep](docs/functions/Sleep.md)

## Index Struktur
- [ClientNPC](docs/structures/ClientNPC.md)
- [DungeonNPC](docs/structures/DungeonNPC.md)
- [ENetClient](docs/structures/ENetClient.md)
- [GameUpdatePacket](docs/structures/GameUpdatePacket.md)
- [ItemInfo](docs/structures/ItemInfo.md)
- [Inventory](docs/structures/Inventory.md)
- [NetAvatar](docs/structures/NetAvatar.md)
- [PlayerItems](docs/structures/PlayerItems.md)
- [Tile](docs/structures/Tile.md)
- [TileExtra](docs/structures/TileExtra.md)
- [TileFlags](docs/structures/TileFlags.md)
- [World](docs/structures/World.md)
- [WorldObject](docs/structures/WorldObject.md)
- [WorldCamera](docs/structures/WorldCamera.md)
- [Vec2](docs/structures/Vec2.md)
- [HttpResponse](docs/structures/HttpResponse.md)

## Contoh (Examples)
- [Quick Start](examples/01_quick_start.lua)
- [Semua Hook](examples/02_hooks.lua)
- [Scan World (WL tile & drop)](examples/03_world_scan.lua)
- [HTTP & Hash](examples/04_http_and_hash.lua)
- [Encrypt & Jalankan](examples/05_encrypt.lua)

