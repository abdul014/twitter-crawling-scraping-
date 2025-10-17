<h1 align="center">🐦 Twitter Crawling & Scraping</h1>

<p align="center">
  <i>Eksperimen akuisisi data digital melalui web scraping dan API Twitter menggunakan Python.</i><br>
  <b>By Abd Rahman | EraNusaData | Magister Statistika & Sains Data, IPB University</b>
</p>

---

## 📚 Daftar Isi
- [📘 Deskripsi Proyek](#-deskripsi-proyek)
- [🧩 Struktur Dataset](#-struktur-dataset)
- [⚙️ Teknologi & Tools](#️-teknologi--tools)
- [🔍 Materi Pembahasan](#-materi-pembahasan)
  - [1️⃣ Akuisisi Data Teks](#1️⃣-akuisisi-data-teks)
  - [2️⃣ Crawling vs Scraping](#2️⃣-crawling-vs-scraping)
  - [3️⃣ Web Scraping Ethics](#3️⃣-web-scraping-ethics)
  - [4️⃣ Twitter Data Crawling](#4️⃣-twitter-data-crawling)
  - [5️⃣ Query Operator Twitter](#5️⃣-query-operator-twitter)
  - [6️⃣ Streaming Twitter Data](#6️⃣-streaming-twitter-data)
- [🚀 Jalankan Proyek](#-jalankan-proyek)
- [✍️ Disusun Oleh](#-disusun-oleh)

---

## 📘 Deskripsi Proyek
Proyek ini membahas proses **pengumpulan dan akuisisi data digital**, khususnya data teks dari **platform Twitter**, melalui dua pendekatan utama:

- **Web Scraping** menggunakan pustaka Python untuk mengekstraksi data dari halaman web.
- **Crawling API Twitter** menggunakan `Tweepy` untuk mengakses data real-time dari akun dan topik tertentu.

Dataset yang dihasilkan digunakan sebagai dasar analisis NLP dan eksplorasi text mining.

<p align="center">
  <img src="https://miro.medium.com/max/1400/1*b4GiiiIgxhfd3pUd86ZUuw.png" width="600">
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

<p align="center">
  <img src="https://raw.githubusercontent.com/abdul014/twitter-crawling-scraping-/main/images/data-acquisition.png" width="600">
</p>

---

### 2️⃣ Crawling vs Scraping
| Web Crawling | Web Scraping |
|---------------|--------------|
| Mengumpulkan halaman web untuk diindeks | Mengekstraksi data spesifik dari halaman |
| Umumnya digunakan oleh mesin pencari | Digunakan oleh analis & peneliti data |
| Bersifat luas dan legal (robots.txt) | Rentan isu legal jika tanpa izin |

<p align="center">
  <img src="https://raw.githubusercontent.com/abdul014/twitter-crawling-scraping-/main/images/crawling-vs-scraping.png" width="600">
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
_From Komunitas EraNusaData_  
Magister Statistika dan Sains Data, IPB University  

📚 [GitHub](https://github.com/abdul014) | [LinkedIn](https://linkedin.com/in/abd-rahman-ysf)
