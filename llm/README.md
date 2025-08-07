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
- [ ] **Kalimat terlalu sempurna**: Grammar dan struktur yang terlalu baku
- [ ] **Paragraf terlalu panjang dan detail** - LLM cenderung verbose
- [ ] **Menghindari fragmen kalimat** - selalu kalimat lengkap

### 4b. Ciri BUKAN LLM (Human Writing)
- [ ] **Kalimat tidak lengkap/fragmen** - gaya percakapan natural
- [ ] **Paragraf sangat pendek** - bahkan satu kalimat
- [ ] **Bullet points berlebihan** tanpa elaborasi
- [ ] **Gaya telegraphic** - singkat, padat, kadang tidak gramatikal
- [ ] **Inconsistent formatting** - human cenderung tidak rapi
- [ ] **Personal interjections** - "Oh", "Nah", "Wait"

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

### 8. Pola Temporal dan Konsistensi
- [ ] **Inkonsistensi timeline**: Tanggal/waktu yang tidak masuk akal
- [ ] **Anachronism**: Referensi teknologi/events yang tidak sesuai era
- [ ] **Tense confusion**: Campur past/present tense tanpa alasan
- [ ] **Cultural inconsistency**: Referensi budaya yang campur aduk
- [ ] **Knowledge cutoff clues**: Info terbatas sampai tanggal tertentu

### 9. Gaya Bahasa dan Tone
- [ ] **Overly diplomatic**: Selalu netral, menghindari kontroversial
- [ ] **Mechanical empathy**: Empati yang terasa dipaksakan/template
- [ ] **Hedging language**: "It's worth noting", "It's important to consider"
- [ ] **Academic jargon overuse**: Istilah teknis berlebihan tanpa perlu
- [ ] **Absence of colloquialisms**: Tidak ada bahasa gaul/slang natural

### 11. Pola Code-Switching (Campur Bahasa)
**Ciri LLM:**
- [ ] **Mixing yang terlalu perfect**: Grammar mixing yang selalu benar
- [ ] **Formal English terms**: Selalu menggunakan istilah formal/teknis
- [ ] **Consistent translation**: Selalu terjemahkan istilah yang sama
- [ ] **Avoid slang mixing**: Tidak pernah campur bahasa gaul
- [ ] **Predictable patterns**: Bahasa Inggris hanya untuk istilah teknis

**Ciri Human Natural:**
- [ ] **Random switching**: Campur bahasa tanpa pola konsisten  
- [ ] **Colloquial mixing**: "Gue tu feeling-nya gimana gitu"
- [ ] **Inconsistent translation**: Kadang terjemah, kadang tidak
- [ ] **Emotional switching**: Ganti bahasa saat emosional
- [ ] **Regional patterns**: Sesuai dengan daerah/background penulis
### 10. Struktur Pengetahuan
- [ ] **Surface-level analysis**: Analisis yang luas tapi dangkal
- [ ] **Wikipedia-style writing**: Gaya ensiklopedia yang kaku
- [ ] **Lack of personal anecdotes**: Tidak ada cerita personal spesifik
- [ ] **Generic examples**: Contoh-contoh yang klise dan umum
- [ ] **No controversial takes**: Menghindari opini yang divisif
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

**Pola Temporal:**
- [Deskripsi temuan]

**Gaya Bahasa:**
- [Deskripsi temuan]

**Code-Switching Patterns:**
- [Deskripsi temuan]

**Struktur Pengetahuan:**
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
