# image-organize
***TR***

Yıllardır çeşit çeşit araçlar ile  sürü ile resim ve video biriktirdim. Bunları düzenli tutmak ise hep ayrı bir dert oldu. Bunu okuyan çoğu kişi at cloud'a düzeni boşver diyebilir. Biraz eski kafalılık herhalde dosyalar benim local ortamımda da duracak ve benim istediğim düzende duracak gibi bir takıntım var. dertler bunun ile bitmiyor tabii ki. Herşeyin 10 tane yedeği olunca kim eski kim yeni soruları da anlamını yitiryor. Bu sorunu halletmek için küçük bir notebook yazdım. Burada belirli bir dizinde olan tüm resim ve video dosyalarını aynı dizin içerisinde ait olduğu yıl klasörüne taşıyor. Bu taşıma sırasında hedef klassörde aynı isimli bir dosya var ise ikisini MSE(mean squared error) ile karşılaştıyor ve sonuç sıfır ise üzerine  yazıyor. değil ise bir kopyasını oluşturyor. 

Bilinen Sorunlar:

* Aynı isimli Mov dosyalarını ezemiyoruz. 
* Kod hiç derli toplu değil. Biraz daha kullanırsam belki bir tasarım deseni uygularım.
* jupyter notebook ihtiyacı var.

***EN*** 

Over the years, I have taken a lot of pictures and videos with a variety of cameras and phones. Keeping them organized has always been a separate problem. Most people reading this might say "move to the cloud". I'm a little bit old-fashioned, I have an obsession that the files should stay in my local machine and should store them in the order I want. Of course, the troubles don't end there. Most of you have 10 copies & backups of everything, and the simple question arises when you want to arrange them, which one is latest? I wrote a small notebook to handle this problem. it arranges all the picture and video files in a root of certain directory, not subdirectories. Creates year folder(such as 2012) and move files using their last accessed, date taken attribbutes. During this migration, if there is a file with the same name in the target folder, matches two of them with MSE(mean squared error) and overwrites if the result is zero.(means same) If not, it creates a copy.

Known Issues:

We cannot overwrite Mov files with the same name.
The code is not tidy at all. Maybe I'll implement a design pattern if I use a little more.
jupyter notebook reueires
