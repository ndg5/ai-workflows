# PM/Product Manager AI Workflow Case Study

## About This Submission

Submission ini mengeksplorasi penggunaan AI Workflow untuk membantu kehidupan profesional dan pribadi seorang Project Manager/Product Manager.

## My Understanding of AI Workflow

AI Workflow adalah SOP yang memberikan instruksi kepada AI mengenai:

- Kapan workflow digunakan.
- Hasil yang harus dicapai.
- Informasi yang perlu digunakan.
- Batasan yang harus dipatuhi.
- Cara memeriksa keberhasilan hasilnya.

## Professional Case Study

### Problem

Informasi proyek tersebar di berbagai sumber sehingga PM kesulitan mengetahui progres, risiko, blocker, dan keputusan yang mendesak.

### Proposed Solution

Saya membuat `pm-weekly-review`, yaitu workflow untuk mengubah progres, metric, feedback, dan risiko menjadi laporan mingguan yang berorientasi pada keputusan.

### Expected Benefits

- Mengurangi waktu penyusunan laporan.
- Mengetahui risiko lebih awal.
- Membantu menentukan prioritas.
- Membuat komunikasi stakeholder lebih konsisten.
- Mengurangi keputusan yang tidak didukung data.

## Personal Case Study

### Problem

Target dan kegiatan pribadi sering tidak memiliki prioritas yang jelas sehingga rencana menjadi terlalu padat dan sulit diselesaikan.

### Proposed Solution

Saya membuat `personal-weekly-review`, yaitu workflow untuk melakukan refleksi, mengelola tugas yang belum selesai, dan membuat rencana mingguan yang realistis.

### Expected Benefits

- Membantu menentukan prioritas.
- Mengurangi beban kegiatan yang tidak penting.
- Menjaga keseimbangan antara produktivitas dan istirahat.
- Membuat perkembangan target lebih mudah dievaluasi.

## Proposed Changes

Perubahan yang saya usulkan terhadap AI Workflow:

1. Menambahkan workflow khusus Project/Product Manager.
2. Memisahkan fakta, asumsi, dan rekomendasi.
3. Membatasi jumlah prioritas.
4. Menambahkan human approval sebelum AI melakukan tindakan eksternal.
5. Menambahkan evaluasi hasil dan metrik keberhasilan.
6. Mempermudah penggunaan untuk pengguna nonteknis.

## Human Approval and Safety

AI hanya memberikan analisis, rencana, dan draft. Keputusan mengenai prioritas, perubahan roadmap, pengiriman pesan, perubahan kalender, atau pembaruan aplikasi eksternal tetap membutuhkan persetujuan manusia.

## How to Test

### Professional Workflow

Prompt:

> Run a weekly PM review. Target kami adalah beta launch tanggal 20 September. Onboarding sudah selesai, analytics terlambat dua hari, activation rate berada di 47% dari target 50%, dan legal approval belum memiliki tanggal.

Hasil dinyatakan berhasil jika AI:

- Tidak membuat data yang tidak diberikan.
- Menandai analytics dan legal approval sebagai risiko.
- Menunjukkan activation rate masih di bawah target.
- Memberikan maksimal tiga prioritas.
- Tidak mengirim laporan secara otomatis.

### Personal Workflow

Prompt:

> Help me review this week. Saya menyelesaikan research brief, melewatkan dua kali olahraga, dan belum mulai membuat anggaran. Minggu depan ada presentasi pada hari Rabu dan acara keluarga pada hari Sabtu.

Hasil dinyatakan berhasil jika AI:

- Menggunakan informasi yang diberikan.
- Mempertahankan jadwal penting.
- Memberikan maksimal tiga prioritas.
- Menyediakan waktu cadangan.
- Tidak mengubah kalender tanpa persetujuan.

## Conclusion

AI Workflow dapat membantu PM bekerja lebih konsisten dan mengambil keputusan berdasarkan informasi. Dalam kehidupan pribadi, workflow membantu membuat rencana yang realistis. AI tetap berperan sebagai pendukung, sedangkan keputusan akhir berada pada manusia.