# prediksi-resiko-late-delivery-dataco

Repository ini mengandung notebook Python yang melakukan prediksi resiko late delivery dari dataset DataCo Supply Chain. Data pertama dilakukan pre-processing terlebih dahulu untuk mengekstrak fitur-fitur yang diperlukan, sebelum dilakukan exploratory data analysis untuk melihat konten data lebih lanjut dan feature engineering untuk mengoptimasi performa model ML. Metrik evaluasi menggunakan validation accuracy untuk membandingkan berbagai model ML dan log loss untuk mengukur error dari model dengan performa terbaik.

Model extra trees classifier memiliki skor validation accuracy paling tinggi, yakni sebesar 97,8894. Model extra trees classifier kemudian dikalkulasikan skor log loss oleh kakas Sklearn dan diperoleh skor log loss 0,0821.

Repository ini dilombakan di Analisis Big Data Fesmaro 2025.

Kelompok:
- M Farrel Danendra Rachim (ITB)
- Moh Aghna Maysan Abyan (ITB)
- Satria Octavianus Nababan (ITB)

Sumber data: https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis
