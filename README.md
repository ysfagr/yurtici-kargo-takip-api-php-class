# yurticikargo

Entegrasyon dökümantasyonu (Klavuz) yurtiçi kargo pazarlama sorumlusundan almanız gerekmektedir.
Ordaki bilgileri , değerleri ve karşılıklarını görmeniz geremektedir.

Kargo Key otomatik oluşturup bu key ve kargo bilgileri ile (adres,telefon,fatura ve irsaliye (ticari gönderiler) numarası zorunludur) 
kargo siparişi oluşturup yurtiçi kargo nun sistemine sipariş (kargo çıkışı) düşürülür.
Kargo firması kargo almaya geldiğinde kargo keyi ile kargoları alır ve bunları sisteme bu key ile girerler.Sizde bu key ile kargonuzun 
durumunu takip edebilirsiniz.(Biraz zorunlu sorunlu bir süreç).


http://webservices.yurticikargo.com:8080/KOPSWebServices/ShippingOrderDispatcherServices?wsdl

Bu link de sorgu yapabilmek için resmi başvuru yapıp kullanıcı adı ve şifre almak durumundasınız.Test linki de var ama ben kullanamadım.
Bu bilgileri başvuru sonrasında size gönderilecek dökümantasyon da görebilirsiniz.
Dökümantasyon da değerlerin anlamlarını ve işlemlerini görebilirsiniz.

Sunucu da bu kodun çalışabilmesi için 80 port unun acık olamsı , soket , openssl , SOAP , curl  gibi eklentilerin açık olması gerekmekte.

https://www.facebook.com/taktikteknoloji/ 
http://umitkatmer.com.tr/
