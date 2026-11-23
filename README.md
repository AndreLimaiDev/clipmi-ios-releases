# ClipMI iOS

Rilis ClipMI untuk iPhone (file `.ipa` tanpa tanda tangan) dan **source SideStore** untuk memasang dan memperbarui
ClipMI langsung dari iPhone.

## Tambahkan source di SideStore

1. Buka SideStore › tab **Sources** › tombol **+**.
2. Tempel alamat ini:

   ```
   https://raw.githubusercontent.com/AndreLimaiDev/clipmi-ios-releases/main/source.json
   ```

3. Buka source **ClipMI** › **ClipMI** › **Install** (atau **Update** bila ada versi baru).

SideStore menandatangani ClipMI dengan Apple ID Anda sendiri. Masa berlakunya 7 hari: buka SideStore › **Refresh All**
seminggu sekali, atau buat otomasi harian di app Pintasan (aksi SideStore › Refresh All).

## Sebelum memasang ulang

Cadangkan data dulu: ClipMI › Pengaturan › Data › **Cadangkan & pulihkan**, simpan ZIP-nya di Files. Bila ClipMI
terpasang sebagai aplikasi baru yang kosong, pulihkan dari ZIP itu.
