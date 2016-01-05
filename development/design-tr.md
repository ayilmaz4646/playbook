# Ürün Tasarım Süreci
Orjinali : [Thoughtbot Playbook](http://playbook.thoughtbot.com)

> "Çoğu insan tasarımın bir şeyin nasıl göründüğüne dair bir konu olduğu
> yanılgısına düşer. Onlara göre bu kadar basittir : tasarımcılara bir kutu
> verilir ve 'bunun güzel görünmesini sağla' denir. Konu sadece bir şeyin nasıl
> göründüğü veya hissettirdiği değildir. Tasarım bir şeyin nasıl çalıştığıdır."
> -Steve Jobs

[Ürün Tasarım Süreci](http://robots.thoughtbot.com/the-product-design-sprint)
[Google Ventures](http://gv.com/design)'un icat ettiği bir kavramdır ve [insanların istediği bir şeyi](http://paulgraham.com/good.html) ortaya çıkarmayı amaçlayan 5 aşamalık bir uygulamadır. Maliyetli bir geliştirme sürecine başlarken varsayımlar yerine doğrulanmış şeylere güvenmeyi yeğliyoruz. Veya, hiç işe yaramayacak bir ürünü inşa edip buna değmeyeceğini öğrenmektense kurşunlar gelirken eğilmeyi istiyoruz.

Süreçler bir ürün veya iş akışı ortaya çıkartırken iyi başlangıç noktalarıdır,
aynı zamanda var olan ürünlerle ilgili olarak mevcut sorunları çözerken de
faydalı araçlar oluştururlar. Genellikle 5 gün sürerler ama daha az zamanda da
tamamlanabilirler. Başlangıç olarak bir odanın içine olabildiğince paydaşı ve
uzmanlığı toplamaya çalışmanız beklenir. 

Ürün Tasarım Süreçlerine test güdümlü tasarım olarak ta bakılabilir.

![Sprint Aşamaları](../images/design_sprint_phases.png)

## Hazırlık Çalışmaları

Sürece başlamadan önce, müşterilerimiz ürünümüzü son test aşamasında deneyecek 5
gerçek kişiyi bulurlar. Sonuçta kullanıcılarını bizim tanıdığımızdan daha iyi
tanımaları beklenir.

Aynı zamanda aşağıdakiler gibi internet üzerindeki değişik kaynaklar üzerinden
bilgi toplarlar :

* [Quora](http://quora.com)
* [Google Analtyics](http://analytics.google.com)
* [Adwords Anahtar Kelime Planlayıcı](https://adwords.google.com/ko/KeywordPlanner/Home)

Aynı zamanda biz de bazı (ücretli) çalışmalar yapabiliriz. 

* [Kullanıcı görüşmeleri](http://www.nngroup.com/articles/interviewing-users/) planlayabilir ve yapabiliriz.
* Kullanıcılara ilişkin, sonuçlarının ilk aşamada tartışılacağı bir [anket](http://www.google.com/insights/consumersurveys/use_cases) çalışması yapabiliriz.

Genellikle ilk gün haricinde yemek için durduğumuz bir aktiviteden söz
etmiyoruz, bunun yerine ayaküstü birşeyler atıştırıp kısa molalar sonrasında
devam ettiğimiz bir aktivite oluyor.

## Anlayın

Bu aşamadaki alıştırmalar bizim için kullanıcılarımızın hayatını (tüketici
yazılımları) veya işini (iş yazılımları) anlayıp empati kurmak için gerekli faaliyetlerdir.

Bu aşama boyunca insanlar çoğunlukla post-it benzeri şeylerin üzerine not alır,
ve bulundukları odanın duvarlarına yapıştırırlar.

Bu aşamaya sunum egzersizi ile başlarız. Burada müşteri, ürününü tıpkı bir
yatırımcıya anlatır gibi anlatır. Bu deney bizim kullanıcıyı tanımamıza,
sorunlarını ve bu sorunu çözmek için kullandıkları ürünleri anlamamıza yardımcı
olur. Aynı zamanda yazılımın hizmet edeceği alan ile ilgili kelime haznesini de
oluşturmaya başlar.

Daha sonra, o zamana kadar yukarıda sayılan kaynaklar üzerinden yapılmış
araştırmaları inceleriz. Bu araştırmalar bize kullanıcılarımızın
motivasyonlarını, pazarlama kanallarını ve hedef pazarların büyüklüğünü
anlamamız konusunda yardımcı olur. 

Son olarak, tasarım sürecinin geri kalanının odaklanacağı şeyin eskizini
çıkartırız : yazılımın kritik yolu. Bu aşamada bunu olabildiğince konseptüel ve
detaylardan uzak tutmaya çalışırız. Kritik yolu ortaya çıkartırken
kullanılabilecek harika bir soru şudur :

>[Kullanıcı ürünü hangi işi yapmak için kiralıyor?](http://www.youtube.com/watch?v=f84LymEs67Y)

![Kritik Yol](../images/criticalpath.jpg)

Kritik yolu aşamalar ilerledikçe gözden geçirerek geliştireceğiz.

## Dağıl

Bu bölümdeki egzersizler hayal gücümüzü, kullanıcının ihtiyacı olan potansiyel
çözümler için geniş biçimde kullanmamıza yardımcı olur.

Bu aşamadan önce, ekibin tümü odada dolaşarak duvarlardaki yapışkan notları
inceler, kritik yol ile karşılaştırır ve kritik yola eklenmesi gerektiği halde
eklenmeyen bir özellik olup olmadığına bakar.

Bu bölüme yine sunum çalışması ile başlar ve sunumda ifade edilenleri kritik yol
ile karşılaştırırız.

Daha sonra ekipteki herkesin 10 veya daha üzerinde [kullanıcı akışı]((https://signalvnoise.com/posts/1926-a-shorthand-for-designing-ui-flows) ve kullanıcı arayüzü çizmelerini istiyoruz. İnsanlara kullanıcıların uygulamaya gelecekleri kaynakları da dahil etmelerini söylüyoruz: Twitter? Blog gönderisi? Adwords? Otomatik öneriler? Email? Bir arkadaşın tavsiyesi? Anlık bildirim?

Eğer ürün gerçekleşirse, bu kaynaklar sonunda [Google Analytics içinde bulunan
"Edinme Kanalları"](http://analytics.blogspot.com/2013/10/new-acquisitions-reporting-channels.html) raporunda ölçümlenecek.

![Edinme Kanalları](images/acquisitionchannels.jpg)

Dhaa sonra bu eskizleri bir duvara koyuyor ve sessiz bir kritik seansına
girişiyoruz, gözlem yaparak ve sevdiğimiz arayüzlerin üzerine yapışkanlı işaretler koyarak ilerliyoruz. Herhangi bir fikri yargılamıyor veya yüceltmiyoruz. Bu oylama
süreci uzun tartışmaları ve komite tarafından tasarımı önlüyor.

Son olarak, daha büyük yapışkanlı işaretler koyarak bir "süper oylama"
yapıyoruz. CEO veya ürünün sahibi her kimse o, en iyi fikirlerin üzerine büyük
bir "süper oy" yapıştırıyor. Bu bize müşteri organizasyonunun nasıl düşündüğünü
anlama ve otoritelerini pekiştirme şansı veriyor.

Bizim deneyimimize göre bu aşama gerçekten zihinsel olarak çok yıpratıcı.
Önerimiz bu aşamadan sonra daha fazla devam etmeyip erken bitirmeniz ve ekibi
yeniden şarj olmaları için eve göndermeniz.

## Toplanın

Bu bölümdeki egzersizler bize yeni çözümler üretmeyi durdurmakta ve mevcut
çözümler arasında en iyi olanlara odaklanmakta, aynı zamanda da prototip için
testleri yazmakta yardımcı oluyor.

Öncelikle, en iyi tasarım fikirleri içinde varolan varsayımları tanımlıyoruz.
Kullanıcıların motivasyonlarıyla, iş modeliyle, kullanıcıları edinebilme
kabiliyetimizle ve bütçe içinde çözümü uygulayabilme kabiliyetimizle ilgili tüm
varsayımları tanımlıyoruz. Bunun bazı seçenekleri elememiz konusunda yardımı
dokunuyor.

![Varsayımlar](../images/assumptions.jpg)
