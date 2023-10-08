## Screen_Saver

# Renk Değiştiren Kareler Uygulaması
Bu proje, HTML ve JavaScript kullanarak dinamik olarak oluşturulan ve belirli aralıklarla renk değiştiren karelerin bulunduğu basit bir web uygulamasını içerir.

<img width="650" alt="Ekran Resmi 2023-10-09 00 18 22" src="https://github.com/zehraarslan/Screen_Saver/assets/48572250/d64039f3-cd20-4b32-b93c-0126241faef1">


# Nasıl Çalışır?
Bu uygulama, tarayıcıda çalışır ve her biri rastgele bir renk alan 1000 adet kare içerir. Aşağıda uygulamanın temel işleyişi açıklanmıştır:

- İlk olarak, HTML belgesi oluşturulur ve tarayıcıda görüntülenen içeriği tanımlar.
- JavaScript kodu, 1000 adet kare oluşturur ve her birine benzersiz bir kimlik (ID) verir.
- Bu karelerin her biri, belirtilen boyut ve arkaplan renkleriyle stilize edilir ve birbirine yakın bir şekilde düzenlenir.
- fnChangeColor fonksiyonu, belirli aralıklarla (1 saniyede bir) her karenin arkaplan rengini rastgele bir RGBA renkle değiştirir.
- Uygulama başladığında setInterval kullanılarak fnChangeColor fonksiyonu düzenli olarak çağrılır ve karelerin renkleri güncellenir.

# Kullanım
Bu kodu kullanmak için aşağıdaki adımları izleyebilirsiniz:

- Bu depoyu klonlayın veya ZIP dosyasını indirin.
- İndirdiğiniz dosyaları bir web tarayıcısında açın (örneğin, Chrome, Firefox, vs.).
- Sayfa yüklendikten sonra, renk değiştiren karelerin etrafındaki görsel efekti gözlemleyin.
- Kodu düzenleyerek, karelerin sayısını, boyutunu veya renk değiştirme hızını özelleştirebilirsiniz.

