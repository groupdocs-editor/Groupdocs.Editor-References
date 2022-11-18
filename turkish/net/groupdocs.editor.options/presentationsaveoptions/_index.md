---
title: PresentationSaveOptions
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Sunum PowerPoint uyumlu belgeleri oluşturmak ve kaydetmek için özel seçenekleri belirlemeye izin verir
type: docs
weight: 880
url: /tr/net/groupdocs.editor.options/presentationsaveoptions/
---
## PresentationSaveOptions class

Sunum (PowerPoint uyumlu) belgeleri oluşturmak ve kaydetmek için özel seçenekleri belirlemeye izin verir

```csharp
public sealed class PresentationSaveOptions : ISaveOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions)(PresentationFormats) | Diğer tüm parametreler default iken, belirtilen zorunlu Sunum çıktı biçimiyle yeni bir PresentationSaveOptions örneği oluşturur |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [InsertAsNewSlide](../../groupdocs.editor.options/presentationsaveoptions/insertasnewslide) { get; set; } | Düzenlenen slaydın orijinal sunumdaki mevcut slaydın, konum tarafından belirtilen konumda değiştirilip değiştirilmeyeceğini belirten Boole bayrağı[`SlideNumber`](./slidenumber) özelliğini değiştirin veya içeriği değiştirilmeden mevcut slayt ile önceki slayt arasına enjekte edilmelidir. Varsayılan olarak yanlıştır — mevcut slayt değiştirilecektir. değeri ise bu özellik göz ardı edilir.[`SlideNumber`](./slidenumber) özellik '0' olarak ayarlandı. |
| [OutputFormat](../../groupdocs.editor.options/presentationsaveoptions/outputformat) { get; set; } | Belgeyi kaydetmek için kullanılacak bir Sunum formatı belirtmeye izin verir |
| [Password](../../groupdocs.editor.options/presentationsaveoptions/password) { get; set; } | Ortaya çıkan Sunum belgesini kodlamak için kullanılacak olan parolanın belirlenmesine, değiştirilmesine ve alınmasına izin verir. Varsayılan olarak NULL'dur - parola ayarlanmayacaktır. Daha önce ayarlanmışsa parolayı kaldırmak için NULL veya boş dize olarak ayarlayın. |
| [SlideNumber](../../groupdocs.editor.options/presentationsaveoptions/slidenumber) { get; set; } | Yeni bir tek slaytlı sunum oluşturmak yerine (varsayılan davranış) mevcut sunuma düzenlenmiş slaytın eklenmesine izin verir. 0 (varsayılan değer) ise, yeni sunum tek düzenlenmiş slaytla oluşturulacaktır. Sıfırdan büyük veya küçükse ve Editor sınıfına yüklenmiş geçerli bir sunum varsa, EditableDocument girişi örneğinde saklanan düzenlenen slayt bu sunuma eklenir. |

### Notlar

Bu sınıfın örneği şuraya geçirilmelidir:[`Save`](../../groupdocs.editor/editor/save)düzenlenmiş sunuyu bazı Sunuma özel formattaki son belgeye kaydetmek için kullanılan bir yöntem. Oluşturucusunun bir zorunlu parametresi vardır - çıktı Sunumunun biçimi. Diğer tüm parametreler isteğe bağlıdır ve atlanabilir.

### Ayrıca bakınız

* interface [ISaveOptions](../isaveoptions)
* ad alanı [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->