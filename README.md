# OBJECT-ORIENTED-PROGRAMMING

### Araç Kiralama Sistemi

### Temel bileşenleri:
### Veri modeli;
### Arac sınıfı: Araç bilgilerini (ID, model, günlük ücret, kiralama durumu) tutar.

### Musteri sınıfı: Müşteri bilgilerini (ID, ad) tutar.

### Kiralama sınıfı: Kiralama işlemlerini yönetir; kiralama yapma ve iptal etme fonksiyonları var.

### Veri yönetimi:
### Veriler JSON dosyasına (veri.json) kaydedilip oradan yükleniyor.

### Araçlar, müşteriler ve kiralamalar ayrı ayrı veri yapılarında tutuluyor.

### Arayüz (Tkinter):
### Üç ana sekme var;

### Araçlar: Araç ekleyebilir ve mevcut araçları görebilirsin.

### Müşteriler: Müşteri ekleme ve listeleme.

### Kiralama: Müşteri ve araç ID’si ile kiralama yapabilir veya kiralamayı iptal edebilirsin. Kiralanan araçların listesi gösteriliyor.

### İşlevsellik:
### Kiralama yaparken tarihler kontrol ediliyor, araç kiradaysa hata veriliyor.

### Kiralama iptal edilince araç durumu güncelleniyor.

### Kiralama ücreti, kiralama gün sayısı * araç günlük ücreti olarak hesaplanıp gösteriliyor.

### Tüm değişiklikler JSON dosyasına kaydediliyor.

### Görsellik:
### Modern ve temiz bir tema kullanılmış.

### Ağaç görünümleri (Treeview) ile araç, müşteri ve kiralama listeleri gösteriliyor.

### Özetle, bu uygulama araç kiralama işlemlerini takip etmek, araç ve müşteri eklemek, kiralama işlemi yapmak ve iptal etmek için bir arayüz sunuyor ve verileri kalıcı şekilde JSON dosyasında saklıyor.