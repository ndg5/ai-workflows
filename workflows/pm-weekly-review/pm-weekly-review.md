---
trigger: Run a weekly PM review of project progress, product metrics, risks, decisions, and next-week priorities.
---

## Goal

Menghasilkan laporan mingguan yang membantu Project Manager atau Product Manager memahami kondisi proyek dan mengambil keputusan.

## Context

Gunakan data yang diberikan pengguna, seperti:

- Target produk atau proyek.
- Progres sprint dan milestone.
- Product metrics.
- Feedback pengguna.
- Blocker dan dependency.
- Risiko dan keputusan yang tertunda.

Langkah kerja:

1. Tentukan periode dan tujuan yang sedang dievaluasi.
2. Bandingkan hasil aktual dengan target.
3. Identifikasi progres, hambatan, dan risiko.
4. Pisahkan fakta, asumsi, dan informasi yang belum tersedia.
5. Tentukan keputusan yang membutuhkan perhatian PM.
6. Pilih maksimal tiga prioritas untuk minggu berikutnya.

Output harus terdiri dari:

### Executive Summary

Ringkasan kondisi proyek dalam tiga sampai lima poin.

### Progress and Evidence

Untuk setiap tujuan, tampilkan:

- Outcome.
- Evidence.
- Status: On Track, At Risk, Off Track, Done, atau Unknown.
- Alasan penentuan status.

### Risks and Dependencies

Tampilkan risiko, dampak, PIC jika tersedia, dan tindakan mitigasi.

### Decisions Needed

Tampilkan keputusan yang diperlukan, rekomendasi, alasan, dan deadline.

### Next-Week Priorities

Maksimal tiga prioritas. Setiap prioritas memiliki outcome, PIC, dan definisi selesai.

### Stakeholder Update

Buat draft laporan singkat untuk stakeholder.

## Constraints

- Jangan membuat data, metric, tanggal, progres, atau PIC yang tidak tersedia.
- Tandai asumsi dan informasi yang belum diketahui.
- Jangan mengubah prioritas proyek tanpa persetujuan PM.
- Jangan mengirim laporan secara otomatis.
- Jangan mengubah data pada aplikasi eksternal tanpa persetujuan.
- Fokus pada outcome dan keputusan, bukan daftar aktivitas yang panjang.

## Verify

- Periode laporan disebutkan dengan jelas.
- Setiap status memiliki evidence.
- Setiap risiko memiliki dampak dan tindakan berikutnya.
- Setiap keputusan memiliki rekomendasi.
- Prioritas minggu berikutnya maksimal tiga.
- Informasi yang tidak tersedia ditandai sebagai unknown.
- Stakeholder update hanya berupa draft dan belum dikirim.