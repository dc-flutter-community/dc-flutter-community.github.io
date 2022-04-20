## PUBSPEC.YAML 

<font size="4">**pubspec.yaml** dosyamız ise bizim için en önemli kısım diyebiliriz. Bu kısımda paketimizin isim, açıklama, versiyon gibi önemli bilgilerini tutuyoruz. Örnek olarak ele alacağımız "**circular_textfield**" adlı paketin pubspec.yaml dosyası şu şekildedir:</font>

```
name: circular_textfield
description: A circular textfield widget for your apps. This widget makes our TextField come as circular by default. We can also add the icon we want with the icon parameter.
version: 0.0.4
homepage: https://github.com/ilyashyrt/
repository: https://github.com/ilyashyrt/circular_textfield/
documentation: https://github.com/ilyashyrt/circular_textfield/


environment:
  sdk: ">=2.16.1 <3.0.0"
  flutter: ">=1.17.0"

dependencies:
  flutter:
    sdk: flutter

dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_lints: ^1.0.0


flutter:
```

- <font size="4">**name:** Paket ismi,
- **description:** Paketin içeriğini anlatan açıklama kısmı,
- **version:** Paketin yayınlanan son versiyonu,
- **homepage:** GitHub profili,
- **repository:** Paketin GitHub  linki,
- **documentation:** Son olarak yine repository kısmı ile aynı şekilde paketin GitHub linki yer alması gerekiyor.</font>


<font size="4">Flutter Uygulama Projesine göre **pubspec.yaml** dosyamızın içeriği biraz daha farklıdır ve düzenlememiz gereken alanlar vardır. Diğer kısımlarda ise herhangi bir değişiklik yapmamız gerekmemektedir.</font>