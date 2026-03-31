# Analisa Sentimen Stockbit

Repositori ini berisi proyek analisis sentimen untuk ulasan aplikasi Stockbit. Tujuan proyek ini adalah mengumpulkan ulasan (scraping), melakukan pembersihan dan preprocessing data, lalu menerapkan teknik NLP untuk menentukan sentimen (positif/negatif/netral) serta mendapatkan insight dari ulasan pengguna.

Struktur utama:
- `Analisa_Sentimen_Stockbit.ipynb` — Notebook utama: eksplorasi data, preprocessing, pemodelan, dan visualisasi hasil.
- `scraping_data.ipynb` — Notebook untuk proses scraping dan penyimpanan data mentah.
- `Stockbit_ulasan_aplikasi.csv` — File dataset CSV berisi ulasan aplikasi (hasil scraping).
- `requirements.txt` — Daftar dependensi Python yang dibutuhkan.

Persyaratan
- Python 3.8+ (disarankan)
- Virtual environment (opsional tetapi direkomendasikan)

Instalasi dan cara menjalankan
1. Buat virtualenv dan aktifkan:
	```
	python -m venv .venv
	source .venv/bin/activate
	```
2. Install dependency:
	```
	pip install -r requirements.txt
	```
3. Jalankan Jupyter:
	```
	jupyter lab
	```
	atau
	```
	jupyter notebook
	```
4. Buka dan jalankan `Analisa_Sentimen_Stockbit.ipynb` untuk mengikuti alur analisis.

Catatan
- Jika dataset belum tersedia atau ingin diperbarui, jalankan `scraping_data.ipynb` untuk mengumpulkan data baru.
- Periksa `requirements.txt` jika ada paket tambahan yang perlu dipasang.

Kontributor
- zickrian

Lisensi
- Periksa file `LICENSE` jika tersedia; jika belum, hubungi pemilik repositori untuk keterangan lisensi.