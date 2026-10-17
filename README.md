# Food Delivery Time Prediction

Prediksi durasi pengantaran makanan (`Delivery_Duration_Minutes`) menggunakan
Machine Learning, dengan perbandingan model LARS, Linear Regression, dan
Gradient Boosting Regressor.

## Dataset
`Order_delivery.csv` berisi 1.000 data order pengantaran makanan, dengan fitur
seperti kota, metode pembayaran, jarak pengantaran, tingkat lalu lintas, dan
ketersediaan driver.

## Tahapan
1. Pengecekan missing value, duplikat, dan outlier (metode IQR)
2. Standardisasi dan encoding fitur kategorikal
3. Analisis korelasi terhadap target
4. Split data 80:20 (`random_state=1`)
5. Pelatihan dan evaluasi model (MAE, MSE, R²)
6. Latihan scaling (MinMax/Standard) dan K-Fold Cross Validation

## Isi Repo
- `FoodDelivery.ipynb`: notebook utama
- `Order_delivery.csv`: dataset
- `LAPRAK_LAB_ML_MALIKI_SEPTIANO.docx`: laporan praktikum
