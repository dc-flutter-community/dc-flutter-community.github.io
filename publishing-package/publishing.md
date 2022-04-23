## Paketimizi Yayınlama İşlemleri

<font size="4">Paketimizi yayınlamadan önce dosyalarımızı GitHub gibi bulut tabanlı bir platform üzerine yüklememiz paketin güncellenmesi ve diğer geliştiriciler tarafından desteklenmesine katkı sağlayacaktır. Şimdi ise GitHub'a nasıl yükleme işlemi gerçekleştirilir onu inceleyeceğiz. 
GitHub anasayfasının sol üstünde bulunan **New** butonuna basıyoruz.</font>


<p align="center">
  <img src="https://user-images.githubusercontent.com/61869567/164947818-2f079515-6af2-4bbc-87f9-d6d156062fec.png"/>
</p>

<font size="4">Ardından açılan ekranda **Repository Name** adlı bölüme paketimizin ismini yazıyoruz ve aşağıdan **Public** seçeneğini işaretliyoruz. Ardından **Create Repository** diyerek projemizi boş repomuzu oluşturuyoruz. Dilerseniz paketinizin sadece organizasyonunuza özel olmasını istiyorsanız **Private** seçeneğini seçebilirsiniz.</font>

<p align="center">
  <img src="https://user-images.githubusercontent.com/61869567/164948019-8b2d8084-f136-459a-afd7-b3cc7184245f.png"  width="600"/>
</p>


<font size="4">Ardından açılan ekranda verilen komutları kullandığımız IDE'nin terminal kısmına sırasıyla yazıyoruz ve artık paket dosyalarımızı GitHub'a yüklemiş bulunuyoruz.</font>


<p align="center">
  <img src="https://user-images.githubusercontent.com/61869567/164948055-071e5c76-9404-44a5-8506-0bdae580e52b.png" width="600"/>
</p>

<font size="4">Artık paketimizi yayınlama işlemlerine başlama vakti geldi. İlk olarak aşağıdaki komutu terminalimize yazıyoruz.</font>

```
flutter pub publish --dry-run
```

<font size="4">Bu komutun amacı paketimizi yayınlamadan önce herhangi bir hata veya eksik bir şey olup olmadığını kontrol etmektir. Eğer herhangi bir hata ile karşılaşmadıysak paketimiz artık yayınlamaya hazır durumdadır.
Son olarak girmemiz gereken ve artık paketimizin pub.dev'e yüklenmesini sağlayacak komut ise şu şekildedir:</font>


```
flutter pub publish
```

<font size="4">Komutumuzu yazdıktan sonra şu şekilde bir seçenek ile karşılaşacağız:</font>

<p align="center">
  <img src="https://user-images.githubusercontent.com/61869567/164948109-2cee5352-5674-4297-ac4b-f0d497de33af.png" width="500"/>
</p>


<font size="4">Bu kısımda "Y" tuşuna bastıktan sonra paketimizi yayınlama işlemi artık tamamen bitmiş olacak.
Bir süre geçtikten sonra artık **pub.dev** üzerinde yayınlanmış olan paketimizi görüntüleyebiliriz.</font>
















