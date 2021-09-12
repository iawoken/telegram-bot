# Telegram Kullanıcı Ekleme Botu
Bu projenin temel amacı: "A" grubundaki kişileri, sizin "B" grubunuza **eklemektir.** Tek tek kullanıcıları manuel eklemektense bu bot ile tek tuşla ekleyebileceksiniz!

## Kurulum
Gelelim en önemli kısıma. Bu projeyi nasıl kullanılabilir hale getirebilirim?
Öncelikle, gereken teknolojileri (Python) ve bu teknolojilerin kütüphanelerini kurmamız gerekiyor.
- Python'u cihazınıza indirmek için: https://www.python.org/downloads/
- Gereken kütüphaneleri kurmak için: `pip install -r requirements.txt`

## API
Telegram API Key almayı bilmiyor iseniz aşağıdaki adımları uygulayabilirsiniz;
- https://core.telegram.org/api sitesine girin ve "[Creating an Application](https://my.telegram.org)" diyin.
- Karşımıza gelen sayfada detaylar bulunmakta. Buradan "**Obtaining api_id**" kısmına gelip, https://my.telegram.org linkine tıklayalım.
- Ardından karşımıza giriş ekranı geliyor. Burada bilgilerimizi doldurup "**Next**" diyoruz.
- Telefonumuza doğrulama amaçlı bir kod gelecek. Gelen kodu girdikten sonra "**API development tools**" diyoruz.
- Uygun formatta bilgileri dolduruyoruz:
```
App title: Uygulama ismi
Short name: 5 ile 32 karakter arasında sayı girin.
URL: boş bırakabiliriz.
Platform: Other (Diğer)
Description: Herhangi bir açıklama.
```
- Ve uygulama bilgilerimizin bulunduğu sayfaya yönlendirildik. Buradan `api_id` ve `api_hash` bilgilerini alıyoruz. 🎉

## Kullanım
Projeyi aktif etmek için öncelikle "**Bot.py**" içerisinde bulunan "Config" kısmını doldurmamız gerekiyor.
Eğer ki `API ID` ve `API HASH` bilgileriniz yok ise yukarıda yazmış olduğum "API" başlığından öğrenebilirsiniz!
