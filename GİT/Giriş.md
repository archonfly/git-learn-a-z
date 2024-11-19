# GİT GİRİŞ

## Git nedir? 
Git metin tabanlı sürüm / versiyon kontrol sistemidir . Git, 2005 yılında Linus Torvalds tarafından geliştirilmiştir . Git açık kaynak bir yazılımdır . Git , metin tabanlı dosya dizinlerindeki değişiklikleri takip edebileceğiniz ,  geliştirebileceğiniz , geliştirilen dosya dizininin geçmişine erişebileceğiniz , birden fazla kimse ile dosya dizinindeki dosyalarınızı geliştirmenize olanak sağlayan , kimin hangi değişikliği yaptığını öğrenebileceğiniz , yerelde çalışıp ve hızını seveceğiniz sürüm / versiyon metin tabanlı kontrol sistemidir . " Git, dağıtık yapısı sayesinde her geliştiricinin yerel deposunda tüm proje geçmişini barındırır , bu da merkezi bir sunucuya bağlı kalmadan çalışma imkanı sunar . " [5] " Stackoverflow bir anketine göre yazılımcıların 94% git kullandığı aonucu elde edilmiştir . " [1]  Tekrardan hatırlatmak istiyorum yazılım alanının kullanımı dışında , metin içeren dosyalarıda takip etmek için kullanabilirsiniz . Örneğin , tez yazan bir akademisyen , roman yazan bir yazar , iş geliştirmek için kullanan yönetici . Yeni öğrenmeye başlayan biri genelde git ve github karıştırmaktadırlar . Git sürüm / versiyon kontrol sistemidir . Github ise git kullanıcılarına hosting hizmeti sunmaktadır . Github , bir çok alternatifi bulunmaktadır . Bitbucket , SourceForge , Gogs , Gitbucket , AWS CodeCommit , Beanstalk , Phabricator , Gitea , Allura , Rodod Code , ... Dahada eklenebilir ama bu dökümanda sadece git ve github üzerine odaklanılarak yazılmıştır . Git aracını çevrim içi veya çevrim dışı kullanabilirsiniz . Git , yerelde çalışdığından dolayı hızlıdır . Git , bir çok platformda desteklemektedir . Linux , MacOs , Windows , İOS ve Android kullanabilirsiniz . 

### Git Kurulumu [5]

Git'i kurmak için aşağıdaki adımları takip ediniz .



##### Windows
Git for Windows sitesinden indirin ve kurulum sihirbazını izleyin.

1. " https://gitforwindows.org/ " 

##### macOS
Terminal üzerinden Homebrew kullanarak brew install git komutunu çalıştırın .

`brew install git`

##### Linux 
Terminal üzerinden sudo apt-get install git komutunu çalıştırarak Git'i yükleyin.

`sudo apt-get install git`

##### Android
Fdroid veya github'dan termux son sürümünü yükleyin. Aşağıdaki komutları çalıştırın. 

`pkg update & upgrade`  <- Termux güncelleme

`termux-setup-storage`  <- Termux'un yerel hafızaya erişmesine izin verin.

`pkg install git`  <- git indirme komutu 

##### Araçların Linkleri 
Buradan kurulum için gerekli araçların linklerine ulaşabilirsiniz . 

### Konfigrasyon 
Kurulumdan sonra, Git'i kullanmaya başlamadan önce bazı temel konfigürasyon ayarlarını yapmanız gerekmektedir . 
Aşağıdaki ayarları doğru ve kendinize göre yapmadığınız takdirde Git'i bilgisayarınızda kullanamayacak hata alacaksınız. O yüzden Git'i bilgisayarınıza kurduktan hemen sonra bu ayarları terminal ekranından yapmanız önemlidir.