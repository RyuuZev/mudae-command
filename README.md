# 🎮 Mudae Bot — Panduan Command Lengkap

> **Mudae** adalah bot Discord untuk mengoleksi karakter anime, manga, dan game melalui sistem gacha. Kamu bisa roll, klaim, menikahi karakter favorit, dan bersaing dengan server lainnya.

---

## 📋 Daftar Isi

1. [Roll (Gacha)](#-roll-gacha)
2. [Klaim Karakter](#-klaim-karakter)
3. [Harem & Koleksi](#-harem--koleksi)
4. [Kakera & Gem](#-kakera--gem)
5. [Wish List](#-wish-list)
6. [Daily & Timer](#-daily--timer)
7. [Pernikahan & Divorsi](#-pernikahan--divorsi)
8. [Trade & Give](#-trade--give)
9. [Info Karakter](#-info-karakter)
10. [Soulmate](#-soulmate)
11. [Minigame](#-minigame)
12. [Pengaturan Server (Admin)](#-pengaturan-server-admin)

---

## 🎲 Roll (Gacha)

Command utama untuk mendapatkan karakter secara acak.

| Command | Alias | Deskripsi |
|---|---|---|
| `$w` | `$waifu` | Roll karakter **waifu** (perempuan) dari anime/manga/game |
| `$h` | `$husbando` | Roll karakter **husbando** (laki-laki) dari anime/manga/game |
| `$wa` | — | Roll waifu dari **anime saja** |
| `$ha` | — | Roll husbando dari **anime saja** |
| `$wg` | — | Roll waifu dari **game saja** |
| `$hg` | — | Roll husbando dari **game saja** |
| `$mx` | `$mxroll` | Roll karakter **campur** (waifu + husbando) |
| `$mwa` | — | Roll karakter campur dari **anime** |
| `$mwg` | — | Roll karakter campur dari **game** |
| `$roll` | — | Sama seperti `$mx` |

> 💡 **Catatan:** Setiap roll menggunakan 1 "roll charge". Jumlah roll yang tersedia bisa dilihat dengan `$tu`.

---

## 💍 Klaim Karakter

Setelah karakter muncul dari roll, kamu bisa mengklaimnya.

| Command | Alias | Deskripsi |
|---|---|---|
| `$marry [nama]` | `$m` | Klaim/menikahi karakter yang baru saja di-roll |
| `$snipe [nama]` | — | Klaim karakter dari roll orang lain sebelum mereka (jika klaim orang lain gagal) |

> 💡 **Cara klaim:** Setelah karakter muncul, ketik nama karakter atau reaksi 💖 (jika fitur react diaktifkan admin). Waktu klaim terbatas!

---

## 👰 Harem & Koleksi

Kelola koleksi karakter yang sudah kamu miliki.

| Command | Alias | Deskripsi |
|---|---|---|
| `$harem` | `$haremlist`, `$hl` | Lihat semua karakter yang kamu miliki |
| `$harem [user]` | — | Lihat harem milik user lain |
| `$haremcopy [user]` | `$hc` | Salin tampilan harem milik user lain |
| `$haremimage` | `$hi` | Lihat harem dalam format gambar |
| `$hibrowse` | — | Browse harem dalam mode gambar interaktif |
| `$hv` | — | Harem dengan nilai kakera ditampilkan |
| `$harempage [nomor]` | `$hp` | Langsung ke halaman tertentu di harem |
| `$dk [nama karakter]` | — | Cek detail karakter di harem kamu |
| `$limroul` | `$lroul`, `$lr` | Roll hanya karakter yang ada di wish list harem |

### Filter Harem

| Command | Deskripsi |
|---|---|
| `$harem -p [seri]` | Filter harem berdasarkan **seri/franchise** |
| `$harem -k` | Urutkan berdasarkan **kakera value** |
| `$harem -r` | Urutkan berdasarkan **rank** |
| `$harem -n` | Urutkan berdasarkan **nama** |
| `$harem -s` | Tampilkan hanya karakter dengan **soulmate** |

---

## 💎 Kakera & Gem

Kakera adalah mata uang utama Mudae yang didapat dari berbagai aktivitas.

| Command | Alias | Deskripsi |
|---|---|---|
| `$kakerainfo` | `$ki` | Lihat total kakera kamu |
| `$daily` | `$dl` | Klaim kakera harian (bisa dikombinasikan dengan `$dailykakera`) |
| `$dailykakera` | `$dk` | Klaim bonus kakera harian tambahan |
| `$kakerashop` | `$ks` | Buka toko untuk membeli power-up dengan kakera |
| `$kakerashopbuy [item]` | `$ksb` | Beli item dari kakera shop |
| `$give [user] [jumlah]k` | — | Kirim kakera ke user lain |
| `$kakerarank` | `$krank` | Lihat leaderboard kakera di server |
| `$kakerarankg` | `$krankg` | Lihat leaderboard kakera global |

### Nilai Kakera Karakter

Karakter memiliki nilai kakera berdasarkan popularitasnya:
- 🔵 **Biru** — Karakter umum (~10–30 kakera)
- 🟣 **Ungu** — Karakter agak populer (~30–100 kakera)
- 🟠 **Oranye** — Karakter populer (~100–300 kakera)
- ❤️ **Merah** — Karakter sangat populer (~300–500 kakera)
- 🩷 **Pink** — Karakter ultra populer (~500+ kakera)

---

## ⭐ Wish List

Tandai karakter impian agar lebih mudah mendapatkannya.

| Command | Alias | Deskripsi |
|---|---|---|
| `$wish [nama karakter]` | `$wishlist` | Tambahkan karakter ke wish list |
| `$unwish [nama karakter]` | — | Hapus karakter dari wish list |
| `$wishlist` | `$wl` | Lihat wish list kamu |
| `$wishlist [user]` | — | Lihat wish list user lain |
| `$wishe [nama seri]` | — | Tambahkan **seluruh seri** ke wish list |
| `$unwishe [nama seri]` | — | Hapus seluruh seri dari wish list |
| `$wishrank` | `$wr` | Lihat urutan karakter wish list berdasarkan popularitas |

> 💡 **Tips:** Karakter di wish list akan diberi tanda ⭐ saat muncul di roll, dan kamu bisa mendapat notifikasi.

---

## ⏰ Daily & Timer

| Command | Alias | Deskripsi |
|---|---|---|
| `$tu` | `$timeup`, `$timeuse` | Lihat sisa waktu roll, klaim, dan daily kamu |
| `$daily` | `$dl` | Ambil bonus kakera harian |
| `$vote` | — | Link untuk vote bot di top.gg (dapat bonus roll) |
| `$votecheck` | `$vc` | Cek apakah kamu sudah vote hari ini |
| `$rollcheck` | `$rc` | Lihat berapa roll yang tersisa |

---

## 💔 Pernikahan & Divorsi

| Command | Alias | Deskripsi |
|---|---|---|
| `$marry [nama]` | `$m` | Klaim karakter (saat muncul dari roll) |
| `$divorce [nama]` | `$dv` | Lepaskan/hapus karakter dari harem kamu |
| `$divorceall` | — | Lepaskan **semua** karakter sekaligus (⚠️ tidak bisa dibatalkan!) |
| `$loveships` | `$ls` | Lihat "love ship" antar karakter di server |
| `$loveship [karakter 1] $ [karakter 2]` | — | Cek kompatibilitas dua karakter |

> ⚠️ **Peringatan:** `$divorceall` akan menghapus semua karakter secara permanen!

---

## 🔄 Trade & Give

Tukarkan atau berikan karakter kepada user lain.

| Command | Alias | Deskripsi |
|---|---|---|
| `$trade [user] $ [karakter kamu] $ [karakter mereka]` | `$t` | Ajukan penawaran trade karakter |
| `$give [user] [nama karakter]` | — | **Berikan** karakter kamu secara gratis ke user lain |
| `$give [user] [jumlah]k` | — | Berikan kakera ke user lain |
| `$tradeaccept` | `$ta` | Terima tawaran trade |
| `$tradedeny` | `$td` | Tolak tawaran trade |

> 💡 **Format trade:** `$t @user $ KarakterKamu $ KarakterMereka`

---

## 🔍 Info Karakter

| Command | Alias | Deskripsi |
|---|---|---|
| `$im [nama karakter]` | `$imagechar` | Lihat gambar karakter beserta info singkat |
| `$cl [nama karakter]` | `$characterlook` | Cek detail karakter: rank, seri, siapa yang punya |
| `$clrank [nama karakter]` | — | Lihat rank global karakter |
| `$mainms [nama karakter]` | — | Tampilkan gambar utama karakter |
| `$imgclaim [nama karakter]` | `$ic` | Ganti gambar karakter di harem kamu |
| `$imgclaim [nama] [nomor]` | — | Pilih gambar ke-N untuk karakter |
| `$imgboard` | — | Lihat papan gambar karakter populer |
| `$seriesinfo [nama seri]` | `$si` | Info lengkap tentang satu seri/franchise |

---

## 💑 Soulmate

Sistem soulmate menghubungkan dua user secara khusus.

| Command | Alias | Deskripsi |
|---|---|---|
| `$soulmate [user]` | `$sm` | Jadikan seseorang sebagai soulmate kamu |
| `$unsoulmate` | — | Putuskan ikatan soulmate |
| `$soulmatecheck` | `$smc` | Lihat soulmate kamu saat ini |
| `$soulmateroll` | `$smr` | Roll karakter bersama soulmate |

> 💡 Soulmate berbagi beberapa bonus dan bisa berkolaborasi dalam roll.

---

## 🎯 Minigame

| Command | Alias | Deskripsi |
|---|---|---|
| `$mudaequiz` | `$mq` | Tebak karakter dari petunjuk (minigame) |
| `$readycheck` | `$ready` | Cek apakah kamu siap untuk event |
| `$battle` | — | Sistem battle antar karakter (jika tersedia) |
| `$top` | — | Lihat karakter paling populer di server |
| `$topg` | — | Lihat karakter paling populer secara global |
| `$toprank` | `$tr` | Leaderboard rank karakter di server |

---

## ⚙️ Pengaturan Server (Admin)

Command ini hanya bisa digunakan oleh **administrator server**.

### Pengaturan Roll & Klaim

| Command | Deskripsi |
|---|---|
| `$setrolls [jumlah]` | Atur jumlah roll per interval untuk semua member |
| `$setclaims [jumlah]` | Atur jumlah klaim per interval |
| `$rollinterval [menit]` | Atur interval reset roll |
| `$claiminterval [menit]` | Atur interval reset klaim |
| `$rollreset` | Reset roll semua member secara manual |
| `$claimreset` | Reset klaim semua member secara manual |

### Pengaturan Channel

| Command | Deskripsi |
|---|---|
| `$channelset` | Atur channel khusus untuk Mudae |
| `$channeladd` | Tambah channel yang diizinkan |
| `$channelremove` | Hapus channel dari daftar yang diizinkan |
| `$disablechannel` | Nonaktifkan Mudae di channel tertentu |

### Pengaturan Karakter & Seri

| Command | Deskripsi |
|---|---|
| `$disable [nama seri]` | Nonaktifkan seri tertentu dari roll di server |
| `$enable [nama seri]` | Aktifkan kembali seri yang dinonaktifkan |
| `$disablelist` | Lihat daftar seri yang dinonaktifkan |
| `$restrict [nama seri]` | Batasi seri hanya untuk role tertentu |
| `$unrestrict [nama seri]` | Hapus batasan role pada seri |

### Pengaturan Lainnya

| Command | Deskripsi |
|---|---|
| `$prefix [karakter]` | Ganti prefix bot (default: `$`) |
| `$reactclaim` | Aktifkan/nonaktifkan klaim via reaksi 💖 |
| `$togglesnipe` | Aktifkan/nonaktifkan fitur snipe |
| `$toggledm` | Aktifkan/nonaktifkan notifikasi DM |
| `$settings` | Lihat semua pengaturan server saat ini |
| `$settingsreset` | Reset semua pengaturan ke default |

---

## 🧩 Tips & Trik

- **Maksimalkan roll:** Gunakan `$tu` untuk cek kapan roll kamu reset, jangan sampai terbuang.
- **Wish list dulu:** Sebelum banyak roll, masukkan karakter incaran ke wish list agar langsung terdeteksi.
- **Snipe:** Kalau ada yang gagal klaim karakter bagus, kamu bisa snipe sebelum waktu habis.
- **Kakera farming:** Selalu ambil `$daily` setiap hari dan vote untuk bonus kakera gratis.
- **Trade strategis:** Gunakan trade untuk mendapat karakter yang tidak bisa kamu dapat sendiri.
- **Soulmate:** Bermain bersama soulmate bisa memberikan bonus dan pengalaman yang lebih menyenangkan.

---

## 📚 Referensi Tambahan

- [Mudae Official Website](https://mudae.net)
- [Mudae Wiki](https://mudae.fandom.com)
- [Mudae Support Server](https://discord.gg/mudae)
- Gunakan `$help` di Discord untuk melihat daftar command langsung dari bot.

---

> *Dokumen ini dibuat berdasarkan command Mudae yang umum digunakan. Beberapa command mungkin berbeda tergantung versi bot dan pengaturan server.*
