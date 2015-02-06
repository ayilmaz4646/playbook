# Çevik Süreçler

![Agile Metodoloji](images/agile.png)

Code2, proje yönetimi için çevik süreçler kullanır.

* [Çevik Manifesto](http://agilemanifesto.org/iso/tr/)
* [Çevik İlkeler](http://agilemanifesto.org/iso/tr/principles.html)
* [Kanban](http://kanban.code2.co) için huboard programını kullanıyoruz.
* Sürüm kontrolü için [semver](http://semver.org/) kullanıyoruz.

# Huboard

Huboard' un proje üzerinde uygulanması için github'da aşağıdaki 6 + 4 etiket açılır ve ilgli renk kodları düzenlenir:

* 0 - Backlog [HEX: #DDDDDD]
* 1 - Ready [HEX: #FBCA04]
* 2 - In Progress [HEX: #07D8E2]
* 3 - Done [HEX: #02E10C]
* 4 - Reviewed [HEX: #1007E2]
* 5 - Rejected [HEX: ##F7C6C7]
* Bug [HEX: #FC2929]
* Future [HEX: #E6E6E6]


Etiketlerin anlamları:

* 0 - **Backlog** : Müşteri ile görüşülmeye devam eden veya görüşülmüş, detaylandırılması sonuçlanmamış, yani henüz analizi tamamlanmamış iş birimi.
* 1 - **Ready** : Analizi tamamlanmış, detaylandırılması yapılmış, geliştirilmeye hazır iş birimi
* 2 - **In Progress** : Geliştirici iş birimini geliştirmeye başlamış, yani geliştiricini hali hazırda üzerinde çalıştığı iş birimi
* 3 - **Done** : Geliştirici iş birimini geliştirmeyi tamamlamış, geliştirme ortamında çalışan iş birimi.
* 4 - **Reviewed** : Geliştiricinin tamamladığı iş birimi kontrol edilmiş, yazım standartlarına uygun olduğu, istenilen işlevi yaptığı ve çalışır olduğu doğrulanmış iş birimi. Üretim ortamına atılabilir, yayınlamaya hazır iş birimi.
* 5 - **Rejected** : Geliştiricinin tamamladığı iş birimi kontrol edilmiş, ancak yazım standartlarına uyulmadığı, istenilen işlevi yapmadığı veya doğru çalışmadığı tespit edilmiş iş birimi.

## Github ve Etiketler

code2 projelerinde github'da 4 adet etiket açılır.

* **Bug** - Hata bildirimleri için kullanılır.
* **Future** - Proje süresince müşterinin aklına gelen ancak anlaşmadığımız gelecekte yapılması planlanan işlerdir. Bunlar yapılmaz ancak fikirler unutulmasın diye future etiketi ile etiketlenir.

# Semantik Versiyonlama

code2 olarak www.semver.org adresinde ki standartlara göre versiyonlama yapıyoruz. Bu reponun Türkçesini https://github.com/lab2023/semver/blob/master/semver_tr.md adresinde bulabilirsiniz.

**Kurallar**

* X.Y.Z şeklinde ifade edilecen bir versiyonlama da X -> Major, Y -> Minor, Z -> Patchi ifade eder.
* Z -> Uygulamaya yapılan hotfix ve typo düzeltmelerinden de yapılır. Yani uygulamaya yeni bir özellik eklemediyseniz, belli bir yerdeki bir hatayı veya yazıyı değiştirdiyseniz Z sayısı değişir.
* Y -> Uygulamaya eklenen yeni özellikler, iyileştirmeler sonucunda değişir. Y deki değişiklikler eski kullanıcıları eklemez. Y de ki değişiklikler **GERİYE UYUMLU**dur.
* X -> Uygulamada yapılan büyük değişikliklerdir. Örneğin yapının komple değişmesi, teknolojinin değişmesi gibi gibi. X de yapılan bir değişiklik **GERİYE UYUMLULUĞU** desteklemez.
* Bir uygulama 0.1.0 versiyonu ile başlar. 
* Bir uygulama product olunca 1.0.0 olmalıdır. 
* Eğer X = 0 ise o uygulama stable değildir. Yani her an her şeyi değişebilir. Hala develop aşamasındadır.
* Her uygulmanın versiyonunu gösteren bir API si olmalıdır. Yani kullancılar, diğer developerlar mutlaka hangi sürümü kullandıklarını bilmelidir! **Bu programcının birinci ve en önemli görevidir.**
* Versiyonlamada [0-9A-Za-z-] ifadelerini kullanabilirsiniz.
* 1.0.0-alpha.1 gibi prepatchleri kullanmanızı biz code2 olarak önermiyoruz. Hayat zaten yeterince karışık!

# Üretkenlik

Bu bölümde geliştiricilerin üretkenliğini artırmaya yönelik kurallar vardır.

* Gelişticiler ile toplantılar günde bir alınır. Bu toplantılar günlük 5 dakikayı geçemez.
* Geliştiricilere işler iteratif olarak haftalık verilir.
* Geliştirici aynı anda iki projeye de çalışmaz. Bir proje bitmeden başka projeye geçemez.
* Mümkün olduğunca iki geliştirici bir projede çalışır.
* Geliştiriciler sorularını mail grubunda sorarlar. Böylece sorular kayıt altına alınır. Aynı sorular iki defa sorulmaz.
* İletişim aracı olarak sırasıyla 1. mail, 2. gtalk, 3. cep telefonu tercih edilir. Böylece geliştiriciler bir birlerini rahatsız etmez.
* code2 geliştiricilerine donanım, lisans vb unsurları alması için kredi verir, bu konuda maddi olarak destekler.
