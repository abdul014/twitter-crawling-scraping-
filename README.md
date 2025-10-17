<h2 align="center">📑 <b>Daftar Isi</b></h2>

<p align="center">
  <a href="#-deskripsi-proyek">📘 Deskripsi Proyek</a> •
  <a href="#-struktur-dataset">🧩 Struktur Dataset</a> •
  <a href="#️-teknologi--tools">⚙️ Teknologi & Tools</a> •
  <a href="#-materi-pembahasan">🔍 Materi Pembahasan</a> •
  <a href="#-jalankan-proyek">🚀 Jalankan Proyek</a> •
  <a href="#-disusun-oleh">✍️ Disusun Oleh</a>
</p>

---

### 🔍 Materi Pembahasan
<div align="center">

| 🔢 No | 📖 Topik Pembahasan | 🔗 Link |
|:--:|:--|:--|
| 1️⃣ | **Akuisisi Data Teks** | [Lihat](#1️⃣-akuisisi-data-teks) |
| 2️⃣ | **Crawling vs Scraping** | [Lihat](#2️⃣-crawling-vs-scraping) |
| 3️⃣ | **Web Scraping Ethics** | [Lihat](#3️⃣-web-scraping-ethics) |
| 4️⃣ | **Twitter Data Crawling** | [Lihat](#4️⃣-twitter-data-crawling) |
| 5️⃣ | **Query Operator Twitter** | [Lihat](#5️⃣-query-operator-twitter) |
| 6️⃣ | **Streaming Twitter Data** | [Lihat](#6️⃣-streaming-twitter-data) |

</div>

---

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tweepy-API_Twitter-lightblue?logo=twitter&logoColor=white"/>
  <img src="https://img.shields.io/badge/BeautifulSoup-WebScraping-green?logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-DataFrame-yellow?logo=pandas&logoColor=white"/>
</p>


---

## 📘 Deskripsi Proyek
Proyek ini membahas proses **pengumpulan dan akuisisi data digital**, khususnya data teks dari **platform Twitter**, melalui dua pendekatan utama:

- **Web Scraping** menggunakan pustaka Python untuk mengekstraksi data dari halaman web.
- **Crawling API Twitter** menggunakan `Tweepy` untuk mengakses data real-time dari akun dan topik tertentu.

Dataset yang dihasilkan digunakan sebagai dasar analisis NLP dan eksplorasi text mining.

<p align="center">
  <img src="https://buffer.com/resources/content/images/resources/wp-content/uploads/2015/11/Twitter-search-operators.png" width="600">
</p>

---

## 🧩 Struktur Dataset
Berikut beberapa dataset yang digunakan dan dihasilkan:

| Nama File | Deskripsi |
|------------|------------|
| `data_news.csv` | Contoh data hasil scraping dari situs berita |
| `data_scraperapi.csv` | Data hasil scraping menggunakan API Scraper |
| `data_shopee.csv` | Dataset dari platform e-commerce (Shopee) |
| `data.json` | Contoh hasil crawling dari Twitter API |
| `Pengumpulan_Data_Digital_Studi_Kasus_Twitter.ipynb` | Notebook utama berisi kode eksperimen dan visualisasi |

---

## ⚙️ Teknologi & Tools
Proyek ini dibangun menggunakan teknologi berikut:

- 🐍 **Python 3.10+**
- 🧠 **Tweepy** untuk akses API Twitter  
- 🕸 **BeautifulSoup & Requests** untuk scraping  
- 📊 **Pandas, Matplotlib** untuk analisis & visualisasi  
- 💾 **Jupyter Notebook / Google Colab** untuk eksperimen  

---

## 🔍 Materi Pembahasan

### 1️⃣ Akuisisi Data Teks
Akuisisi data teks merupakan proses pengumpulan informasi berbasis teks dari berbagai sumber:
- Data primer: survei, eksperimen, crawling, scraping  
- Data sekunder: sumber pihak ketiga  

---

### 2️⃣ Crawling vs Scraping
| Web Crawling | Web Scraping |
|---------------|--------------|
| Mengumpulkan halaman web untuk diindeks | Mengekstraksi data spesifik dari halaman |
| Umumnya digunakan oleh mesin pencari | Digunakan oleh analis & peneliti data |
| Bersifat luas dan legal (robots.txt) | Rentan isu legal jika tanpa izin |

<p align="center">
  <img src="https://i.pinimg.com/originals/68/3e/d4/683ed4ad7a71f4e20789b7d1b7d69ba0.jpg" width="600">
</p>

---

### 3️⃣ Web Scraping Ethics
> Scraping tanpa izin bisa menyebabkan pelanggaran hukum dan etika.
- Hormati file `robots.txt`  
- Gunakan API resmi bila memungkinkan  
- Pelajari **Terms of Service (ToS)** dari sumber data  

📎 [More details at Tau Data](https://tau-data.id/scraping)

---

### 4️⃣ Twitter Data Crawling
Langkah umum untuk mengambil data Twitter:

1. Login ke akun Twitter  
2. Registrasi di [Twitter Developer](https://developer.twitter.com/en/portal/projects-and-apps)  
3. Buat App baru dan dapatkan **API Key & Token**  
4. Gunakan library `tweepy`  
5. Lakukan query berdasarkan topik atau hashtag  

---

### 5️⃣ Query Operator Twitter
Beberapa contoh query operator Twitter yang digunakan:

| Operator | Fungsi |
|-----------|--------|
| `"happy hour"` | Mencari tweet dengan frasa tepat |
| `love OR hate` | Mencari tweet berisi “love” atau “hate” |
| `beer -root` | Mencari “beer” tanpa kata “root” |
| `#hashtag` | Berdasarkan hashtag |
| `from:user` | Dari akun tertentu |

📘 [Panduan Resmi Query Twitter](https://developer.twitter.com/en/docs/tweets/search/guides/standard-operators.html)

---

### 6️⃣ Streaming Twitter Data
Tipe pemrosesan data:

| Real-Time Systems | Batch Processing | Stream Processing |
|--------------------|------------------|-------------------|
| Reaksi cepat (ms) | Volume besar sekaligus | Proses lintas-perangkat real-time |
| Kompleks diimplementasikan | Butuh waktu dan resource besar | Kecepatan tinggi, sinkron dengan input |

📖 Baca lebih lanjut:  
[Batch vs Stream Processing (BMC Blog)](https://www.bmc.com/blogs/batch-processing-stream-processing-real-time/)

---

## 🚀 Jalankan Proyek
Untuk mencoba eksperimen ini secara langsung:

📂 **Google Colab Notebook:**
- [Buka Notebook 1](https://drive.google.com/file/d/1zcquGKJVsw7tlnUdNkmQNvOsr5rm9WV2/view?usp=sharing)  
- [Buka Notebook 2](https://drive.google.com/file/d/1RnLhe9ALKizbFYG89YmS0fKpAMj8DbDn/view?usp=sharing)

---

## ✍️ Disusun Oleh
**Abd Rahman**  
Magister Statistika dan Sains Data, IPB University  

📚 [GitHub](https://github.com/abdul014) | [LinkedIn](https://linkedin.com/in/abd-rahman-ysf)
