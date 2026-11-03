# Batas & Bentuk — Latihan UTS Kalkulus

Latihan soal pilihan ganda untuk UTS Kalkulus Reguler: **Bilangan & Modulo**, **Trigonometri**, **Fungsi & Invers**, **Pertidaksamaan**, **Domain & Range**, **Limit Aljabar**, dan **Limit Trigonometri**.

- 35 soal: 14 soal materi sendiri + 13 soal inti + 8 soal tantangan
- 14 soal materi sendiri selalu tampil di awal dengan urutan tetap 1–14
- Pembahasan langkah demi langkah di setiap soal
- Lembar rumus bisa dibuka kapan saja saat latihan
- Urutan soal inti dan tantangan diacak, begitu juga pilihan jawabannya
- Bisa dijawab dengan klik, tombol **1–4 / A–D**, lalu **Enter** untuk lanjut
- Rapor per topik, review jawaban salah, dan rekor tersimpan di browser

## Buka latihan

Langsung buka [`index.html`](index.html) di browser — tidak perlu install, build, atau server.

Lewat GitHub Pages: **https://voltakyy.github.io/latihan-kalkulus/**

## Catatan soal

Beberapa limit pada lembar UTS tidak menuliskan arah limit. Di latihan ini dipakai asumsi `x → ∞` / `t → ∞`, dan asumsi tersebut dijelaskan pada pembahasan. Typo `sin(-x) = sin x` pada lembar rumus juga sudah dikoreksi menjadi `sin(-x) = -sin x`.

Pada soal materi sendiri nomor 5, sumber hanya menuliskan `θ = 5π/6`; latihan meminta nilai `sin θ`, `cos θ`, dan `tan θ` sekaligus. Soal nomor 8 dan 14 ditulis dengan bentuk pecahan yang jelas: `f(x) = (3x−2)/(x+1)` dan `f(x) = 3/(x−4)`.

## Menambah soal

Tambahkan object baru ke salah satu file di folder [`questions/`](questions/). Setiap soal berisi `topic`, `q`, `options`, `answer`, dan `explain`. Tandai `challenge: true` untuk soal tantangan. Untuk soal pembuka yang urutannya tetap, tambahkan `intro: true` dan `introOrder` (angka urut). Grafik SVG tambahan dapat didaftarkan di [`figures.js`](figures.js).
