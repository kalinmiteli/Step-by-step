# 1 - Debian iso dosyasının indirilmesi


## A - Siteye ulaşma

Tarayıcınızın adres çubuğuna " [http://cdimage.debian.org/debian-cd/8.6.0/amd64/iso-dvd/](http://cdimage.debian.org/debian-cd/8.6.0/amd64/iso-dvd/) " 
yazarak isoyu indireceğiniz internet sitesine ulaşabilirsiniz.


## B - Dosya seçimi

Buradaki '.iso' uzantılı iso dosyalarından istediğinizi, üzerine tıklayarak 
indirebilirsiniz.

![liste](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/1.png)
![kaydetme](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/2.png)
![yüklenme](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/3.png)


# 2 - Windows üzerinde Debian iso dosyasının USB belleğe yazdırılması ve gerekli aracın kurulumu (Pendrivelinux)


## A - Pendrivelinux'u indirmek için internet sitesine ulaşma 

İnternet tarayıcınızın adres çubuğuna "[http://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/](http://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/)" 
yazarak siteye ulaşabilirsiniz.


## B - İndirme ve kurulum 

Sayfanın altında bulunan indirme butonuna bastıktan sonra '.exe' uzantılı dosyanız inmeye başlayacaktır. İndirme işlemi bittikten sonra dosyayı açın. 

![tıklama](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.1.png)
![kaydet](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.2.png)
![aç](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.3.png)

Karşınıza çıkan lisans sözleşmesini okuduktan sonra 
kabul edin. Birinci adımda USB belleğe koymak istediğiniz Linux dağıtımını seçin. İkinci adımda indirmiş olduğunuz iso dosyasını ekleyin. Üçüncü adımda usb belleğinizin harfini seçin ve "Create" seçeneğine 
tıklayın.
 
![kabulet](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.4.png)
![seç](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.5.png)
![iso](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.6.png)
![usb](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.7.png)
![oluştur](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.8.png)

Karşınıza yapılacak işlemle alakalı bir uyarı çıkacak. Bu uyarı size yapılacak işlemleri ve işlemlerin uygulanacağı USB belleği tekrar gösterir. Sizden doğrulamanız istenir. "Evet" seçeneğini
seçtiğiniz taktirde işlem başlar. İşlem bittikten sonra "Close" seçeneğini seçerek pencereyi kapatabilirsiniz. 

![kapat](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.9.png)
![süreç1](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.10.png)
![süreç2](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.11.png)
![süreç3](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.12.png)
![kapat](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.13.png)

## C - Sonuç

Bu işlemler sonucunda artık boot edilebilir bir USB belleğe sahip olursunuz.

![sonuç](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.14.png)



# 3 - Windows üzerinde disk bölümlendirme

## A - Disk Yönetimine giriş

'Bilgisayarım'a sağ tıklayıp 'yönet'e bastıktan sonra sol taraftaki barda çıkacak olan 'disk yönetimi' seçeneğine basarak disk bölümlendirmesi yapacağınız ekrana ulaşabilirsiniz.


![sağtık](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/1.png)
![giriş](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/2.png)

## B - Disk bölümlendirme

Öncelikle bilgisayarınızdaki disk bölümlerinden birini küçültmeniz ve kendinize bir disk bölümü açmanız gerekiyor. Küçültmek istediğiniz bölümü seçin (Hangi diskinizde boş yer var ise onu seçmelisiniz.). Seçtikten sonra birimin üstüne gelip sağ tıklayın ve 
'birimi küçült' seçeneğine tıklayın. Birim sorgulama bittikten sonra küçültmek istediğiniz alan boyutunu MB cinsinden girerek küçült seçeneğine tıklayın.

![birimseç](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/4.png)
![sorgu](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/5.png)
![boyut](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/7.png)
![disk](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/8.png)




# 4 - Usb'den boot etme işlemi için BIOS/UEFI ayarları

![birim](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/1.jpeg)
![seçim](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/2.jpeg)
![usb](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/3.jpeg)
![kaydetme](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/4.jpeg)
![güvenlik](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/5.jpeg)
![izin](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/6.jpeg)
![geçiş](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/7.jpeg)
![değiştirme](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/8.jpeg)
![öncelikverme](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/9.jpeg)
![tamamatık](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/10.jpeg)
![kaydetçık](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/11.jpeg)


# 5 - Diske Debian kurulumu

Bilgisayarınızı USB takılı şekilde açtığınızda karşınıza Debian kurulumu gelecek. Burada karşınıza pek çok adım gelse de gözünüzü korkutmasın, sadece birkaç adım sizi uğraştıracaktır.

## A - Dil, Konum seçimi ve İsim, Parola Oluşturma

Önünüze gelen ekrandan 'Graphical Install' seçeneğini ok tuşları ve 'Enter' tuşu yardımı ile seçin. Ardından dil ve konum seçimi yapın. Klavye dili seçin.  Yüklemenin bitmesini bekleyip 'makine adı' belirleyin. Alan adı kısmını boş
bırakabilirsiniz. 'Root parolası' belirleyin. (Unutmayacağınıza emin olun zira çok lazım olacak.). Kullanıcı tam adı kısmına kendi adınızı yazın. Ardından kendinize bir kullanıcı adı ve kullanıcı parolası belirleyin. Yükleme bittikten
sonra karşınızda 'Disk Bölümlendirme' kısmını göreceksiniz.

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/1.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/2.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/3.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/4.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/5.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/6.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/7.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/8.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/9.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/10.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/1.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/2.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/13.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/14.PNG)


## B - Disk Bölümlendirme

Karşınıza gelen ekrandan bölümleme yöntemi olarak 'elle' seçeneğini seçin. Önünüze gelecek olan ekranda Sağında 'BOŞ ALAN' yazan birimi seçin ve devam edin. 'Boş alanı otomatik olarak bölümle' seçeneğini seçip devam edin. 
'Tüm dosyalar tek bölümde' seçeneğini seçin. Ardından 'Bölümlendirmeyi bitir ve değişiklikleri diske kaydet' seçeneğini seçin ve devam edin. Önünüze yapılan değişiklikler gelecek. Eğer her şey doğru gözüküyorsa 'Evet' seçeneğini seçin
 ve devam edin. Yüklemenin bitmesini bekleyin. 


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/3.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/4.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/5.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/6.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/7.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/8.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/9.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/10.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/11.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/12.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/13.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/14.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/15.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/16.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/17.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/18.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/19.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/20.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/d%C3%BCzenleme5/21.PNG)
## C - Paket Yöneticisi ve GRUB ekranı 

Ağ yansısı kullanılsın mı sorusuna evet diyin ve devam edin. Ülke seçin. Arşiv yansısını seçin (ftp.tr.debian.org veya ftp.linux.org.tr tavsiye edilir.). HTTP vekil bilgileri kısmını eğer internete bağlanmak için vekil bilgilerine 
ihtiyacınız varsa doldurun, aksi durumda boş bırakabilirsiniz. Yüklenme bittikten sonra karşınıza GRUB ekranı kurulumu gelecek. 'GRUB önyükleyici ana önyükleme kaydına (MBR) kurulsun mu?' sorusuna evet diyin ve devam edin. 
Önyükleyicinin kurulacağı aygıt olarak bilgisayarınızın sabit diskini seçin. Yükleme bittikten sonra karşınıza gelen 'Kurulumu bitir' kısmını okuyup devam edin. Son yükleme bitince bilgisayarınızı kapatın,
USB'yi çıkartın ve tekrar çalıştırın. GRUB ekranından yeni işletim sisteminizi seçerek Debian'ın tadını çıkartabilirsiniz.


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/23.PNG)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/24.PNG)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/25.PNG)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/26.PNG)





#Lisans

Bu belge "GNU Free Documentation License" ile lisanslanmıştır. Lisansı [lisans](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/LICENCES.txt) adresinden inceleyebilirsiniz.


# Yapılacak Değişiklikler :


## 1. ve 2. Bölüm İçin :

* Arama motoru kullanılmadan URL verilecek.
* İso dosyası indirme seçeneklerinde, gnome değil full imaj tercih edilecek ve yönergeye buna göre devam edilecek.
* Firefox ya da başka bir özgür tarayıcı üzerinden ekran görüntüleri alınacak.
 
## 3. Bölüm İçin :

* "Bilgisayarım" ikonu, yanındaki ikonlar yok edilerek ve arkaplan siyah belirlenerek daha görünür hale getirilecek.
* 3 B - Disk Bölümlendirme kısmında (Bu genellikle "C:" olacaktır.) ibaresi yerine "Hangi diskte boş yer varsa o küçültülmeli." yazılacak.

## 4 . Bölüm İçin : 

* Açıklama silinecek.
* Ekran görüntüleri daha doğru açıdan çekilecek.
* UEFI ayarları da dahil edilecek.

## 5. Bölüm İçin : 

* Telefon görüntüsü yerine ekran görüntüleri kullanılacak.
* Tam ad kısmına "Ad Soyad", kullanıcı hesabı kısmına "kullanici_adi" yazılacak. 
