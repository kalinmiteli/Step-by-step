# 1 - Debian iso dosyasının indirilmesi


## A - Siteye ulaşma

Kullandığınız arama motoruna "cd image debian" yazarak veya tarayıcınızın 
adres çubuğuna "[cdimage.debian.org/debian-cd](http://cdimage.debian.org/debian-cd/)" 
yazarak isoyu indireceğiniz internet sitesine ulaşabilirsiniz.

![at](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/1.png)
![kedi](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/2.png)

## B - Dosyaya ulaşma

Önünüze gelen dizinlerden sırasıyla

*current-live/*

*amd64/*

*iso-hybrid/*

Dizinlerinin içine girerek iso dosyalarına ulaşabilirsiniz.

![dizin1](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/3.png)
![dizin2](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/4.png)
![dizin3](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/5.png)

## C - Dosya seçimi

Buradaki '.iso' uzantılı iso dosyalarından istediğinizi üzerine tıklayarak 
indirebilirsiniz.

![liste](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/6.png)

# 2 - Windows üzerinde Debian iso dosyasının USB belleğe yazdırılması ve gerekli aracın kurulumu (Pendrivelinux)


## A - Pendrivelinux'u indirmek için internet sitesine ulaşma 

Kullandığınız arama motoruna "pendrivelinux download" yazarak veya internet
tarayıcınızın adres çubuğuna
 "[http://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/](http://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/)" 
yazarak siteye ulaşabilirsiniz.
![arama](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.png)

## B - İndirme ve kurulum 

Sayfanın altında bulunan indirme butonuna bastıktan sonra '.exe' uzantılı dosyanız inmeye başlayacaktır. İndirme işlemi bittikten sonra dosyayı açın. 
![indirbuton](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/3.png)
![aç](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/5.png)
Karşınıza çıkan lisans sözleşmesini okuduktan sonra 
kabul edin. Birinci adımda USB belleğe koymak istediğiniz Linux dağıtımını seçin. İkinci adımda indirmiş olduğunuz iso dosyasını ekleyin. Üçüncü adında usb belleğinizin harfini seçin ve "Create" seçeneğine 
tıklayın. 
![agreement](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/6.png)
![adım1](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/7.png)
![adım2](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/mastehttps://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/11.pngr/level2/8.png)
![adım2.1](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/9.png)
![adım3](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/10.png)
![create](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/11.png)

Karşınıza yapılacak işlemle alakalı bir uyarı çıkacak. Bu uyarı size yapılacak işlemleri ve işlemlerin uygulanacağı USB belleği tekrar gösterir. Sizden doğrulamanız istenir. "Evet" seçeneğini
seçtiğiniz taktirde işlem başlar. İşlem bittikten sonra "Close" seçeneğini seçerek pencereyi kapatabilirsiniz. 
![uyarı](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/12.png)
![bekleme1](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/13.png)
![bekleme2](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/15.png)
![kapat](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/16.png)

## C - Sonuç

Bu işlemler sonucunda artık boot edilebilir bir USB belleğe sahip olursunuz.
![sonuç](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/17.png)



# 3 - Windows üzerinde disk bölümlendirme

## A - Disk Yönetimine giriş

'Bilgisayarım'a sağ tıklayıp 'yönet'e bastıktan sonra sol taraftaki barda çıkacak olan 'disk yönetimi' seçeneğine basarak disk bölümlendirmesi yapacağınız ekrana ulaşabilirsiniz.

![sağtık](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/1.png)
![giriş](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/2.png)

## B - Disk bölümlendirme

Öncelikle bilgisayarınızdaki disk bölümlerinden birini küçültmeniz ve kendinize bir disk bölümü açmanız gerekiyor. Küçültmek istediğiniz bölümü seçin (Bu genellikle 'C:' olacaktır.). Seçtikten sonra birimin üstüne gelip sağ tıklayın ve 
'birimi küçült' seçeneğine tıklayın. Birim sorgulama bittikten sonra küçültmek istediğiniz alan boyutunu MB cinsinden girerek küçült seçeneğine tıklayın.

![birimseç](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/4.png)
![sorgu](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/5.png)
![boyut](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/7.png)
![disk](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/8.png)




# 4 - Usb'den boot etme işlemi için BIOS/UEFI ayarları

Öncelikle üzülerek belirtmek zorundayım ki BIOS/UEFI ayarları bilgisayarın marka ve modeline göre hem bu ayarlara ulaşım, hem de ayarların yapılışı açısında farklılık göstermektedir. Bu bölümde size yol göstermesi için göstereceğimiz
ekran görüntüleri ile sizin BIOS/UEFI ekranlarınız ve  ayarlarınız uyuşmayabilir. Bundan dolayı bu ayarları yapmadan önce internetten bilgisayarınızın marka ve modelini belirterek araştırma yapmanız iyi olacaktır.

Bilgisayarınızı kapatıp USB'yi takarak tekrar başlatın. Bilgisayarınız açılırken F1-F2-F10-F11-F12 veya DEL tuşuna arka arkaya basın. Karşınıza çıkacak ekranda size menüler arasında geçiş yapmanızı sağlayacak (genellikle sağ ve sol ok
tuşları), seçim yapmanızı sağlayacak (genellikle 'Enter' tuşu) ve değerleri değiştirmenizi sağlayacak (genellikle -/+ tuşları) tuşları gösteren bir kısım göreceksiniz. Bu tuşlar sayesinde Boot ayarlarına ulaşıp bilgisayarınızı boot 
etmek istediğiniz (bizim durumumuzda USB) bileşeni en üste çıkartın. Yaptığınız değişiklikleri kaydedip çıkın.

![bios](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/1.jpeg)

![system](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/2.jpeg)

![order](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/3.jpeg)

![seçim](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/4.jpeg)

![üst](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/5.jpeg)

![çık](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/6.jpeg)

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

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/11.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/12.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/13.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/14.PNG)


## B - Disk Bölümlendirme

Karşınıza gelen ekrandan bölümleme yöntemi olarak 'elle' seçeneğini seçin. Önünüze gelecek olan ekranda Sağında 'BOŞ ALAN' yazan birimi seçin ve devam edin. 'Boş alanı otomatik olarak bölümle' seçeneğini seçip devam edin. 
'Tüm dosyalar tek bölümde' seçeneğini seçin. Ardından 'Bölümlendirmeyi bitir ve değişiklikleri diske kaydet' seçeneğini seçin ve devam edin. Önünüze yapılan değişiklikler gelecek. Eğer her şey doğru gözüküyorsa 'Evet' seçeneğini seçin
 ve devam edin. Yüklemenin bitmesini bekleyin. 

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/15.jpeg)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/16.jpeg)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/17.jpeg)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/18.jpeg)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/19.jpeg)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/20.jpeg)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/21.PNG)

![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/22.PNG)

## C - Paket Yöneticisi ve GRUB ekranı 

Ağ yansısı kullanılsın mı sorusuna evet diyin ve devam edin. Ülke seçin. Arşiv yansısını seçin (ftp.tr.debian.org veya ftp.linux.org.tr tavsiye edilir.). HTTP vekil bilgileri kısmını eğer internete bağlanmak için vekil bilgilerine 
ihtiyacınız varsa doldurun, aksi durumda boş bırakabilirsiniz. Yüklenme bittikten sonra karşınıza GRUB ekranı kurulumu gelecek. 'GRUB önyükleyici ana önyükleme kaydına (MBR) kurulsun mu?' sorusuna evet diyin ve devam edin. 
Önyükleyicinin kurulacağı aygıt olarak bilgisayarınızın sabit diskini seçin. Yükleme bittikten sonra karşınıza gelen 'Kurulumu bitir' kısmını okuyup devam edin. Son yükleme bitince bilgisayarınızı kapatın,
USB'yi çıkartın ve tekrar çalıştırın. GRUB ekranından yeni işletim sisteminizi seçerek Debian'ın tadını çıkartabilirsiniz.


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/23.PNG)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/24.PNG)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/25.PNG)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/26.PNG)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/27.PNG)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/28.PNG)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/29.jpeg)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/30.jpeg)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/31.PNG)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/32.PNG)


![](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level5/33.PNG)


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
