🧪 Uygulanan Veri Doldurma Yöntemleri
Bu projede eksik verileri doldurmak için hem klasik istatistiksel yaklaşımlar hem de makine öğrenmesi temelli algoritmalar kullanılmıştır. Kullanılan yöntemler:

1. 🔢 Temel İstatistiksel Yöntemler
Ortalama (Mean) ile Doldurma: Sayısal sütunlarda eksik değerler o sütunun ortalama değeriyle doldurulmuştur.

Medyan ile Doldurma: Aykırı değerlerin etkisini azaltmak amacıyla bazı durumlarda medyan tercih edilmiştir.

Mod (En Sık Görülen Değer) ile Doldurma: Kategorik verilere uygulanmıştır.

2. 🤖 KNN Imputer (K-En Yakın Komşu ile Doldurma)
Bu yöntem, eksik değerleri en yakın komşu veriler üzerinden tahmin ederek doldurur.

Özellikle eksik verinin komşuluk ilişkilerine göre tahmin edilebilir olduğu durumlarda kullanılır.

Sayısal ve kategorik karma veri setlerinde etkili sonuç verir.

3. 📈 Linear Regression ile Doldurma (Regresyon Tabanlı Tahmin)

Eksik olan sütun, bağımsız değişkenler kullanılarak regresyon modeliyle tahmin edilir.

Özellikle eksik veri ile diğer sütunlar arasında güçlü korelasyon varsa yüksek doğruluk sağlar.

Model önce eksiksiz satırlarla eğitilir, sonra eksik olanlar için tahmin yapılır.

📌 Not:
Her yöntemin uygulanabilirliği, veri setinin türüne ve eksiklik yapısına göre değişmektedir. Bu projede her yöntem uygulanmış ve sonuçları görselleştirilerek karşılaştırılmıştır.

👨‍💻 Geliştirici:
Harun Gökce
📬 GitHub: Harungokc
