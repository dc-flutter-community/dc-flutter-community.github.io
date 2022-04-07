## Git Üzerinden Paket Kullanımı 

<font size="4">Bazı paketler pub.dev üzerinde yayınlanmamış olsa bile açık kaynak olarak GitHub üzerinde mevcuttur. Bu tür durumlarda kullanmak istediğimiz paketi GitHub üzerinden projemize entegre ederek kullanabiliriz. 

Kullanımı ise şu şekildedir.

Örnek olarak GitHub üzerinde **plugin1** adlı bir paket olsun. Bu paketi Git üzerinden çekip kullanabilmemiz için *pubspec.yaml* dosyamıza aşağıdaki kod bloğumuzu eklememiz gerekmektedir:

``` 
dependencies:
  plugin1:
    git:
      url: git://github.com/flutter/plugin1.git
```

Artık Git üzerinden çektiğimiz paketimiz kullanıma hazır durumdadır.</font>