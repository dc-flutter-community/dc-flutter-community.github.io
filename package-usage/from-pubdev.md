## Pub.dev Üzerinden Paket Kullanımı 

<font size="4">Öncelikle pub.dev'in ne olduğundan bahsedelim.
Pub.dev; Flutter ve Dart paketlerinin yer aldığı açık kaynak bir platformdur. Geliştirdiğimiz paketlerimizi burada insanlarla paylaşabilir ve onlarında kullanımına sunabiliriz. Şimdi ise pub.dev üzerinden paket kullanımını inceleyelim.

Paketimizin eğer proje kullanıma sunulduktan sonra dahi kullanılmasını istiyorsak aşağıdaki şekilde terminal kısmına kod bloğumuzu ekliyoruz:

``` 
flutter pub add <package-name>
```

Paketimizin sadece geliştirme aşamasında kullanılmasını ve kullanıcıya sunulmamasını istiyorsak bu şekilde terminal kısmına kodumuzu yazıyoruz:

``` 
flutter pub add -d <package-name>
```

Bu şekilde paketi projemize ekledikten sonra artık istediğimiz yerde kullanabiliriz.</font>