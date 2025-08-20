<style> 
body{ 
    background-color: #24292e; 
    color: #fff;
} 
.highlight{
    background-color: #44494e; 
}
</style> 


[back](./index.md)
# Apa itu Batocera linux

Batocera Linux adalah sebuah sistem operasi berbasis Linux yang khusus dibuat untuk emulasi game retro dan media center.

Kelebihan Utama Batocera

1. Plug & Play → nggak perlu ribet install emulator satu-satu, semuanya sudah siap di dalamnya.
1. Mendukung banyak konsol → mulai dari Atari, NES, SNES, Sega, PS1, PSP, Nintendo 64, Dreamcast, GameCube, Wii, PS2, bahkan sebagian PS3, Wii U, dan Switch.
3. Gratis & Open Source.
4. User Friendly → antarmuka (UI) dibuat mirip menu konsol, gampang dipakai.
5. Portabel → bisa dijalankan dari USB atau HDD eksternal tanpa mengganggu OS utama di PC.
6. Media Center → bisa juga dipakai nonton film & musik (karena sudah ada Kodi bawaan).

# Install Batocera

Batocera bisa di download di [homepage batocera](https://batocera.org/). Panduan lengkap tentang batocera bisa dibaca [di sini](https://wiki.batocera.org/)
# Perintah Tambahan Batocera

install switch emulator (v41+)
```
# versi batocera 41+
$ curl -L bit.ly/foclabroc-switchoff | bash
```
```
# versi batocera 39 / 40
$ curl -L bit.ly/fovlabroc-switchoff-40 | bash
```
install wine tricks (dll file)
```
$ batocera-wine windows trick [path/to/folder.wine] [tricks to install]
```
```
# menampilkan daftar tricks
$ batocera-wine tricks-list
``` 
install RGSX (untuk download game)
```
$ curl -L bit.ly/rgsx-install | sh
```
# Batocera Dual Boot
untuk menginstall batocera dengan boot lain bisa lihat panduannya [di sini](https://wiki.batocera.org/dual_boot_ubuntu_batocera.linux)


[back](./index.md)
