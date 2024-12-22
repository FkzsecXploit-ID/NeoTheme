![](https://img.shields.io/badge/Code-php-informational?style=flat&logo=php&logoColor=white&color=blue) ![](https://img.shields.io/badge/Terminal-Termux-informational?style=flat&logo=android&logoColor=white&color=brightgreen)

## What is ***NeoTheme*** specifically for Termux?
**NeoTheme** adalah sebuah program software di rancang untuk membuat penampilan termux menjadi keren atau menarik. Di dalam nya ada beberapa fitur yang tersedia dan dapat digunakan dengan mudah kapan saja anda mencobanya!

![Logo](https://raw.githubusercontent.com/FkzsecXploit-ID/FkzsecXploit-ID.github.io/refs/heads/main/images/fkzsec.dev.jpg)

## Dependencies
- datetime
- figlet
- toilet
  
## Instalation
### Disclaimer : Script ini digunakan pada Termux saja.

1. Update Untuk memperbarui paket dan sistem

``` bash
pkg update && pkg upgrade
```

2. Install git pada Terminal
``` bash
pkg install git
```

3. install PHP pada Terminal
``` bash
pkg install php
```

4. Jalankan Git Clone
``` bash
git clone https://github.com/FkzsecXploit-ID/NeoTheme.git
```

5. Masuk ke path NeoTheme
``` bash
cd NeoTheme
```

6. Beri izin akses penuh pada main.php
``` bash
chmod +x main.php
```

7. Jalankan program main.php
``` bash
php main.php
```

## Usage

### Setelah menjalankan Program dan Enter name, sekarang ketik **Help**
``` php
┏━━(NeoTheme㉿fkzsec)━[/storage/emulated/0/NeoTheme]
┗━# help

[+] Bantuan telah tersedia, silahkan anda membaca panduan di bawah ini :
[+] Pastikan jika anda ingin menggunakan Theme Dari kami, terminal anda kosong belum ada theme lain atau ascii lain
[+] Disclaimer : Theme ini dibuat sedemikian khusus menggunakan ascii jika terasa lag pada terminal anda silahkan hapus themenya

[•] Command / Perintah Utama :
 ╰─► Help      | Menampilkan bantuan
 ╰─► About     | Tentang kami
 ╰─► Contact   | Hubungi Kami
 ╰─► Update    | Update Tools ini
 ╰─► Uninstall | Uninstall Theme Mask, Font, PS1, Color, Reset All
 ╰─► Exit      | Menghentikan Prorgam ini

[•] Command Untuk menyetel Termux Style Configuration :
 ╰─► Color   | Custom Terminal color style
 ╰─► Font    | Custom terminal font style
 ╰─► PS1     | Primary Prompt String (Variabel Shell)
 ╰─► Theme   | Customize Theme/Banner In Terminal

[•] Berikut beberapa theme yang tersedia saat ini :
 ╰─► Anonymous
 ╰─► Bunny Girl
 ╰─► Galaxy1
 ╰─► Banner_Boxes1
 ╰─► Demon
 ╰─► Anonymous2
 ╰─► A.Unicorn
 ╰─► More..., type 'theme' untuk melihat secara detail
```

### Menu Theme
``` php
┏━━(NeoTheme㉿fkzsec)━[/storage/emulated/0/NeoTheme]
┗━# theme

[+] Mempersiapkan Bahan-bahan..
[+] Pilih mask style yang ingin diterapkan:

[01] Anonymous
[02] Bunny_Girl
[03] Galaxy1
[04] Banner_Boxes1
[05] Demon
[06] Anonymous2
[07] A.Unicorn
[08] Kali-normal
[09] Ubuntu-normal
[10] Debian-normal
[11] Black Arch-normal
[12] Debian-normal
[13] Ubuntu
[14] Cyber Wolf


[?] Pilih Tema anda yang ingin diterapkan (eg.1-14) :
```

### Color Menu
``` php
┏━━(NeoTheme㉿fkzsec)━[/storage/emulated/0/NeoTheme]
┗━# color

[+] Mempersiapkan Bahan-bahan..
[+] Pilih color style yang ingin diterapkan :

[1] 3024-dark
[2] 3024-day
[3] 3024-light
[4] 3024-night
[5] _base
[6] aci
[7] aco
[8] adventuretime
[9] afterglow
[10] alien-blood
[11] apathy-dark
[12] apathy-light
[13] argonaut
[14] arthur
[15] ashes-dark
[16] ashes-light
[17] atelierdune-dark
[18] atelierdune-light
[19] atelierforest-dark
[20] atelierforest-light
[21] atelierheath-dark
[22] atelierheath-light
[23] atelierlakeside-dark
[24] atelierlakeside-light
[25] atelierseaside-dark
[26] atelierseaside-light
[27] atom
[28] azu
[28-365] More....
```

### Font Menu
``` php
┏━━(NeoTheme㉿fkzsec)━[/storage/emulated/0/NeoTheme]
┗━# font

[+] Mempersiapkan Bahan-bahan..
[+] Pilih font style yang ingin diterapkan :

[1] Anonymous-Pro.ttf
[2] AnonymousPro.ttf
[3] Bedstead-Condensed.ttf
[4] CascadiaCode.ttf
[5] Consolas.ttf
[6] Courier-Prime.ttf
[7] CourierNew.ttf
[8] D2-Coding.ttf
[9] DejaVu-Sans-Mono.ttf
[10] DejaVu.ttf
[11] DejaVuSansMono.ttf
[12] DroidSansMono.ttf
[13] Fantasque-Sans-Mono.ttf
[14] Fantasque.ttf
[15] Fira-Code.ttf
[16] Fira-Mono.ttf
[17] FiraCode.ttf
[18] FiraFlott.ttf
[19] GNU-FreeFont.ttf
[20] Go-Mono.ttf
[21] Go.ttf
[22] Hack.ttf
[23] Hermit.ttf
[24] Inconsolata.ttf
[25] InputMono.ttf
[26] Iosevka.ttf
[27] JetBrains-Mono.ttf
[28] Liberation-Mono.ttf
[29] LiberationMono.ttf
[30] Menlo.ttf
[31] Meslo.ttf
[32] Monaco.ttf
[33] Monofur.ttf
[34] Monoid.ttf
[35] OpenDyslexic.ttf
[36] OxygenMono.ttf
[37] ProFont.ttf
[38] ProggyClean.ttf
[39] Roboto-Mono.ttf
[40] Roboto.ttf
[41] Source-Code-Pro.ttf
[42] Terminus.ttf
[43] Ubuntu-Mono.ttf
[44] Ubuntu.ttf
[45] Victor-Mono.ttf

[?] Silahkan pilih angka di atas untuk menerapkan font (eg.1-45) :
```

## Top Languages
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=FkzsecXploit-ID&hide=html,javascript,css,c,c++,python,assembly)](https://github.com/FkzsecXploit-ID/readme-components)

## Links
[![YouTube Badge](https://img.shields.io/static/v1?label=|&message=YouTube&color=red&style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@fkzz_id?si=2iKh-_gak2JPjffW) [![Telegram Badge](https://img.shields.io/static/v1?label=|&message=Telegram&color=lightblue&style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/fkzsec) [![Telegram Badge](https://img.shields.io/static/v1?label=|&message=Telegram2&color=lightblue&style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/ton619cyber) [![TikTok Badge](https://img.shields.io/static/v1?label=|&message=TikTok&color=Gray&style=for-the-badge&logo=tiktok&logoColor=white)](https://tiktok.com/@fkzsec.id)
