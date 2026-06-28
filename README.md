#Proje Ekibi Bilgileri

Mahmud KERİM 1306230004

Taha SEYMEN  1306240024


Projeyi Çalıştırma Talimatları

 Projeyi Jupyter Lab ortamında hatasız bir şekilde çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

 Çalışma Ortamını Hazırlayın: Ham veri setini (.csv) ve projenin Jupyter Notebook (.ipynb) dosyasını aynı klasörde konumlandırdığınızdan emin olun.

 Projeyi Başlatın: Proje dosyasını Jupyter Lab üzerinden açın.

 Kütüphaneleri ve Kodları Çalıştırın: Projenin ihtiyaç duyduğu bağımlılıklar (pandas, seaborn vb.) dosyanın ilk hücrelerine entegre edilmiştir. Kodların doğru mantıksal sırayla çalışması, kütüphanelerin kurulması ve grafiklerin çizilmesi için üst menüden Run sekmesine tıklayıp Run All Cells seçeneğini seçmeniz yeterlidir.


Kullanılan Kütüphaneler

 Projenin geliştirilme sürecinde veri manipülasyonu, görselleştirme ve yapay zeka entegrasyonu için aşağıdaki Python kütüphanelerinden faydalanılmıştır:

pandas: Veri setinin yüklenmesi, La Liga'ya özel filtrelenmesi, eksik verilerin temizlenmesi ve yeni özelliklerin (Feature Engineering) üretilmesi için.

matplotlib \& seaborn: Takım istatistiklerini ve değişkenler arası ilişkileri anlamlandırmayı sağlayan Dağılım Grafiği (Scatter), Çubuk Grafiği (Bar), Histogram ve Korelasyon Isı Haritası (Heatmap) çizimleri için.

scikit-learn: Takımların attığı ve yediği gol sayılarını kullanarak sezon sonu toplayacakları puanı tahmin eden Çoklu Doğrusal Regresyon (Multiple Linear Regression) modelinin kurulması ve test edilmesi için.


Veri Kaynağının Adı

 Bu projede kullanılan Avrupa'nın 5 büyük ligine ait ham futbol veri seti Kaggle platformundan temin edilmiştir (Kaynak: https://www.kaggle.com/code/ukaszkwestarz/inside-top-5-football-leagues/input).


Veri Kaynağının Lisansı

 Veri seti, platformun standart açık erişim (Open Access / Public Domain) koşullarına tabidir. İşlenmiş ve La Liga'ya (2010-2019) özel filtrelenmiş alt veri seti (laliga\_temiz\_veri.csv) yalnızca akademik analiz ve eğitim projesi gereksinimleri amacıyla oluşturulmuştur.
