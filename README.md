# Capstone-Project_Ilfiah-Nur-Lailiyah
Capstone Project – Representasi Perempuan di Parlemen dan Kepala Daerah Perempuan di Indonesia

# Representasi Perempuan di Parlemen dan Kepala Daerah Perempuan di Indonesia

## 📖 Project Overview
Keterwakilan perempuan dalam politik merupakan indikator penting kualitas demokrasi dan kesetaraan gender yang sejalan dengan Sustainable Development Goals (SDGs) poin 5 yaitu Gender Equality. Undang-Undang Nomor 2 Tahun 2008 menetapkan bahwa keterwakilan perempuan sebesar 30% harus disertakan dalam pendirian dan pembentukan partai politik, sedangkan Undang-Undang Nomor 10 Tahun 2008 mewajibkan sekurang-kurangnya 30% perempuan dalam kepengurusan partai politik tingkat pusat agar dapat menjadi peserta pemilu. Berangkat dari ketentuan tersebut, proyek ini bertujuan untuk melihat apakah provinsi di Indonesia telah memenuhi batas minimal keterwakilan perempuan baik di tingkat legislatif (DPRD provinsi) maupun eksekutif (gubernur/wakil gubernur). Tujuan akhir proyek ini adalah memberikan insight berbasis data untuk mendukung evaluasi dan rekomendasi kebijakan. Analisis dilakukan dengan Python melalui visualisasi berupa grafik, kemudian diperkuat dengan narasi analitis berbantuan AI untuk menjelaskan tren dan memberikan rekomendasi kebijakan.

---

## 📊 Dataset
- **Sumber data Representasi Perempuan di Parlemen**: Data representasi perempuan di parlemen diperoleh dari situs web Badan Pusat Statistik (BPS) yang diukur dengan satuan persen 
- **Data kepala daerah perempuan**: Data kepala daerah perempuan diperoleh dari situs web Kemendagri, KPU, dan publikasi resmi Pemerintah Daerah. Data ini dibuat dummy (1 = ada gubernur/wakil gubernur perempuan, 0 = tidak ada gubernur/wakil gubernur perempuan)
- **Raw dataset** tersedia di repo ini: [DATA.xlsx](./DATA.xlsx)

---

## 🔍 Insight & Findings
Berdasarkan analisis visualisasi data:

1. **Grafik garis provinsi terpilih (3 tertinggi & 3 terendah) + rata-rata nasional**  
   → Terdapat kesenjangan besar antar-provinsi. Sebagian provinsi konsisten rendah, sementara sedikit provinsi memiliki representasi relatif tinggi.  

2. **Grafik batang jumlah provinsi memenuhi 30% vs belum**  
   → Mayoritas provinsi **belum memenuhi kuota 30%**. Hanya sedikit yang konsisten melewati ambang batas.  

3. **Grafik garis rata-rata nasional representasi perempuan di parlemen**  
   → Rata-rata nasional masih berada di bawah 30%, menunjukkan bahwa representasi perempuan secara keseluruhan masih rendah.  

4. **Grafik garis kepala daerah perempuan**  
   → Persentase kepala daerah perempuan (gabungan gubernur & wakil gubernur) masih sangat rendah, rata-rata di bawah 15% dari total provinsi.  

---

## 🤖 AI Support Explanation
Untuk analisis naratif, digunakan **IBM Granite via Replicate API**:  
- Data divisualisasikan di Google Colab dengan Python.  
- Akan diperoleh hasil (misalnya tren nasional & persentase kepala daerah perempuan)
  

---
