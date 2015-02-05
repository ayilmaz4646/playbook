# Kontrol Listesi

Bir işi yapmadan önce yapılması gereken işlerin listesidir.

## Deploy

* Veritabanı yedeklerinin alınması.
* Yeni bir versiyon atılması. version.txt'nin güncellenmesi.
* Müşterinin projesi ise proje grubuna email atılması
* Açık kaynaklı bir proje ise şirket mail grubuna mail atılması ve konu ile ilgili tweet atılması

## Proje Başlangıcı

Aşağıdaki kontrol listesini açık Kaynaklı veya özel projeler için uygulayınız.

**Müşteri adına açılacak hesaplar**

* Gmail mail adresi
* Github hesabı açılması
* Mandrill hesabının açılması
* Amazon S3 hesabının açılması
* İletişim için email grubu açılması
* Facebook app gerekli ise facebook app açılması
* SSL sertifikası alınacak

**Müşteriye sorulacak sorular**

* Sosyal medya hesaplarını aldınız mı?
* Marka tescili yaptınız mı?
* Takımın gtalk, email, iletişim bilgileri sizde var mı?
* Sizin adınıza hollywood lansmanı yapalım mı?
 
**Ekibin yapması gerekenler**

* Proje yöneticisi sözleşme ek1′e göre github issuelardan iterasyonları ayarlar. Böylece huboard kullanılmaya başlanır.
* Müşteri ile github, huboard, çevik süreçler ile ilgili kaynaklar paylaşılır. Müşteriye kısa bir bilgi verilir.
* Stagging ve production için sunucu kurulur. Bu işlem daha ilk kod yazılması ile yapılır.

**Araçlar**

* Github, git versiyon kontrol sitesi
* Huboard, github etiketleri ile oluşturulmuş bir kanban
* Semver
* Gitflow
* Yapılacak iş listesi

**Huboard ve topluluk için Github etiketlerini için düzenlemek.**

* 0 - Backlog [HEX: #DDDDDD]
* 1 - Ready [HEX: #FBCA04]
* 2 - In Progress [HEX: #07D8E2]
* 3 - Done [HEX: #02E10C]
* 4 - Reviewed [HEX: #1007E2]
* 5 - Rejected [HEX: ##F7C6C7]
* Enhancement [HEX: #84B6EB]
* Bug [HEX: #FC2929]
* Future [HEX: #E6E6E6]
* Question [HEX: #CC307C]

**README.md dosyasını güncellemeyiliz**

Bu iş için bir standartınız olursa güzel olabilir.
Örnek olarak [https://github.com/kebab-project/cybele/blob/develop/README.md](https://github.com/kebab-project/cybele/blob/develop/README.md) dosyasına bakabilirsiniz

**VERSION.txt dosyasını eklemeliyiz**

Unutmamak lazım ki versiyonlamayı Semver.org kullanıyoruz. Unutmayalım ki ilk milestonemuz 0.1.0 olmalıdır.
Bknz [semver.org](semver.org)

**LICENSE.txt dosyasını eklemeliyiz**

MIT candır. Örnek olarak [https://github.com/code2/builder/blob/master/LICENSE.txt](https://github.com/code2/builder/blob/master/LICENSE.txt)
dosyasına bakabilirsiniz.

**Projeyi [git-flow](https://github.com/nvie/gitflow) ile yönetmeliyiz**

Etkin geliştirme süreçleri için git branchlar ile manuel uğraşmamamız gerekir.

**CHANGELOG.md dosyasını oluşturmalıyız**

Oluşturulan haftalık iterasyonlar, milestone'lar ve issue'ların hangi versiyonlara ait olduğunu gösteren genel bir
changelog oluşturmalıyız. Ve her release'de güncellemeliyiz. Bu süreçleri otomatikleştirmek için hazırladığımız
ruby rake görevlerini içeren [katip](https://github.com/code2/katip) adlı projemize göz atabilirsiniz.

## Sunucu Kurulumu

* Firewall var mı?
* Periyodik yedek alınıyor mu?
* Sunucu şifreleri Keepass programına girildi mi?

## Siteye Makale Yazılması

* Yazan kişişi - Mail grubuna mail atmak
* Sosyal medya sorumlusu - Twitter ve Facebook hesabında paylaşılması

## Yeni Sürüm Çıkarılması

**Açık Kaynak Projelerde**

* VERSION.txt değişmeli
* CHANGELOG.md değişmeli
* Yeni etiket oluşturulmalı
* Yeni etiket, master ve develop branch push edilmeli
* code2-dev mail grubuna email atılmalı

Sonra

* Yeni versiyon ile ilgili code2'e makale yazılmalı.
* Blog yazısında versiyonda ne olduğu anlatılmalı ve rubygems, changelog gibi unsurlara link verilmeli
* Blog yazısı twitter ve facebook hesabından paylaşılmalı

NOT: Kendinize işkence yapmayın! Git-flow kullanın.

**Müşteri Projelerinde**

* VERSION.txt değişmeli
* CHANGELOG.md değişmeli
* Yeni etiket oluşturulmalı
* Yeni etiket, master ve develop branch push edilmeli
* Proje email grubuna email atılmalı
* Staging sunucusuna deploy edilmeli

NOT: Hotfix olmadıkça yeni sürümler cumadan cumaya çıkar.
