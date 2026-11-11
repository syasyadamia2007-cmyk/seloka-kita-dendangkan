# seloka-kita-dendangkan
seloka tahun 6
Aplikasi pembelajaran interaktif Bahasa Melayu (Seni Bahasa), SK 4.2 dan SP 4.2.1.

## Kandungan
- `index.html` – aplikasi utama (HTML, CSS dan JavaScript tanpa framework).
- `assets/video-pembelajaran-seloka.mp4` – video pembelajaran kumpulan yang telah ditukar kepada MP4 untuk keserasian pelayar.

## Fungsi
- Perjalanan pembelajaran 12 langkah berasaskan urutan WHERETO.
- Video pembelajaran, nota murid, teks/bukti seloka dan pautan video akhir.
- Kuiz objektif automatik dan penilaian kendiri empat kemahiran.
- Dashboard pelajar: kemajuan, markah, tahap penguasaan dan maklum balas.
- Dashboard guru: purata kelas, analisis kemahiran dan prestasi tiga profil simulasi.
- Cadangan pemulihan/pengukuhan/pengayaan berdasarkan skor kemahiran.
- Simpanan data menggunakan `localStorage`.

## Jalankan secara setempat
Buka `index.html` dalam pelayar. Untuk ujian pelayan setempat, jalankan `python -m http.server 8000` dalam folder projek dan buka `http://localhost:8000`.

## Terbitkan melalui GitHub dan Render
1. Muat naik semua kandungan folder ini ke repositori GitHub (pastikan folder `assets` dan fail MP4 turut dimuat naik).
2. Di Render, pilih **New + → Static Site** dan sambungkan repositori.
3. Tetapkan **Build Command** kosong dan **Publish Directory** kepada `.`.
4. Klik **Create Static Site**. Gunakan URL Render yang dijana.

## Penting tentang data
Ini prototaip demonstrasi. `localStorage` menyimpan rekod dalam pelayar/peranti semasa sahaja. Data tidak diselaraskan antara peranti atau akaun berbeza. Untuk penggunaan sebenar satu kelas, sambungkan sistem log masuk dan pangkalan data awan (contohnya Supabase atau Firebase), serta tetapkan akses guru/murid.

## Kandungan yang perlu dilengkapkan oleh kumpulan
PDF tugasan tidak mengandungi teks penuh seloka atau pautan DLO Google Sites asal. Oleh itu, murid boleh menampal teks seloka sebenar pada ruangan “Jejak Pengajaran”. Jika kumpulan mempunyai pautan aktiviti/kuiz asal, masukkan semula pautan tersebut atau bina item pentaksiran khusus berdasarkan teks sebenar.
