Judul Project:
Predictive Analysis of Operational Performance and Customer Satisfaction in a Quick Service Restaurant

Deskripsi:
Quick Service Restaurant (QSR) membutuhkan pemahaman yang lebih baik mengenai faktor operasional apa yang paling memengaruhi kepuasan pelanggan, serta bagaimana perubahan operasional dapat memengaruhi hasil bisnis secara keseluruhan.
Simulasi menunjukkan bahwa peningkatan kualitas produk dan efisiensi staf memberikan dampak kepuasan yang lebih besar dibanding sekadar mempercepat proses pelayanan.

Tools:
1. PostgreSQL: data storage, cleaning, and modeling
2. Python: NLP-based sentiment analysis. Pandas, SQLAlchemy, NLTK (stopwords)
3. Power BI: data modeling, DAX measures, and dashboard visualization

Insight:
1. Item rating dan staff efficiency adalah faktor paling berpengaruh terhadap customer satisfaction 
2. Wait time berpengaruh negatif, namun dampaknya lebih kecil dibanding kualitas layanan dan produk
3. Model prediksi memiliki akurasi tinggi dengan error rata-rata rendah

Dataset:
https://www.kaggle.com/datasets/john8909/qsr-operational-dataset

Analytical Approach:
- Exploratory Data Analysis untuk memahami pola waktu, menu, staf, dan antrian
- Feature engineering berbasis operasional
- Predictive modeling menggunakan regresi linear
- Model validation & error analysis
- What-if scenario simulation untuk pengambilan keputusan

Selanjutnya PowerBI import data tersebut untuk dibuat dashboard dengan struktur:
1. Executive Overview
2. Actual vs Predicted Performance
3. Key Operational Driver
4. What-If Scenario Simulation
5. Operational Insight