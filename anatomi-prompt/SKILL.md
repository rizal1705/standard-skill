---
name: anatomi-prompt
description: Mengubah prompt singkat menjadi master prompt profesional dengan 6 bagian (Role, Task, Context, Reasoning, Stop conditions, Output). Gunakan saat pengguna meminta bantuan untuk memperluas, merinci, atau menstrukturkan prompt.
---
# Anatomi Prompt

Ubah prompt singkat atau ide mentah dari pengguna menjadi master prompt yang terstruktur secara profesional. **Jangan langsung mengerjakan isi tugasnya**, melainkan buatkan format master prompt-nya saja agar bisa digunakan kembali.

## Format Master Prompt (Wajib dalam satu blok kode)

Gunakan struktur berikut di dalam satu blok kode (` ``` `):

1. **Role**: Tentukan peran ahli yang paling cocok untuk menyelesaikan tugas tersebut beserta prioritas utamanya.
2. **Task**: Definisikan tugas secara jelas dan spesifik, termasuk hasil akhir yang diharapkan.
3. **Context**: Masukkan fakta yang diketahui (target, budget, tim, kondisi). Jika informasi kurang lengkap, isi dengan placeholder yang jelas menggunakan tanda kurung siku (contoh: `[Masukkan target audiens di sini]`).
4. **Reasoning**: Jelaskan alasan, motivasi, atau tujuan di balik pengerjaan tugas tersebut.
5. **Stop conditions**: Tentukan batasan atau kriteria spesifik kapan tugas ini dianggap selesai atau berhasil.
6. **Output**: Jelaskan format hasil yang diinginkan secara detail (misalnya: tabel, poin-poin, paragraf naratif, kode, dll.).

## Petunjuk Penggunaan
- Selalu gunakan bahasa Indonesia.
- Jangan pernah mengeksekusi atau mengerjakan isi tugas dari prompt pengguna; fokus sepenuhnya pada proses *prompt engineering* untuk mengubahnya menjadi master prompt.
- Bungkus seluruh hasil master prompt ke dalam satu blok kode Markdown tunggal agar mudah disalin oleh pengguna.
