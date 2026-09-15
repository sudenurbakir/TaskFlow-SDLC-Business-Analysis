# İlerleme Takibi ve Raporlama
## TaskFlow

Bu bölümde, kullanıcıların kendi yaptıkları işleri ve ilerlemelerini nasıl görebileceklerini tanımladım.

### 1. Amaç
Kullanıcıların:
- Kendilerine atanan görevleri,
- Tamamladıkları işleri,
- Ne kadar ilerleme kaydettiklerini
net bir şekilde görebilmesini sağlamak.

### 2. Kullanıcı İhtiyacı
Bir kullanıcı olarak, sadece görev listesini görmek istemiyorum.  
Aynı zamanda:
- Bu ay kaç görev tamamladığımı,
- Hala devam eden kaç görevim olduğunu,
- Geciken görevlerimi
tek bakışta görmek istiyorum.

### 3. Çözüm Yaklaşımı

Sistemde her kullanıcının kendi **İlerleme Paneli (Dashboard)** bulunacak.

#### 3.1. Kişisel İlerleme Özeti
Kullanıcı giriş yaptığında şu özet bilgileri görebilecek:

| Metrik                        | Açıklama                              |
|------------------------------|---------------------------------------|
| Toplam Görev                 | Bana atanan tüm görev sayısı          |
| Tamamlanan Görev             | Başarıyla bitirdiğim görevler         |
| Devam Eden Görev             | Hala üzerinde çalıştığım görevler     |
| Geciken Görev                | Bitiş tarihi geçmiş ama bitmemiş olanlar |
| Tamamlanma Oranı             | Yüzdesel ilerleme                     |

#### 3.2. Örnek Görünüm (Tablo)

| Görev Başlığı              | Durum          | Bitiş Tarihi | İlerleme |
|---------------------------|----------------|--------------|----------|
| Müşteri sunumu hazırlığı  | Tamamlandı     | 10.09.2025   | %100     |
| Haftalık rapor            | Devam Ediyor   | 15.09.2025   | %60      |
| Toplantı notları          | Yapılacak      | 18.09.2025   | %0       |
| Sistem testi              | Gecikmiş       | 08.09.2025   | %40      |

### 4. İlgili User Story

**US-06**  
Bir kullanıcı olarak, kendi ilerleme özetimi görebilmek istiyorum ki ne kadar iş yaptığımı net anlayabileyim.  

**Kabul Kriterleri:**
- Toplam, tamamlanan, devam eden ve geciken görev sayıları görünmeli
- Tamamlanma oranı yüzde olarak gösterilmeli
- Görev listesi durum ve tarihe göre filtrelenebilmeli

### 5. İş Kuralları
- İlerleme yüzdesi, görevin durumuna göre otomatik hesaplanır:
  - Yapılacak → %0
  - Devam Ediyor → %50 (veya manuel güncellenebilir)
  - Tamamlandı → %100
- Geciken görevler kırmızı renk ile vurgulanır.
- Sadece kullanıcıya atanan görevler kişisel panelde görünür.

