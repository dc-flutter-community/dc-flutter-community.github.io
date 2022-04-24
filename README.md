![logo](_media/cover.png ':size=450')

# Developer Challenge Akademi

## Paket Nedir?

Paket; geliştiricilerin Dart/Flutter projelerindeki ihtiyaçlarını karşılamak üzere hazırlanmış açık kaynaklı kod bütünleridir. Paket kullanımı ile projelerinizdeki her ihtiyacı sıfırdan kodlamayarak zaman tasarrufu elde edebiliriz.

Resmi paket dağıtım web adresi olan *pub.dev* üzerinde ihtiyacınız olan paketleri aratabilir, dilerseniz kendiniz de paket oluşturarak ekleyebilirsiniz.

Sizlere bu döküman ile kullanım olsun geliştirme olsun Flutter paket ekosistemine dair herşeyi paylaşmak istiyoruz.
Haydi başlayalım.

## Paket Türleri

Sadece Dart kodlarından oluşan paketleri Dart ve Flutter uygulamalarınızda her platforma destek verecek şekilde kullanabilirsiniz.
> Örneğin [email_validator](https://pub.dev/packages/email_validator) isimli paket teknik olarak bir e-posta adresinin doğruluğunu teyit etme imkanı sunmaktadır.

Bununla beraber bir paket plaforma özgü kod yapısı içeriyorsa o paketlere plugin (eklenti) paketi adı veriyoruz. 

> Örneğin [geolocator](https://pub.dev/packages/geolocator) isimli paket ios cihazlarda konum bilgisine erişebilmek için CLLocationManager ile Swift veya Objective-C dillerini kullanarak etkileşim kurmakmaktadır.
