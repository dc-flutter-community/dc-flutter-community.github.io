## Dosya Yolu Üzerinden Paket Kullanımı

<font size="4">Paketler, pub.dev'de yayınlanmasa bile kullanılabilir. Özel eklentiler veya yayınlanmaya hazır olmayan paketler için kullanım seçenekleri mevcuttur. Bunlardan biri de dosya yolu üzerinden paket kullanımıdır. Burada dosya yolu üzerinden paket kullanımının en yaygın sebebi, oluşturduğumuz paketimizin sadece kişisel veya çalıştığımız şirket gibi özel alanlarda kullanımıdır. Burada bahsettiğimiz en yaygın olan kullanım şeklidir fakat bunun dışında birçok sebep elbette mevcuttur.

Kullanımı ise şu şekildedir: 

Örnek olarak **plugin1** adlı bir paketimiz olsun. Bu paketimizi dosya yolu üzerinden kullanabilmemiz için *pubspec.yaml* dosyamıza aşağıdaki şekilde dosya yolumuzu vermemiz gerekmektedir:

```
dependencies:
  plugin1:
    path: ../plugin1/
```

Artık paketimiz kullanıma hazır durumdadır.</font>