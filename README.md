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







### Kütüphane Yönetim Sistemi
### Veri Yapısı ve Dosyalar:

### Kitaplar, üyeler, kullanıcılar ve ödünç kayıtları JSON dosyalarında saklanıyor.

### Her biri için ayrı sınıflar (Kitap, Uye, Kullanici, Odunc) var. Bu sınıflar veriyi nesne olarak tutup, JSON’a kolayca dönüştürülüp tekrar ### yüklenmesini sağlıyor.

### Veri Yükleme ve Kaydetme:

### JSON dosyalarından veriler uygulama açılırken yükleniyor.

### Veriler değiştiğinde yine JSON dosyalarına kaydediliyor.

### Kullanıcı Yönetimi:

### Sistemde admin ve normal kullanıcılar var.

### Eğer hiç kullanıcı yoksa otomatik olarak admin kullanıcısı oluşturuluyor.

### Tkinter Arayüzü:

### Giriş ekranı var, kullanıcı adı ve şifre ile sisteme giriş yapılabiliyor.

### Başarılı giriş sonrası 3 ana sekme açılıyor:

### Kitap Yönetimi: Kitap ekleme, listeleme ve kitapların rafta mı ödünçte mi olduğunu gösterme.

### Üye Yönetimi: Üye ekleme ve listeleme.

### Ödünç İşlemleri: Üyenin kitap ödünç alması ve iade etmesi.

### Ödünç Alma / İade Süreci:

### Kitap ödünç verildiğinde kitap durumu “Ödünçte” olarak işaretleniyor ve 14 gün sonra iade tarihi belirleniyor.

### Kitap iade edilince kitap tekrar “Rafta” olarak işaretleniyor ve ödünç kaydı siliniyor.

### Arayüz Özellikleri:

### Kitaplar, üyeler ve ödünç kayıtları için tablo görünümü (Treeview) ile listeleme yapılabiliyor.

### Kullanıcıya hatalar veya başarı durumları mesaj kutuları ile bildiriliyor.

### Kısaca, kullanıcı yönetimi, kitap ve üye ekleme, ödünç alma/iade işlemleri yapabilen ve tüm verileri JSON dosyalarına kaydeden bir masaüstü kütüphane sistemi.