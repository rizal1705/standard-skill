---
name: vibe-coding
description: Membuat kode utuh untuk aplikasi baru dan mengoreksi error hingga berjalan normal. Aktif saat diminta membuat aplikasi, web, komponen, atau memperbaiki bug kode.
---
# Vibe Coding

Skill ini dirancang untuk menghasilkan kode aplikasi yang utuh, siap pakai, dan mengutamakan penyelesaian masalah (error correction) hingga aplikasi berjalan normal, langsung dari ide pengguna.

## Kapan Menggunakan Skill Ini
- Pengguna meminta untuk membuat aplikasi baru, komponen web, atau script dari awal.
- Pengguna melaporkan error (debugging) pada kode dan meminta perbaikan.
- Pengguna memberikan deskripsi kasual tentang ide aplikasi dan ingin langsung mendapatkan kode fungsional.

## Aturan Utama (Vibe Coding)
1. **Pilih Stack Terbaik:** Secara otomatis pilih tech stack modern terbaik yang paling cocok dengan ide pengguna (misal: React/Vite + Tailwind untuk web, Python untuk skrip/data, Node.js untuk backend), KECUALI pengguna meminta stack tertentu.
2. **Kode Utuh (Copy-Paste Ready):** Berikan blok kode utuh yang siap disalin. JANGAN gunakan *placeholder* malas seperti `// letakkan logika Anda di sini` atau `// kode sebelumnya`. Tulis logika intinya hingga fungsional.
3. **Panduan Langkah-demi-Langkah:** Selalu sertakan instruksi ringkas dan jelas tentang:
   - Persiapan (nama file yang harus dibuat).
   - Instalasi *dependencies* (perintah terminal).
   - Cara menjalankan aplikasi/kode.
4. **Fokus pada Solusi (Koreksi Error):** Jika pengguna melaporkan error, jangan berikan teori panjang lebar. Langsung temukan masalahnya dan berikan kode yang sudah diperbaiki secara utuh agar pengguna bisa langsung *copy-paste* dan melanjutkan pekerjaan.

## Format Output yang Diharapkan
1. **Pilihan Stack:** Sebutkan stack yang dipakai (jika tidak ditentukan pengguna).
2. **Langkah Persiapan:** Perintah terminal untuk setup awal.
3. **Blok Kode:** Kode utuh (satu blok kode per file) dengan penanda nama file di bagian atas kode.
4. **Cara Run:** Perintah untuk mengeksekusi aplikasi.