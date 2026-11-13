# 🚀 AI Prompt Skills Library

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)

Selamat datang di **AI Prompt Skills Library**! Repositori ini berisi koleksi *System Prompts* (Instruksi Sistem) tingkat lanjut yang dirancang khusus untuk mengoptimalkan kinerja Large Language Models (LLM) seperti ChatGPT, Gemini, Claude, dan lainnya. 

Dengan menggunakan skill/prompt di dalam repositori ini, Anda dapat mengubah AI asisten standar menjadi spesialis di berbagai bidang, mulai dari *Software Engineering*, *Creative Direction*, hingga *Professional Writing*.

---

## 📂 Struktur Repositori

Skill-skill di dalam repositori ini dikategorikan berdasarkan fungsinya agar mudah ditemukan:

```text
📁 ai-prompt-skills-library/
│
├── 📄 README.md
│
├── 📁 developer/
│   ├── vibe-coding.md          # Spesialis pembuatan aplikasi end-to-end & debugging
│   └── anatomi-prompt-v2.md    # Framework konversi prompt singkat menjadi master prompt
│
├── 📁 creative/
│   ├── design-visual-prompter.md # Generator prompt presisi untuk Midjourney/DALL-E
│   └── scene-storyboard-director.md # Konseptor visual dan penceritaan adegan (storyboard)
│
└── 📁 writing/
    └── anti-slop.md            # Filter penulisan untuk teks natural, manusiawi, dan to-the-point
```

---

## 🛠️ Daftar Skill

Berikut adalah deskripsi singkat dari masing-masing skill yang tersedia:

### 1. Developer Skills
*   **[Anatomi Prompt v2](./developer/anatomi-prompt-v2.md)**: Mengubah instruksi acak dan singkat dari pengguna menjadi struktur prompt profesional yang terdiri dari Role, Task, Context, Reasoning, Stop Conditions, dan Output.
*   **[Vibe Coding](./developer/vibe-coding.md)**: Sistem instruksi untuk *Full-Stack Developer AI* yang memberikan kode utuh, bebas error, terintegrasi, dan panduan instalasi siap pakai tanpa teks narasi yang berlebihan.

### 2. Creative Skills
*   **[Design & Visual Prompter](./creative/design-visual-prompter.md)**: Mengonversi ide kasar menjadi prompt visual tingkat tinggi yang memperhatikan subjek, *style*, pencahayaan, jenis kamera, dan rasio aspek.
*   **[Scene & Storyboard Director](./creative/scene-storyboard-director.md)**: Merancang visualisasi adegan berurutan untuk kebutuhan video, komik, atau animasi dengan detail pergerakan kamera dan komposisi layar.

### 3. Writing Skills
*   **[Anti-Slop (Humanized Text)](./writing/anti-slop.md)**: Mencegah AI menghasilkan teks dengan gaya bahasa generik/robotik. Skill ini memaksa AI menulis dengan lugas, padat, alami, dan tanpa basa-basi mekanis.

---

## 💡 Cara Penggunaan

Anda dapat mengimplementasikan skill ini pada berbagai platform AI:

1. **Untuk OpenAI (Custom GPTs):**
   * Masuk ke menu pembuatan Custom GPT.
   * Salin seluruh teks dari salah satu file `.md` (contoh: `anti-slop.md`).
   * Tempelkan ke kolom **Instructions**.
2. **Untuk Google Gemini atau Anthropic Claude:**
   * Fitur *System Instructions* (biasanya tersedia di API atau fitur lanjutan).
   * Salin isi teks `.md` dan jadikan sebagai aturan dasar/sistem bagi sesi percakapan Anda.
3. **Penggunaan Standar (Prompting biasa):**
   * Salin isi file `.md`.
   * Tempel di awal percakapan Anda dengan AI dan tambahkan perintah: *"Gunakan instruksi berikut untuk seluruh percakapan kita ke depan: [Paste teks di sini]"*.

---

## 🤝 Kontribusi (Contributing)

Kontribusi sangat terbuka! Jika Anda memiliki *system prompt* atau skill AI baru yang berguna dan ingin ditambahkan ke repositori ini:

1. *Fork* repositori ini.
2. Buat *branch* baru untuk fitur atau skill Anda (`git checkout -b fitur/skill-baru`).
3. Tambahkan file Markdown (`.md`) Anda ke dalam kategori folder yang sesuai.
4. *Commit* perubahan Anda (`git commit -m 'Menambahkan skill [Nama Skill]'`).
5. *Push* ke *branch* Anda (`git push origin fitur/skill-baru`).
6. Buka *Pull Request*.

---

## 📜 Lisensi

Proyek ini dilisensikan di bawah **MIT License**. Anda bebas menggunakan, memodifikasi, dan mendistribusikan ulang karya ini baik untuk kebutuhan personal maupun komersial.