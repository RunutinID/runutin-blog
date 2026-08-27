# 📚 Blog Runutin — Tag Index

> File ini adalah hub pusat untuk visualisasi hubungan antar konten blog.
> Galaxy View akan membaca tag dan link di sini untuk menampilkan graph koneksi.
> **Kembali ke:** [[Home]] · **Suasana lain:** [[../Module/Module\|Module]] · [[../Project/Project\|Project]]

---

## 🏷️ Tag Index

### `elektronik`
Topik dasar elektronik dan komponen.

| Post | Slug | Tags Lain | Koneksi |
|------|------|-----------|---------|
| [[Blog/elektronik/Apa itu Arduino/blog\|Apa itu Arduino]] | `apa-itu-arduino` | `arduino` `microcontroller` `prototype` | → Sejarah Arduino, → Breadboard, → ESP32 |
| [[Blog/elektronik/Apa itu ESP32/blog\|Apa itu ESP32]] | `apa-itu-esp32` | `esp32` `iot` `microcontroller` | → Arduino, → Module/ESP32 |
| [[Blog/elektronik/Apa itu Breadboard/blog\|Apa itu Breadboard]] | `apa-itu-breadboard` | `breadboard` `prototype` `arduino` | → Arduino |
| [[Blog/elektronik/Mengenal sejarah terciptanya Arduino/blog\|Sejarah Arduino]] | `mengenal-sejarah-terciptanya-arduino` | `arduino` `sejarah teknologi` `open source` | → Arduino |

---

### `arduino`
Semua konten yang terkait Arduino.

| Post | Slug | Tags Lain | Koneksi |
|------|------|-----------|---------|
| [[Blog/elektronik/Apa itu Arduino/blog\|Apa itu Arduino]] | `apa-itu-arduino` | `elektronik` `microcontroller` `prototype` | → Sejarah Arduino, → Breadboard, → ESP32 |
| [[Blog/elektronik/Apa itu Breadboard/blog\|Apa itu Breadboard]] | `apa-itu-breadboard` | `elektronik` `breadboard` `prototype` | → Arduino |
| [[Blog/elektronik/Mengenal sejarah terciptanya Arduino/blog\|Sejarah Arduino]] | `mengenal-sejarah-terciptanya-arduino` | `elektronik` `sejarah teknologi` `open source` | → Arduino |

---

### `microcontroller`
Board dan chip untuk embedded project.

| Post | Slug | Tags Lain | Koneksi |
|------|------|-----------|---------|
| [[Blog/elektronik/Apa itu Arduino/blog\|Apa itu Arduino]] | `apa-itu-arduino` | `elektronik` `arduino` `prototype` | → ESP32, → Sejarah Arduino, → Breadboard |
| [[Blog/elektronik/Apa itu ESP32/blog\|Apa itu ESP32]] | `apa-itu-esp32` | `elektronik` `esp32` `iot` | → Arduino, → Module/ESP32 |

---

### `prototype`
Alat dan teknik untuk percobaan awal.

| Post | Slug | Tags Lain | Koneksi |
|------|------|-----------|---------|
| [[Blog/elektronik/Apa itu Arduino/blog\|Apa itu Arduino]] | `apa-itu-arduino` | `elektronik` `arduino` `microcontroller` | → Breadboard, → ESP32, → Sejarah Arduino |
| [[Blog/elektronik/Apa itu Breadboard/blog\|Apa itu Breadboard]] | `apa-itu-breadboard` | `elektronik` `breadboard` `arduino` | → Arduino |

---

### `iot`
Internet of Things dan konektivitas.

| Post | Slug | Tags Lain | Koneksi |
|------|------|-----------|---------|
| [[Blog/elektronik/Apa itu ESP32/blog\|Apa itu ESP32]] | `apa-itu-esp32` | `elektronik` `esp32` `microcontroller` | → Arduino, → Module/ESP32 |

---

### `ai`
Kecerdasan buatan dan ChatGPT.

| Post | Slug | Tags Lain | Koneksi |
|------|------|-----------|---------|
| [[Blog/ai/membuat-custom-gpts-sendiri/blog\|Membuat Custom GPTs]] | `membuat-custom-gpts-sendiri` | `AI` `ChatGPT` `Custom GPTs` | _(terisolasi dari elektronik)_ |

---

## 🔗 Cross-Reference Map

```
                    ┌─────────────────┐
                    │ Apa itu Arduino │
                    └────────┬────────┘
                             │
            ┌────────────────┼────────────────┐
            ▼                ▼                ▼
    ┌───────────────┐ ┌─────────────┐ ┌──────────────────┐
    │ Sejarah       │ │ Breadboard  │ │ Apa itu ESP32    │
    │ Arduino       │ │             │ │                  │
    └───────────────┘ └─────────────┘ └────────┬─────────┘
                                               │
                                               ▼
                                      ┌────────────────┐
                                      │ Module/ESP32   │
                                      │ (Basic, Sensor,│
                                      │  Actuator,     │
                                      │  Display)      │
                                      └────────────────┘

    ┌─────────────────┐
    │ Custom GPTs     │  ← terisolasi dari cluster elektronik
    └─────────────────┘
```

---

## 📂 Folder Structure

```
Blog/
├── README.md                          ← file ini (tag hub)
├── ai/
│   └── membuat-custom-gpts-sendiri/
│       ├── blog.md
│       ├── hero-prompt.md
│       └── ilustration-prompt.md
└── elektronik/
    ├── Apa itu Arduino/
    │   ├── blog.md
    │   ├── hero-prompt.md
    │   ├── ilustration-prompt.md
    │   ├── apa-itu-arduino-hero.png/.webp
    │   └── illustration/ (16 gambar)
    ├── Apa itu Breadboard/
    │   ├── blog.md
    │   ├── hero-prompt.md
    │   ├── ilustration-prompt.md
    │   ├── apa-itu-breadboard-hero.png/.webp
    │   └── illustration/ (8 gambar)
    ├── Apa itu ESP32/
    │   ├── blog.md
    │   ├── hero-prompt.md
    │   ├── ilustration-prompt.md
    │   ├── apa-itu-esp32-hero.png/.webp
    │   └── illustration/ (8 gambar)
    └── Mengenal sejarah terciptanya Arduino/
        ├── blog.md
        ├── hero-prompt.md
        ├── ilustration-prompt.md
        ├── mengenal-sejarah-terciptanya-arduino-hero.png/.webp
        └── illustration/ (6 gambar)
```

---

## 🎯 Status Konten

| Post | Blog | Hero Prompt | Ilustrasi | Post IG | YouTube |
|------|------|-------------|-----------|---------|---------|
| Apa itu Arduino | ✅ | ✅ | ✅ (16) | ✅ (7 slide) | ✅ |
| Apa itu ESP32 | ✅ | ✅ | ✅ (8) | ✅ (8 slide) | — |
| Apa itu Breadboard | ✅ | ✅ | ✅ (8) | — | — |
| Sejarah Arduino | ✅ | ✅ | ✅ (6) | ✅ (8 slide) | — |
| Custom GPTs | ✅ | ✅ | — | — | — |

---

## 🔧 Cara Update

Setiap kali menambah blog post baru:
1. Buat folder di `elektronik/` atau `ai/`
2. Buat `blog.md`, `hero-prompt.md`, `ilustration-prompt.md`
3. Tambahkan baris di tabel tag yang relevan di file ini
4. Update cross-reference map jika ada koneksi baru
5. Galaxy View akan otomatis membaca link `[[...]]` ini
