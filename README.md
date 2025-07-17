Proyek ini bertujuan untuk melakukan web scraping terhadap berita dari situs CNBC Indonesia, mengambil informasi penting seperti judul berita, tanggal publikasi, dan isi berita, lalu menyimpannya ke dalam format yang dapat diolah lebih lanjut (CSV/DataFrame).

Fitur Utama : 
1. Mengambil daftar berita terbaru dari CNBC Indonesia
2. Mendapatkan detail: judul, tanggal, kategori, dan isi artikel
3. Menyimpan data hasil scraping ke dalam format CSV

Cara Menjalankan
Jalankan notebook CNBC_Scrapping.ipynb dari Jupyter atau VS Code.
Pastikan kamu telah menginstall semua dependency:

```bash
pip install requests beautifulsoup4 pandas
```
Setelah proses selesai, hasil scraping akan tersimpan dalam bentuk:
1. DataFrame (dalam notebook)
2. CSV (cnbc_news.csv atau sesuai nama output)
