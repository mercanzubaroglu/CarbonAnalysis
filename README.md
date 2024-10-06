# Karbon Emisyonları Analizi ve Tahmini

Bu proje, kişi başına düşen karbon dioksit (CO2) emisyonlarının geçmiş verilerine dayalı bir analiz ve tahmin modelini içermektedir. Python kullanılarak geliştirilmiş olan bu model, gelecekteki emisyon oranlarını tahmin eder ve hem tarihsel verileri hem de gelecekteki tahminleri görselleştirir.

**Pandeminin Etkisi (2020)**
2020 yılında tüm dünyayı etkileyen **COVID-19** pandemisi nedeniyle karbon emisyonlarında önemli bir düşüş yaşanmıştır. Salgın nedeniyle uygulanan karantina tedbirleri, azalan sanayi üretimi ve seyahat kısıtlamaları, kişi başına düşen CO2 emisyonlarını ciddi şekilde **azaltmıştır.**

Bu modeldeki tahminler, **2020 yılındaki** bu anomaliyi içermektedir ve bu durum geleceğe yönelik tahminlerde kısa vadede bir düşüşe neden olabilir. Ancak bu, pandemi sonrası dönemde ekonomilerin ve faaliyetlerin normalleşmesi ile düzelmeye başlayacak bir eğilim olarak kabul edilmelidir. Model, tarihsel verilere dayandığı için, bu tür beklenmedik olayların gelecekteki tahminlerde geçici **dalgalanmalara** neden olabileceği göz önünde bulundurulmalıdır.

**Proje Özellikleri**

+ Veri Analizi: Kişi başına düşen tarihsel CO2 emisyonları analiz edilir.
+ Tahmin Modeli: Gelecek 10 yıl için CO2 emisyon tahminleri sağlar.
+ Görselleştirme: Hem geçmiş verileri hem de tahmin sonuçlarını içeren bir grafik üretir.

**Gereksinimler**

Bu projeyi çalıştırabilmek için aşağıdaki yazılım ve kütüphanelere ihtiyaç vardır:

+ Python 3.x
+ Kütüphaneler:
+ pandas: Veri işleme ve analiz için.
+ numpy: Sayısal hesaplamalar için.
+ matplotlib: Grafik oluşturmak için.
+ statsmodels: İstatistiksel modelleme ve zaman serisi analizi için.

## Model Detayları

Tahminler, zaman serisi analizi kullanılarak yapılmıştır. Model, tarihsel CO2 emisyon verilerine dayalı olarak gelecekteki eğilimleri öngörmek için **ARIMA (AutoRegressive Integrated Moving Average)** yöntemi ile oluşturulmuştur. 

## Sonuçların Yorumlanması

Bu model, geçmiş verilere dayanarak tahmin yapmaktadır. Ancak, beklenmeyen politikalar, ekonomik değişiklikler veya doğal felaketler gibi faktörler gelecekteki CO2 emisyonlarını önemli ölçüde etkileyebilir. Bu nedenle tahminler, kısa vadede güvenilir olsa da uzun vadeli stratejik kararlar için dikkatle kullanılmalıdır.

