#Step-by-step

#Yapılacaklar
##1. Debian iso dosyasının indirilmesi
##2. Windows üzerinde Debian iso dosyasını usb belleğe yazdırma
##2.1. Gerekli aracın kurulumu (Pendrive linux)
##3. Windows üzerinde disk bölümlendirme
##4. Usb'den boot etme işlemi için BIOS/UEFI ayarları
##5. Diske Debian kurulumu


# 1 - Debian iso dosyasının indirilmesi


## A - Siteye ulaşma

Kullandığımız arama motoruna "cd image debian" yazarak veya tarayıcımızın 
adres çubuğuna "[cdimage.debian.org/debian-cd](http://cdimage.debian.org/debian-cd/)" 
yazarak isoyu indireceğimiz internet sitesine ulaşabiliriz.

![at](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/1.png)
![kedi](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/2.png)

## B - Dosyaya ulaşma

Önümüze gelen dizinlerden sırasıyla

*current-live/*

*amd64/*

*iso-hybrid/*

Dizinlerinin içine girerek iso dosyalarına ulaşabiliriz.

![dizin1](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/3.png)
![dizin2](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/4.png)
![dizin3](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/5.png)

## C - Dosya seçimi

Buradaki .iso uzantılı iso dosyalarından istediğimizi üzerine tıklayarak 
indirebiliriz.

![liste](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level1/6.png)

# 2 - Windows üzerinde Debian iso dosyasının usb belleğe yazdırılması ve gerekli aracın kurulumu (Pendrivelinux)


## A - Pendrivelinux'u indirmek için internet sitesine ulaşma 

Kullandığımız arama motoruna "pendrivelinux download" yazarak veya internet
tarayıcımızın adres çubuğuna
 "[http://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/](http://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/)" 
yazarak siteye ulaşabiliriz.
![arama](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/2.png)

## B - İndirme ve kurulum 

Sayfanın altında bulunan indirme butonuna bastıktan sonra .exe uzantılı dosyamız inmeye başlayacaktır. İndirme işlemi bittikten sonra dosyayı açın. 
![indirbuton](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/3.png)
![aç](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/5.png)
Karşınıza çıkan lisans sözleşmesini okuduktan sonra 
kabul edin. Birinci adımda usb belleğe koymak istediğiniz linux dağıtımını seçin. İkinci adımda indirmiş olduğunuz iso dosyasını ekleyin. Üçüncü adında usb belleğinizin harfini seçin ve "Create" seçeneğine 
tıklayın. 
![agreement](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/6.png)
![adım1](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/7.png)
![adım2](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/mastehttps://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/11.pngr/level2/8.png)
![adım2.1](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/9.png)
![adım3](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/10.png)
![create](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/11.png)

Karşınıza yapılacak işlemle alakalı bir uyarı çıkacak. Bu uyarı size yapılacak işlemleri ve işlemlerin uygulancağı usb belleği tekrar gösterir. Sizden doğrulamanız istenir. "Evet" seçeneğini
seçtiğiniz taktirde işlem başlar. İşlem bittikten sonra "Close" seçeneğini seçerek pencereyi kapatabilirsiniz. 
![uyarı](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/12.png)
![bekleme1](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/13.png)
![bekleme2](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/15.png)
![kapat](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/16.png)

## C - Sonuç

Bu işlemler sonucunda artık boot edilebilir bir usb belleğe sahip olursunuz.
![sonuç](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level2/17.png)



# 3 - Windows üzerinde disk bölümlendirme

## A - Disk Yönetimine giriş

'Bilgisayarım'a sağ tıklayıp 'yönet'e bastıktan sonra sol taraftaki barda çıkacak olan 'disk yönetimi' seçeneğine basarak disk bölümlendirmesi yapacağımız ekrana ulaşabiliriz.

![sağtık](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/1.png)
![giriş](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/2.png)

## B - Disk bölümlendirme

Öncelikle bilgisayarımızdaki disk bölümlerinden birini küçültmemiz ve kendimize bir disk bölümü açmamız gerekiyor. Öncelikle küçültmek istediğiniz bölümü seçin (Bu genellikle 'C:' olacaktır.). Seçtikten sonra birimin üstüne gelip sağ tıklayın ve 'birimi küçült' seçeneğine tıklayın. Birim sorgulama bittikten sonra küçültmek istediğiniz alan boyutunu MB cinsinden girerek küçült seçeneğine tıklayın.

![birimseç](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/4.png)
![sorgu](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/5.png)
![boyut](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/7.png)

Oluşturduğunuz birimin üzerine gelerek sağ tıklayın ve 'yeni basit birim' seçeneğine tıklayın. Karşınıza 'Yeni Basit Birim Sihirbazı' çıkacak. 'İleri' seçeneğini seçin. Basit birim boyutunu en çok disk alanı kısmında gösterilen alan kadar ayarlayın ve 'İleri' seçeneğine tıklayın. Sürücü harfini seçtikten sonra tekrar 'İleri' seçeneğine tıklayın. Yeni gelecek ekranda hiçbir değişiklik yapmadan 'İleri' seçeneğine  tıklayın ve son olarak gelen sayfada ayarlarınızı tekrar gözden geçirip 'Son' seçeneğine tıklayın.

![disk](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/8.png)
![basit](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/9.png)
![sihirbaz](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/10.png)
![alan](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/11.png)
![harf](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/12.png)
![ileri](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/13.png)
![ileri2](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/14.png)
![son](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/15.png)

## C - Sonuç

Bu işlemler sonucunda artık diskinizde yeni bir birim oluşturmuş olursunuz.

![disk](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level3/16.png)



# 4 - Usb'den boot etme işlemi için BIOS/UEFI ayarları

Öncelikle üzülerek belitmek zorundayım ki BIOS/UEFI ayarları bilgisayarın marka ve modeline göre hem bu ayarlara ulaşım, hem de ayarların yapılışı açısında farklılık göstermektedir. Bu bölümde size yol göstermesi için göstereceğimiz
ekran görüntüleri ile sizin BIOS/UEFI ayarlarınız uyuşmayabilir. Bundan dolayı bu ayarları yapmadan önce internetten bilgisayarınızın marka ve modelini belirterek araştırma yapmanız iyi olacaktır.

## A - BIOS/UEFI ekranına ulaşım ve Boot ayarları

Bilgisayarınızı kapatıp USB'yi takarak tekrar başlatın. Bilgisayarınız açılırken F1-F2-F10-F11-F12 veya DEL tuşuna arka arkaya basın. Karşınıza çıkacak ekranda size menüler arasında geçiş yapmanızı sağlayacak (genellikle sağ ve sol ok
tuşları), seçim yapmanızı sağlayacak (genellikle 'Enter' tuşu) ve değerleri değiştirmenizi sağlayacak (genellikle -/+ tuşları) tuşları gösteren bir kısım göreceksiniz. Bu tuşlar sayesinde Boot ayarlarına ulaşıp bilgisayarınızı boot 
etmek istediğiniz (bizim durumumuzda USB) bileşeni en üste çıkartın. Yaptığınız değişiklikleri kaydedip çıkın.

![bios](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/1.jpeg)

![system](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/2.jpeg)

![order](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/3.jpeg)

![seçim](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/4.jpeg)

![üst](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/5.jpeg)

![çık](https://raw.githubusercontent.com/DoraUzunsoy/Step-by-step/master/level4/6.jpeg)

