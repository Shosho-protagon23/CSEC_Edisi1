# 🛡️ CSEC — Cyber Security Self-Paced Learning Vault (Edition 1)

Selamat datang! Ini adalah **bahan belajar cyber security mandiri (self-paced)** berbentuk **vault Obsidian** — 90+ catatan saling terhubung yang memetakan jalur belajar dari **nol** hingga topik lanjutan, mencakup **Red Team (offensive)**, **Blue Team (defensive)**, dan **Purple Team**.

Materi ditulis dalam **Bahasa Indonesia** untuk level **pemula total**, dengan istilah teknis tetap dalam Bahasa Inggris (sesuai praktik industri).

---

## 🚀 Cara Memakai (mulai di sini)

1. **Install [Obsidian](https://obsidian.md)** (gratis, Windows/Mac/Linux/Android/iOS).
2. Buka Obsidian → **"Open folder as vault"** → pilih folder hasil ekstrak ini (`CSEC_Edition_1`).
3. Buka file **`00 - START HERE.md`** — itu peta utama & titik masuk belajarmu.
4. Aktifkan **Graph View** (ikon lingkaran-titik di kiri) untuk melihat seluruh materi sebagai jaring koneksi.

> 💡 Vault ini bisa dibaca sebagai teks biasa (Markdown) tanpa Obsidian, tapi **navigasi link & graph** hanya optimal di dalam Obsidian.

---

## 🗂️ Struktur Folder

| Folder | Isi |
|---|---|
| `00 - START HERE.md` | Peta utama / titik masuk |
| `01 - Fondasi/` | Prasyarat wajib: CIA Triad, jaringan, OSI/TCP-IP, Linux, Windows/AD, kriptografi + seri **Lab** (setup VM rentan, jaringan, WiFi, IoT, OT/ICS, mobile) |
| `02 - Red Team/` | Jalur menyerang: recon → scanning → exploitation → privesc → AD → cloud/container, web/API, binary exploitation, evasion & C2 |
| `03 - Blue Team/` | Jalur bertahan: defense-in-depth, SOC/SIEM, log, IR, DFIR, threat hunting, detection engineering, hardening |
| `04 - Bersama (Red & Blue)/` | Threat Modeling, Purple Team, Sumber Belajar, Glosarium |
| `05 - Templates/` | Template catatan untuk menambah materi sendiri |

---

## 🧭 Alur Belajar Disarankan

```
01 - Fondasi  →  pilih jalur:  02 - Red Team   dan/atau   03 - Blue Team
                                      ↘                 ↙
                              04 - Bersama (Purple Team, Threat Modeling)
```

Setiap catatan materi memakai struktur konsisten **7 bagian**: Ringkasan → Konsep Inti → Cara Kerja/Praktik → Tools → Kaitan → Latihan → Sumber. Catatan Red & Blue **saling terhubung** (mis. *Privilege Escalation* ↔ *Hardening*) supaya kamu selalu melihat "sisi lawannya".

---

## ⚖️ Disclaimer Etika & Legalitas (PENTING)

> **Seluruh materi di vault ini ditujukan murni untuk EDUKASI dan pengujian yang SAH.**
>
> Gunakan teknik di sini **hanya** pada: sistem/akun milik sendiri, lab pribadi, platform latihan legal (TryHackMe, Hack The Box, PortSwigger, VulnHub, dsb.), atau engagement dengan **izin tertulis**.
>
> Mengakses, menguji, atau menyerang sistem **tanpa izin adalah ilegal** — di Indonesia diatur oleh **UU ITE** dan **UU PDP**, dan di negara lain oleh hukum setempat (mis. CFAA di AS). Penulis & distributor materi ini **tidak bertanggung jawab** atas penyalahgunaan.
>
> Catatan bertanda `[!danger]` / `[!warning]` menandai teknik *dual-use* atau berisiko fisik (mis. OT/ICS, automotive, akses fisik) — baca peringatannya sebelum praktik.

---

## 📦 Tentang Produk Ini

- **Edisi:** 1 (CSEC_Edition_1)
- **Format:** Obsidian Vault (Markdown `.md`), portabel & tahan-masa-depan (teks biasa).
- **Cakupan:** 90+ catatan, Red/Blue/Purple, fondasi → lanjutan, dengan lab praktik.
- **Lisensi penggunaan:** untuk pembelajaran pribadi. Hubungi penulis untuk distribusi ulang.

Selamat belajar — dan **hack responsibly**. 🔐
