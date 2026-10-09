---
title: "TextEditOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Düz metin TXT belgelerinin yüklenmesi için özelleştirilmiş seçenekler belirtmeye izin verir."
type: docs
weight: 1150
url: /tr/net/groupdocs.editor.options/texteditoptions/
---
## TextEditOptions class

Düz metin (TXT) belgelerini yüklemek için özel seçenekleri belirtmeye izin verir.

```csharp
public class TextEditOptions : IEditOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [TextEditOptions](texteditoptions)() | Varsayılan yapıcı. |

## Properties

| Name | Açıklama |
| --- | --- |
| [Direction](../../groupdocs.editor.options/texteditoptions/direction) { get; set; } | Giriş düz metin belgesindeki metin akış yönünü belirtmeye izin verir. Varsayılan olarak Soldan Sağa'dır. |
| [EnablePagination](../../groupdocs.editor.options/texteditoptions/enablepagination) { get; set; } | Ortaya çıkan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. Varsayılan olarak devre dışıdır (false). |
| [Encoding](../../groupdocs.editor.options/texteditoptions/encoding) { get; set; } | Metin belgesinin açılmasında uygulanacak karakter kodlaması |
| [LeadingSpaces](../../groupdocs.editor.options/texteditoptions/leadingspaces) { get; set; } | Ön boşluk işleme için tercih edilen seçeneği alır veya ayarlar. Varsayılan olarak ön boşlukları sol girintiye dönüştürür. |
| [RecognizeLists](../../groupdocs.editor.options/texteditoptions/recognizelists) { get; set; } | Belge düz metin formatından içe aktarıldığında numaralı liste öğelerinin nasıl tanınacağını belirtmeye izin verir. Varsayılan değer doğrudur (true). |
| [TrailingSpaces](../../groupdocs.editor.options/texteditoptions/trailingspaces) { get; set; } | Son boşluk işleme için tercih edilen seçeneği alır veya ayarlar. Varsayılan olarak tüm son boşlukları kırpar. |

### Ayrıca Bakınız

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
