# image-organize

Yıllardır çeşit çeşit araçlar ile  sürü ile resim ve video biriktirdim. Bunları düzenli tutmak ise hep ayrı bir dert oldu. Bunu okuyan çoğu kişi at cloud'a düzeni boşver diyebilir. Biraz eski kafalılık herhalde dosyalar benim local ortamımda da duracak ve benim istediğim düzende duracak gibi bir takıntım var. dertler bunun ile bitmiyor tabii ki. Herşeyin 10 tane yedeği olunca kim eski kim yeni soruları da anlamını yitiryor. Bu sorunu halletmek için küçük bir notebook yazdım. Burada belirli bir dizinde olan tüm resim ve video dosyalarını aynı dizin içerisinde ait olduğu yıl klasörüne taşıyor. Bu taşıma sırasında hedef klassörde aynı isimli bir dosya var ise ikisini MSE(mean squared error) ile karşılaştıyor ve sonuç sıfır ise üzerine  yazıyor. değil ise bir kopyasını oluşturyor. 

Bilinen Sorunlar:

* Aynı isimli Mov dosyalarını ezemiyoruz. 
* Kod hiç derli toplu değil. Biraz daha kullanırsam belki bir tasarım deseni uygularım.
* jupyter notebook ihtiyacı var.
