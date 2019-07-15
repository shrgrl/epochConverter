# epochConverter
Bu proje, bir Epoch Dönüştürücü uygulamasını HTML/CSS/JavaScript kullanarak yazıldı. 1 Ocak 1970 günü saat 00:00’da başlayan ve sonrasındaki herhangi bir ana kadar geçen saniye cinsinden süreye Epoch Zamanı adı verilmektedir. (Hesaplamalarda artık yılları da dikkate almamız gerek, artık olmayan her bir yılda 86400x365=31536000 saniye ve her bir artık yılda 86400x366=31622400 saniye tüketildiğini hatırlayalım.)

Proje 3 kısımdan oluşuyor. Uygulamanın birinci (en üst) bölümünde aşağıdaki gibi bir ekran yer alıyor ve bu ekrana ait 3
bilginin her biri her saniye güncellenerek kullanıcıya sunuluyor.

![](https://github.com/shrgrl/epochConverter/blob/master/img1.JPG)

Uygulamanın ikinci bölümünde aşağıdaki gibi bir ekran yer alıyor ve bu ekrandaki text kutucuğuna girilen Epoch zamanı yandaki butona tıklandığında bizim kullandığımız zaman formatına dönüştürülerek kullanıcıya sunuluyor.

![](https://github.com/shrgrl/epochConverter/blob/master/img2.JPG)
![](https://github.com/shrgrl/epochConverter/blob/master/img3.JPG)
Uygulamanın üçüncü ve son bölümünde aşağıdaki gibi bir ekran yer alıyor ve bu ekrandaki her bir HTML form elemanı <select> özelliği taşıyor. Yani kullanıcı her bir veri girişini bir drop-down listesi sayesinde yapabiliyor. (Year için listelenecek değerler 1971 ile 2023, Month için 01-January ile 12-December, Day için 01 ile 31, Hour için 01 ile 23, Minute için 01 ile 59 ve Second için 01 ile 59 arasında) Öte yandan Time Zone Local veya GMT olarak seçilebiliyor. Kullanıcı veri girişi yaptıktan sonra Convert isimli butonu tıkladığında ilgili tarihe denk gelen Epoch zamanı hemen altta ekrana yansıtılıyor.
![](https://github.com/shrgrl/epochConverter/blob/master/img3.JPG)
  
