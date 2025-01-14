Öğrenci ve Ders Yönetim Sistemi
Bu proje, öğrenci, öğretim görevlisi ve ders yönetimini sağlayan bir konsol uygulamasıdır. Projede veriler JSON formatında yerel dosyalarda saklanır ve bu dosyalardan okunarak işlemler gerçekleştirilir.

Özellikler

Öğrenci İşlemleri
Öğrenci ekleme
Öğrenci bilgilerini JSON dosyasına kaydetme
Öğrenci listesini görüntüleme
Öğretim Görevlisi İşlemleri
Öğretim görevlisi ekleme
Öğretim görevlisi bilgilerini JSON dosyasına kaydetme
Öğretim görevlisi listesini görüntüleme
Ders İşlemleri
Ders ekleme
Ders bilgilerini JSON dosyasına kaydetme
Bir dersin adını, kredisini, öğretim görevlisini ve kayıtlı öğrencileri listeleme
Kullanılan Teknolojiler

Programlama Dili: C#
Veri Saklama: JSON Formatı
.NET Core: Konsol tabanlı uygulama geliştirme
Sınıflar ve Yapılar

Temel Sınıf (Kisi):
Ortak özellik ve davranışları tanımlayan bir temel sınıf.
Ad, Soyad gibi ortak özelliklere sahiptir.
Türetilmiş sınıflar: Ogrenci, OgretimGorevlisi.
Interface (IKisi):
Login gibi davranışların zorunlu olarak tanımlanmasını sağlar.
Ogrenci ve OgretimGorevlisi sınıflarında uygulanmıştır.
Ders Yönetimi (Ders):
Ders adı, kredisi, öğretim görevlisi bilgileri.
Öğrencilerin bir derse kaydolması için gerekli yapı.
Projenin Çalıştırılması

Proje dosyalarını bilgisayarınıza indirin.
Uygulamayı Visual Studio veya uyumlu bir IDE'de açın.
Program.cs dosyasını çalıştırarak uygulamayı başlatın.
Konsoldaki talimatları izleyerek öğrenci, öğretim görevlisi ve ders ekleyin ya da listeleme işlemleri yapın.
JSON Dosyaları

Öğrenci bilgileri: ogrenciler.json
Öğretim görevlisi bilgileri: ogretimGorevlileri.json
Ders bilgileri: dersler.json
Örnek Kullanım

Öğrenci eklemek için konsoldan ilgili menü seçilir ve öğrenci bilgileri girilir.
Girdiğiniz bilgiler otomatik olarak ogrenciler.json dosyasına kaydedilir.
Listeleme işlemi seçilerek dosyadaki tüm bilgiler görüntülenebilir.
Geliştirici Notları

Uygulama her başlatıldığında JSON dosyalarındaki mevcut veriler yüklenir.
Dosya okuma veya yazma sırasında oluşabilecek hatalar ele alınmıştır.
Katkıda Bulunma

Bu projeyi geliştirmek isterseniz, Pull Request oluşturarak katkıda bulunabilirsiniz.

Lisans

Bu proje açık kaynaklıdır ve herhangi bir lisans kısıtlaması olmadan kullanılabilir.
