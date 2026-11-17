# 📚 Sistem Rekomendasi Buku (Comics & Graphic Novels)

Aplikasi web **Sistem Rekomendasi Buku** berbasis **Content-Based Filtering** menggunakan **TF-IDF** dan **Cosine Similarity**, dibangun dengan **Python** dan **Streamlit**.

## ✨ Fitur Utama
- Pencarian judul komik/buku dari dataset Goodreads (*Top 5.000 Comics & Graphic Novels*).
- Menampilkan detail buku (cover, rating, jumlah rating, genre/tag, dan sinopsis).
- Menghasilkan rekomendasi buku paling mirip lengkap dengan persentase kemiripan (*Cosine Similarity*).
- Tautan langsung ke halaman detail resmi di Goodreads.

## 🛠️ Teknologi
- Python
- Streamlit
- Pandas & OpenPyXL
- Scikit-Learn (`TfidfVectorizer` & `cosine_similarity`)

## 🚀 Cara Menjalankan
```bash
pip install streamlit pandas openpyxl scikit-learn
python -m streamlit run app.py
```
