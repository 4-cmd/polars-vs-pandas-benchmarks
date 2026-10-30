

| Özellik / Kriter | Polars DataFrame | Pandas DataFrame |
| --- | --- | --- |
| **Bellek Mimarisi** | Apache Arrow standardını kullanır, sütun bazlı (columnar) sıfır kopya (`zero-copy`) prensibiyle çalışır. | Geleneksel NumPy dizileri ve blok yöneticilerine dayanır; büyük veri setlerinde yüksek bellek tüketebilir. |
| **Paralel İşleme** | Rust altyapısı sayesinde çok çekirdekli (`multi-threaded`) ve yerel (`native`) paralel işlem yeteneğine sahiptir. | Çekirdek operasyonlarının büyük bölümünde tek iş parçacıklı (`single-threaded`) çalışır. |
| **Değerlendirme Stratejisi** | Sorgu optimizasyonu sağlayan tembel değerlendirme (`lazy evaluation`) mekanizmasını destekler. | Komutları anında işleyen dinamik değerlendirme (`eager evaluation`) yaklaşımını kullanır. |
| **API Tasarımı** | İfade tabanlı (`expression-based`) ve yöntem zincirlemeye (`method chaining`) dayalı modern bir yapı sunar. | İndeks tabanlı erişimler, satır/sütun etiketleri ve klasik veri çerçevesi manipülasyon sözdizimi barındırır. |
| **Ana Kullanım Alanları** | Büyük veri setleri, yüksek performanslı ETL süreçleri, RAG boru hatları ve bellek optimizasyonunun kritik olduğu modern projeler. | Keşifsel veri analizi (EDA), makine öğrenmesi veri hazırlığı, küçük/orta ölçekli veri setleri ve geniş ekosistem desteği gerektiren projeler. |
