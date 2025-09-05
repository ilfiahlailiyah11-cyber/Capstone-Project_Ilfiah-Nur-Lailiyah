# Capstone-Project_Ilfiah-Nur-Lailiyah
Capstone Project – Representasi Perempuan di Parlemen dan Kepala Daerah Perempuan di Indonesia

# Representasi Perempuan di Parlemen dan Kepala Daerah Perempuan di Indonesia

## 📖 Project Overview
Keterwakilan perempuan dalam politik merupakan isu penting dalam demokrasi dan kesetaraan gender. Analisis ini dilakukan untuk melihat sejauh mana perempuan terwakili dalam parlemen provinsi (DPRD) dan dalam jabatan kepala daerah (gubernur/wakil gubernur).  

Tujuan project ini:
- Menggambarkan tren keterwakilan perempuan di parlemen provinsi Indonesia.
- Mengukur keterwakilan kepala daerah perempuan per tahun.
- Membandingkan pencapaian provinsi terhadap ambang batas kuota 30% keterwakilan perempuan.
- Memberikan insight berbasis data yang dapat mendukung evaluasi kebijakan afirmasi politik bagi perempuan.

---

## 📊 Dataset
- **Sumber data DPRD**: Badan Pusat Statistik (BPS), diolah dalam bentuk persentase keterwakilan perempuan per provinsi per tahun.
- **Data kepala daerah perempuan**: Dibuat dummy (1 = ada gubernur/wakil gubernur perempuan, 0 = tidak ada), lalu dihitung persentasenya per tahun.
- **Raw dataset** tersedia di repo ini: [DATA.xlsx](./DATA.xlsx)

---

## 🔍 Insight & Findings
Berdasarkan analisis visualisasi data:

1. **Grafik garis provinsi terpilih (3 tertinggi & 3 terendah) + rata-rata nasional**  
   → Terdapat kesenjangan besar antar-provinsi. Sebagian provinsi konsisten rendah, sementara sedikit provinsi memiliki representasi relatif tinggi.  

2. **Grafik batang jumlah provinsi memenuhi 30% vs belum**  
   → Mayoritas provinsi **belum memenuhi kuota 30%**. Hanya sedikit yang konsisten melewati ambang batas.  

3. **Grafik garis rata-rata nasional DPRD**  
   → Rata-rata nasional masih berada di bawah 30%, menunjukkan bahwa representasi perempuan secara keseluruhan masih rendah.  

4. **Grafik garis kepala daerah perempuan**  
   → Persentase kepala daerah perempuan (gabungan gubernur & wakil gubernur) masih sangat rendah, rata-rata di bawah 15% dari total provinsi.  

5. **Tabel provinsi yang memenuhi 30% tiap tahun**  
   → Memberikan daftar provinsi yang berhasil mencapai target kuota 30%, namun jumlahnya fluktuatif.  

---

## 🤖 AI Support Explanation
Untuk analisis naratif, digunakan **IBM Granite via Replicate API**:  
- Data divisualisasikan di Google Colab dengan Python (pandas, matplotlib, seaborn).  
- Ringkasan hasil (misalnya tren nasional & persentase kepala daerah perempuan) dikirim ke IBM Granite.  
- Granite menghasilkan insight naratif: menjelaskan pola naik/turun, memberikan interpretasi tren, serta menyarankan rekomendasi kebijakan.  

Dengan bantuan AI, hasil analisis lebih komprehensif: bukan hanya angka & grafik, tetapi juga penjelasan deskriptif mengenai makna data.  

---

## 📂 Struktur Repository
