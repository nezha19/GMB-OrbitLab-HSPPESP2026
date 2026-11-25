# OrbitLab — Remediasi Gerak Melingkar Beraturan

## Menjalankan di VS Code
1. Ekstrak folder `remediasi_gmb`.
2. Buka folder tersebut di VS Code.
3. Buka `index.html` dengan ekstensi **Live Server** (klik kanan → Open with Live Server), atau buka langsung di browser.
4. Masukkan nama dan asal sekolah untuk memulai.

## Isi
- Slide 1: identitas siswa.
- Slide 2: beranda dan navigasi.
- Slide 3: materi GMB dan diagram vektor.
- Slide 4: laboratorium virtual dengan eksperimen GMB, enam fenomena, serta kontrol arah putaran roda dan pemilihan titik untuk mengamati vektor kecepatan sudut dan linear.
- Slide 5: enam soal latihan, pilihan alasan, tingkat keyakinan 0–5, umpan balik, dan skor.

## Catatan penting
- Seluruh simulasi dibuat dengan HTML Canvas dan JavaScript; tidak memerlukan library animasi eksternal.
- Pada eksperimen GMB, pilih searah atau berlawanan jarum jam, lalu klik titik pada roda. Simbol ⊗ menandakan vektor kecepatan sudut masuk bidang kertas (searah jarum jam dari tampak depan), sedangkan ⊙ menandakan keluar bidang kertas (berlawanan jarum jam). Vektor kecepatan linear selalu tangensial pada titik yang dipilih.
- Rumus utama: `v = ωr`, `a_s = v²/r = ω²r`, `F_s = m a_s`, `T = 2π/ω`.
- Pada skenario bola/tali dan mesin cuci, lintasan tangensial menggambarkan arah gerak sesaat setelah benda tidak lagi dipaksa mengikuti lintasan melingkar. Gaya lain seperti gravitasi dapat memengaruhi lintasan berikutnya.
- Pada skenario motor di tikungan datar, gesekan statis ban-jalan dapat menyediakan resultan gaya menuju pusat.
- Versi ini merupakan prototipe front-end. Data identitas dan hasil latihan belum dikirim atau disimpan ke database/server.
