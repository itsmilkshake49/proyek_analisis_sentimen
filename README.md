# proyek_analisis_sentimen

1. Upload Proyek
Gunakan Google Colab dan upload semua file proyek ke Google Drive.

2. Install Dependensi
python

!pip install -r requirements.txt

3. Jalankan Notebook
  a.) Scraping PUBG Review.ipynb : Mengambil ulasan aplikasi PUBG dari Google Play menggunakan google-play-scraper dan menyimpannya ke CSV.

  b.) Pemodelan.ipynb : Preprocessing teks (cleansing, stopwords, stemming), Label encoding sentimen, Training model (SVM, LSTM, atau GRU), Menyimpan model (.pkl atau .h5)
  
  c.) Inference.ipynb : Melakukan prediksi sentimen dari input teks baru menggunakan model yang sudah dilatih.
