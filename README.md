![logo](_media/cover.png ':size=450')

# Developer Challenge Akademi

## Paket Nedir?

Paket; geliştiricilerin Dart/Flutter projelerindeki ihtiyaçlarını karşılamak üzere hazırlanmış açık kaynaklı kod bütünleridir. Paket kullanımı ile projelerinizdeki her ihtiyacı sıfırdan kodlamayarak zaman tasarrufu elde edebiliriz.

Resmi paket dağıtım web adresi olan *pub.dev* üzerinde ihtiyacınız olan paketleri aratabilir, dilerseniz kendiniz de paket oluşturarak ekleyebilirsiniz.

Sizlere bu döküman ile kullanım olsun geliştirme olsun Flutter paket ekosistemine dair herşeyi paylaşmak istiyoruz.
Haydi başlayalım.

## Plugin (Eklenti) Paketi Nedir?

Sadece Dart kodlarından oluşan paketleri Dart ve Flutter uygulamalarınızda her platforma destek verecek şekilde kullanabilirsiniz. Bununla beraber bir paket plaforma özgü kod yapısı içeriyorsa o paketlere plugin (eklenti) paketi adı veriyoruz. 

Örnekler:

_**Dart Paketi**: [email_validator](https://pub.dev/packages/email_validator) isimli paket teknik olarak bir e-posta adresinin doğruluğunu teyit etme imkanı sunmakta olup tüm Dart ve Flutter uygulamalarında kullanılabilir._

_**Flutter Paketi**: [infinite_scroll_pagination](https://pub.dev/packages/infinite_scroll_pagination) isimli paket arayüz ile sayfalama işlevi sağladığından sadece Flutter uygulamalarında kullanılabilir._

_**Plugin Paketi**: [geolocator](https://pub.dev/packages/geolocator) isimli paket çalıştığı cihazın konu bilgisini dart kodları tarafından erişilebilir kılmaya olanağı sunmaktadır. Android, iOS, MacOS, Web, Windows platformlarını desteklediği için, o platformlara özgü kod yapıları içermektedir. Örneğin iOS için CLLocationManager ile Swift veya Objective-C dillerini kullanarak etkileşim kurmakmaktadır._
