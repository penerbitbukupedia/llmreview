# Prompt untuk Deteksi Naskah Buku yang Dihasilkan LLM

## Instruksi Analisis

Analisis naskah berikut untuk mengidentifikasi kemungkinan penggunaan LLM dalam penulisan. Perhatikan indikator-indikator berikut:

### 1. Penggunaan Emoticon dan Karakter Khusus
- [ ] Emoticon berlebihan atau tidak konsisten (😊, 😢, 🤔, dll.)
- [ ] Penggunaan emoji yang tidak sesuai konteks formal buku
- [ ] Karakter khusus yang tidak biasa: ★, ♦, ◆, •, ▪, ▫
- [ ] Bullet points atau formatting yang tidak konsisten

### 2. Pola Tanda Baca Mencurigakan
- [ ] **Penggunaan dash berlebihan**: em-dash (—) yang terlalu sering
- [ ] **Triple dash**: --- yang berulang
- [ ] **Elipsis berlebihan**: ... di akhir kalimat tanpa alasan jelas
- [ ] Kombinasi tanda baca aneh: ?!, !?, ---, ***

### 3. Pola Bahasa dan Struktur LLM
- [ ] **Frasa transisi berlebihan**: "Selain itu", "Lebih lanjut", "Penting untuk dicatat"
- [ ] **Struktur list berulang**: Poin 1, 2, 3 tanpa variasi
- [ ] **Pengulangan kata kunci** yang tidak natural
- [ ] **Kalimat pembuka klise**: "Dalam era digital ini", "Tidak dapat dipungkiri bahwa"

### 4. Ciri Khas Output LLM Lainnya
- [ ] **Konsistensi berlebihan** dalam gaya penulisan
- [ ] **Vocabulary range terbatas** - penggunaan kata yang itu-itu saja
- [ ] **Absence of personal voice** - suara penulis yang generik
- [ ] **Overuse of qualifiers**: "mungkin", "dapat", "cenderung", "pada umumnya"

### 5. Overclaim dan Data Mencurigakan
- [ ] **Klaim berlebihan tanpa bukti**: Pernyataan superlativ tanpa data pendukung
- [ ] **Statistik yang terlalu bulat**: "90% ahli setuju", "100% efektif"
- [ ] **Referensi samar**: "Penelitian menunjukkan", "Para ahli berpendapat" tanpa sumber spesifik
- [ ] **Data yang terlalu pas**: Angka yang sangat cocok dengan narasi
- [ ] **Generalisasi berlebihan**: "Semua orang", "Tidak pernah", "Selalu"

### 6. Red Flags Referensi dan Sumber
- [ ] **Kutipan tanpa sumber jelas**: Quote tanpa nama/tahun/publikasi
- [ ] **Referensi generik**: "Menurut studi terbaru" tanpa detail
- [ ] **Pola sitasi mencurigakan**: Format sitasi yang tidak konsisten
- [ ] **Sumber yang tidak bisa diverifikasi**: Website/jurnal yang tidak ada
- [ ] **Tanggal publikasi mencurigakan**: Terlalu baru atau terlalu spesifik

### 7. Struktur dan Organisasi
- [ ] **Paragraf dengan panjang seragam** (terlalu konsisten)
- [ ] **Transisi yang terlalu mulus** antar paragraf
- [ ] **Struktur bab yang sangat sistematis** tanpa variasi natural
- [ ] **Conclusion yang selalu merangkum** dengan formula sama

## Format Laporan Analisis

**HASIL ANALISIS NASKAH**

**Judul:** [Masukkan judul naskah]
**Panjang:** [Jumlah halaman/kata]
**Tanggal analisis:** [Tanggal]

### Temuan Utama:
1. **Skor Kecurigaan:** [1-10, dimana 10 = sangat mencurigakan]
2. **Indikator Terkuat:**
   - [Sebutkan 3-5 indikator paling kuat]

### Detail Temuan:
**Emoticon & Karakter Khusus:**
- [Deskripsi temuan]

**Pola Tanda Baca:**
- [Deskripsi temuan]

**Pola Bahasa:**
- [Deskripsi temuan]

**Overclaim & Data:**
- [Deskripsi temuan]

**Referensi & Sumber:**
- [Deskripsi temuan]

**Struktur & Organisasi:**
- [Deskripsi temuan]

### Contoh Spesifik:
[Berikan 3-5 kutipan langsung yang menunjukkan ciri LLM]

### Rekomendasi:
- [ ] **RENDAH** (1-3): Kemungkinan kecil hasil LLM
- [ ] **SEDANG** (4-6): Perlu investigasi lebih lanjut
- [ ] **TINGGI** (7-8): Kemungkinan besar hasil LLM
- [ ] **SANGAT TINGGI** (9-10): Hampir pasti hasil LLM

### Catatan Tambahan:
[Observasi lain yang relevan]

---

## Tips Penggunaan Prompt:

1. **Gunakan sampling**: Pilih 5-10 halaman acak dari berbagai bagian buku
2. **Perhatikan konsistensi**: Bandingkan gaya antar bab
3. **Cek metadata**: Waktu penulisan yang terlalu cepat bisa mencurigakan  
4. **Cross-reference**: Bandingkan dengan karya penulis sebelumnya
5. **Gunakan tools**: Pertimbangkan AI detection tools sebagai referensi tambahan

## Disclaimer:
Analisis ini bersifat indikatif dan tidak 100% akurat. Selalu kombinasikan dengan judgment manusia dan pertimbangan konteks lainnya.
