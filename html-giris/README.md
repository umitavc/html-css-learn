# HTML Nedir?
HTML kod, kısaca “standart bir metin işaretleme dili” şeklinde tanımlanabilir. 90’lı yıllarda ortaya çıktığı bilinen bu dijital dil, hiç şüphesiz internetin bugünkü işlevlerinin pek çoğunun temelini atmaya yardımcı olmuştur. Evrensel açılımı “Hypertext Markup Language” şeklindedir ve Türkçe karşılık olarak “Hipermetin İşaretleme Dili” ya da “Köprü Metni Biçimlendirme Dili” tabiri kullanılır.

Hipermetin, bilgisayar gibi elektronik cihazların ekranında görüntülenen bir çeşit belge olarak tanımlanabilir. Sadece yazıdan ibaret değildir ve video, fotoğraf, tablo gibi içerikleri de kapsar. Ayrıca sayfalar ve web siteler arasında köprü görev de görür. Hipermetin İşaretleme Dili ise bu hipermetinleri hazırlamak için kullanılan kodlardan oluşan bir dildir. Sürekli geliştirilen bu dilin güncel olarak kullanılan son sürümü HTML5’tir.

Dijital kodların yeni programlar yazmak ve çalıştırmak için kullanıldığı da doğrudur fakat HTML özellikleri itibariyle böyle bir işlevi yerine getiremez. Örneğin HTML kod yazma işlemi ile bir tarayıcı uygulaması yapılamaz ama o tarayıcının ekranında gösterilecek tüm içerikler hazırlanabilir. Bu nedenle bir programlama dili değil, işaretleme dilidir.


## Doctype 
Türkçesiyle Belge tipi; internet sayfaları hazırlarken sayfanızın hangi türe ait olduğunu internet tarayıcısına bildirmek amacıyla kullanılan bir bildirme etiketidir. Bu etiket sayesinde sayfanızı tasarlarken hangi HTML sürümünü kullandığınızı internet tarayıcılarına bildirebilir ve internet sitenizin tüm internet tarayıcılarında ideal görüntülenmesini sağlayabilirsiniz.

## Etiketlere nitelik (attribute) tanımla
* Tüm HTML öğelerinin özellikleri olabilir.
* Öznitelikler bir öğe hakkında ek bilgi sağlar.
* Öznitelikler her zaman başlangıç ​​etiketinde belirtilir.
* Öznitelikler genellikle ad / değer çiftleri olarak gelir: name = ‘value’ gibi.

## Href Özniteliği
* HTML bağlantıları <a> etiketi ile tanımlanır. Bağlantı adresi href niteliğinde belirtilir.

## Src Özniteliği
* HTML görüntüleri <img> etiketi ile tanımlanır. Görüntü kaynağının dosya adı, src özniteliğinde belirtilmiştir.

 
 ## Genişlik (width) ve Yükseklik (height) Özniteliği
 * HTML’deki resimler, görüntünün genişliğini ve yüksekliğini belirten  özniteliklere sahiptir.

## Alt Özniteliği
 * alt özniteliği, bir görüntü gösterilemediğinde kullanılacak alternatif bir metin belirtir.

## Style Özniteliği
 * Stil özelliği, renk, yazı tipi, boyut vb. Gibi bir öğenin stilini belirtmek için kullanılır.
 

## Lang Özniteliği
 * Belgenin dili <html> etiketinde bildirilebilir.
 * Belgenin dili <html> etiketinde bildirilebilir.
 * Dil bildirmek, erişilebilirlik uygulamaları (ekran okuyucular) ve arama motorları için önemlidir.

## Title Özniteliği
* <p> öğesine bir title özniteliği eklendiğinde paragrafın üzerine fare ile gelindiğinde başlık özniteliğinin değeri bir ipucu olarak görüntülenir.

## Disabled Özniteliği
* Bir giriş öğesinin devre dışı bırakılması gerektiğini belirtir.

## id Özniteliği
* Bir öğe için benzersiz bir kimlik belirtir.

## <html> Etiketi Ne İşe Yarar?
* html etiketi içerisine yazılacak tüm etiketleri kapsar. Html etiketi kullanmadan diğer etiketlerin bir anlamı olmaz.

## head Etiketi Ne İşe Yarar?
* Bu etiket sayfanın tarayıcıya ve arama motorlarına tanıtıldığı (Meta etiketleriyle), CSS ve Javascript dosyalarının dahil edildiği alanı temsil etmektedir. Sayfa görünümde herhangi bir değişikliğe sebep olmaz. Görünmez özellikleri temsil edecektir.

## <title> Etiketi Ne İşe Yarar?
* Bu etiket sayfa isminin belirtilmesini sağlar. Yani tarayıcı sekmesini temsil eden adı kapsar.

## meta Etiketi Ne İşe Yarar?
* Meta etiketleri sayfaya ait temel bilgileri (Sayfa açıklaması, anahtar kelimeler, başlık vs) gibi bilgileri tarayıcılara ve arama motorlarına iletir. Böylelikle sayfanın hangi konu ile alakalı olduğunu arama motorları öğrenir ve sonuçları o bilgilere göre listeler. Meta etiketleri her html sayfasında muhakkak olması gereken etiketlerdir.

## body Etiketi Ne İşe Yarar?
* Bu etiket arasında yazacağımız tüm etiketler ekrana yansır. Genel olarak tasarım yaparken body etiketleri arasında çalışacağız. Yani body etiketi bir html dosyanın en önemli kısmı.

## En Çok Kullanılan HTML Etiketleri Nelerdir
- H Etiketleri
  * H etiketleri başlık etiketleridir. Büyükten küçüğe sırasıyla . h1,h2,h3,h4,h5,h6.
  * HTML otomatik olarak Başlık etiketlerinin öncesine ve sonrasına satır atlatır.


- P Etiketi 
  * p etiketi paragraf etiketidir. Sayfa içerisinde oluşturacağımız metinleri p etiketi ile oluştururuz.


- BR Etiketi
  * br etiketi satır atlatma etiketidir ve kapatmaya ihtiyaç duymayan etiketlerden biridir. Atlatmak istediğiniz satır sayısı kadar br etiketi kullanabilirsiniz. NOT: BR etiketinin farklı kullanımlarını görebilirsiniz. örn.(<br>,<br/>,<br />) Hepsi aynı işlevi yerine getirir.


- A Etiketi
  * a etiketinin en önemli özelliği href özelliğidir. Bu etiket ile sayfaları linkleyebiliriz. Etiket içerisine yazılan içerik sayfa üzerinde gösterilecek içeriktir. href içine yazılan ise tıklandığında gideceği URL'dir.

## Listeleme Etiketleri
- ol
  * Sıralı liste oluşturmak için ol etiketi kullanılır. 
- ul
  *  Sırasız liste oluşturmak için ul etiketi kullanılır.
- li
  * li etiketi liste öğelerini yazmak için kullanılır.
- Liste etiketiyle kullanılabilecek parametreler
  * type: sıralı yada sırasız listenin türünü belirler.
  * Sırasız Liste İçin;
    - Disc : içi dolu daire
    - Circle : içi boş daire
    - Square : kare
  * Sıralı Liste İçin;
    - 1 : onluk taban 
    - i : küçük romen rakamları
    - I : büyük romen rakamları
    - a : küçük harf 
    - A : büyük harf
  * start: sıralı listede başlangıç değerini belirtmek için kullanılır.
  * value: Liste ögesinin numarasını belirtmek için kullanılır.
  
## STRONG ve B Etiketi
  * strong etiketi bir metinin arama motorlarına önemli olduğunu bildirmek için kullanılır. Kullanıldığı zaman metini kalın yapar. Eğer sadece metini kalınlaştırmak isterseniz b etiketini kullanabilirsiniz.

## Script Etiketi
* script etiketi JavaScript kodlarını HTML içerisine yazabilmemizi sağlar.

## Button Etiketi
* button etiketini buton oluşturmak için kullanırız. Buton üzerine yazmak istediğiniz içeriği etiketin içine yazmanız yeterlidir.
## img Etiketi
* Resim eklemek için img etiketini kullanıyoruz. img src=”resim.jpg” alt=”açıklama yazısı” src="" kısmına eklemek istediğimiz görselin yolunu yani kaynağını yazmalıyız. Eğer görselimiz ve HTML dosyamız aynı klasörde ise görselin adını ve uzantısını yazmamız yeterlidir. alt="" kısmına görselin açıklamasını yazıyoruz fakat isterseniz boş bırakabilirsiniz. Bu etiket kapanmaya ihtiyaç duymaz.

## iframe Etiketi
* Belge içinde belge gösterebilmemizi sağlayan etikettir. Genelde başka bir sitedeki belgeyi kendi sayfamızda göstermek için kullanırız. örn: Youtube'dan bir videoyu sayfamızda göstermek istersek iframe kodlarını sayfamıza eklememiz yeterli.(video üzerinde sağ tıklayıp yerleştirme kodunu kopyala diyerek iframe kodunu kopyalayabiliriz.)








 


  

  



