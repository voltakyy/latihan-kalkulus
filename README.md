# Batas & Bentuk — Latihan UTS Kalkulus

Latihan soal pilihan ganda untuk UTS Kalkulus Reguler: **Pertidaksamaan**, **Domain & Range**, **Limit Aljabar**, dan **Limit Trigonometri**.

- 21 soal: 13 soal inti + 8 soal tantangan
- Pembahasan langkah demi langkah di setiap soal
- Lembar rumus bisa dibuka kapan saja saat latihan
- Urutan soal dan pilihan jawaban diacak
- Bisa dijawab dengan klik, tombol **1–4 / A–D**, lalu **Enter** untuk lanjut
- Rapor per topik, review jawaban salah, dan rekor tersimpan di browser

## Buka latihan

Langsung buka [`index.html`](index.html) di browser — tidak perlu install, build, atau server.

Lewat GitHub Pages: **https://voltakyy.github.io/latihan-kalkulus/**

## Catatan soal

Beberapa limit pada lembar UTS tidak menuliskan arah limit. Di latihan ini dipakai asumsi `x → ∞` / `t → ∞`, dan asumsi tersebut dijelaskan pada pembahasan. Typo `sin(-x) = sin x` pada lembar rumus juga sudah dikoreksi menjadi `sin(-x) = -sin x`.

## Menambah soal

Tambahkan object baru ke salah satu file di folder [`questions/`](questions/). Setiap soal berisi `topic`, `q`, `options`, `answer`, dan `explain`. Tandai `challenge: true` untuk soal tantangan. Grafik SVG tambahan dapat didaftarkan di [`figures.js`](figures.js).
