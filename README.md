# ⚽ Football Matches 2024–2025 Analysis 
Capstone Project – Data Classification and Summarization Using IBM Granite

---

**Ringkasan Proyek**  
Proyek ini menganalisis data pertandingan sepak bola musim **2024–2025** dari berbagai liga besar Eropa.  
Tujuannya adalah memperoleh wawasan terkait **hasil pertandingan, performa tim, dan tren waktu** melalui **Exploratory Data Analysis (EDA)** serta **ringkasan berbasis AI** dengan IBM Granite (via Replicate API).  

Ruang lingkup analisis:  
- Analisis tingkat pertandingan (hasil, jumlah gol, margin kemenangan).  
- Analisis tingkat tim (poin, kekuatan menyerang, kekuatan bertahan).  
- Analisis tren waktu (bulanan, harian, jam pertandingan).  

---

**Dataset**  
- **Nama**: [football_matches_2024_2025.csv](https://www.kaggle.com/datasets/tarekmasryo/football-matches-20242025-top-5-leagues) 
- **Jumlah data**: 1.941 pertandingan  
- **Kolom**: informasi kompetisi, tim, gol (fulltime & halftime), hasil, poin, serta tanggal pertandingan (UTC & lokal Jakarta).  
- **Sumber**: dataset publik (non-rahasia).  

---

**Hasil Analisis (Analytical Results)**  

*Pertandingan*  
- Home wins: **832 (42.86%)**, Away wins: **646 (33.28%)**, Draws: **463 (23.85%)**  
- Rata-rata gol per pertandingan: **2.88** (Home: 1.54 | Away: 1.34)  
- Sebagian besar pertandingan berakhir dengan margin tipis (median goal difference = 0).  

*Tim*  
- **Poin**: PSG (118) unggul tipis dari Barcelona (117).  
- **Gol tercetak**: Barcelona (145) jadi tim paling produktif.  
- **Gol kebobolan paling sedikit**: SK Sturm Graz (14 kebobolan).  

*Waktu & Tren*  
- **Bulan tersibuk**: Desember 2025 (225 pertandingan), September 2024 (197).  
- **Bulan terendah**: Maret 2025 (183 pertandingan).  
- **Dominasi akhir pekan**: Sabtu (639) & Minggu (702) jadi hari terfavorit.  
- **Prime-time**: 21:00–22:00 WIB jadi slot tersibuk (298 pertandingan).  

---

**Insight & Temuan**  

*Pertandingan*  
- Keunggulan kandang nyata (**42.86%** vs tandang **33.28%**).  
- Hasil imbang cukup sering (**23.85%**), menandakan kompetisi seimbang.  
- Rata-rata gol **2.88**, dengan banyak pertandingan berakhir tipis.  

*Tim*  
- PSG unggul tipis poin (**118**) atas Barcelona (**117**).  
- Barcelona dominan dalam serangan (**145 gol**, unggul 29 dari PSG).  
- SK Sturm Graz jadi patokan pertahanan (**14 kebobolan**).  
- Liverpool & Inter Milan sama-sama mencetak **105 gol**.  
- Arsenal & Atalanta sama-sama mencetak **100 gol**, tapi perlu perbaikan lini belakang.  

*Waktu & Tren*  
- Bulan tersibuk: **Des 2025 (225 pertandingan)**; terendah **Mar 2025 (183)**.  
- Lonjakan gol tertinggi di **Juni 2025 (5.0 rata-rata)**, anomali turnamen.  
- Pertandingan dominan di akhir pekan (**702 Minggu, 639 Sabtu**).  
- Prime-time: **21:00–22:00 WIB** jadi jam pertandingan paling aktif.  

---

**Rekomendasi**  

*Pertandingan*  
- Perkuat strategi tandang → efisiensi serangan tim tamu.  
- Optimalkan set-piece → margin tipis sering jadi penentu.  
- Latihan skenario kritis → menjaga keunggulan tipis & mengejar ketertinggalan.  

*Tim*  
- PSG perlu meningkatkan pertahanan agar seimbang dengan serangan.  
- Barcelona pertahankan pola ofensif agresif.  
- Liverpool & Inter Milan butuh variasi serangan untuk unggul.  
- Arsenal & Atalanta perlu memperkuat lini belakang.  

*Waktu & Tren*  
- Jadwalkan big match di akhir pekan untuk maksimalkan penonton.  
- Revitalisasi pertandingan Senin & Kamis dengan promosi khusus.  
- Optimalkan prime-time (**21:00–22:00 WIB**) untuk laga besar.  
- Jadwalkan latihan intensif di luar jam pertandingan utama.  
- Perkuat fan engagement dengan event dan promo akhir pekan.  

---

**Dukungan AI**  
Proyek ini memanfaatkan **IBM Granite (via Replicate API + LangChain)** untuk:  
- Merangkum hasil analisis EDA (pertandingan, tim, tren).  
- Menghasilkan insight & temuan yang lebih mendalam.  
- Memberikan rekomendasi praktis bagi pelatih, analis, dan manajemen.  

Granite berperan sebagai **AI analyst assistant**, yang mengubah data kuantitatif menjadi narasi yang jelas dan mudah dipahami stakeholder non-teknis.  

---

**Link Submission**  
- **Notebook Google Colab**: *(https://colab.research.google.com/drive/1Vjm26K0g4INou2kYitZee6zyDcH0KlIa?usp=sharing)*
