# Prediksi Harga Saham Stellar (XLM) menggunakan LSTM dan GRU
Proyek ini bertujuan untuk memprediksi harga saham Stellar (XLM) menggunakan model Long Short-Term Memory (LSTM) dan Gated Recurrent Unit (GRU). 

# Cara Penggunaan
## 1. Impor Pustaka dan Unduh Data
Kode ini menggunakan pustaka yfinance untuk mengunduh data harga saham Stellar (XLM) dan pustaka lain untuk pemrosesan dan visualisasi data.

## 2. Normalisasi Data
Data harga penutupan dinormalisasi menggunakan MinMaxScaler dari pustaka scikit-learn untuk memastikan nilai berada dalam rentang [0, 1].

## 3. Visualisasi Data
Menggunakan plotly, harga pembukaan, penutupan, rendah, dan tinggi dari saham divisualisasikan dalam bentuk grafik.

## 4. Pemrosesan dan Persiapan Data
Data diproses dan disiapkan untuk model LSTM dan GRU dengan menggunakan fungsi prepare_data yang mengubah data menjadi bentuk yang dapat digunakan oleh model.

## 5. Tuning Hyperparameter
Menggunakan pustaka hyperopt untuk menemukan hyperparameter terbaik untuk model LSTM dan GRU dengan menggunakan metode Bayesian optimization.

## 6. Pembangunan dan Pelatihan Model
Dua model dibangun, satu untuk LSTM dan satu lagi untuk GRU. Masing-masing model dilatih menggunakan hyperparameter terbaik yang ditemukan dari proses tuning.

## 7. Evaluasi Model
Kinerja model dievaluasi menggunakan metrik MSE, RMSE, dan MAPE. Hasil prediksi juga divisualisasikan dan dibandingkan dengan data asli.

## 8. Menyimpan Model
Model LSTM dan GRU yang telah dilatih disimpan dalam file final_model_lstm.h5 dan final_model_gru.h5, yang kemudian dapat diunduh.

# Struktur Proyek
- LSTM_GRU_FINAL.ipynb: Notebook Jupyter berisi seluruh kode.
- final_model_lstm.h5: Model LSTM yang telah dilatih.
- final_model_gru.h5: Model GRU yang telah dilatih.
- 
# Cara Menjalankan
- Unduh atau clone repositori ini.
- Pastikan semua pustaka yang diperlukan telah terinstal.
- Buka dan jalankan LSTM_GRU_FINAL.ipynb menggunakan Google Colab atau Jupyter Notebook.
