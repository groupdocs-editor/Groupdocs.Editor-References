---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Ayırıcı kullanan metin tabanlı Spreadsheet belgelerini (CSV, Tab tabanlı vb.) yüklemek için seçenekler"
type: docs
weight: 810
url: /tr/net/groupdocs.editor.options/delimitedtexteditoptions/
---
## DelimitedTextEditOptions class

Ayırıcı (delimiter) kullanan metin tabanlı Spreadsheet belgelerini (CSV, Tab-based etc.) yükleme seçenekleri

```csharp
public sealed class DelimitedTextEditOptions : IEditOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [DelimitedTextEditOptions](delimitedtexteditoptions)(string) | Zorunlu ayırıcı (delimiter) ile ayrılmış metin için seçenek sınıfının bir örneğini oluşturur. |

## Properties

| Name | Açıklama |
| --- | --- |
| [ConvertDateTimeData](../../groupdocs.editor.options/delimitedtexteditoptions/convertdatetimedata) { get; set; } | Metin tabanlı belgede bulunan dizgenin tarih verisine dönüştürülüp dönüştürülmeyeceğini gösteren bir değeri alır veya ayarlar. Varsayılan değer `false`'tır. |
| [ConvertNumericData](../../groupdocs.editor.options/delimitedtexteditoptions/convertnumericdata) { get; set; } | Metin tabanlı belgede bulunan dizgenin sayısal veriye dönüştürülüp dönüştürülmeyeceğini gösteren bir değeri alır veya ayarlar. Varsayılan değer `false`'tır. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/delimitedtexteditoptions/optimizememoryusage) { get; set; } | Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir; bu, bazı özel durumlarda performansı düşürebilir, ancak diğer yandan bellek kullanımını azaltır. Büyük belgeler işlenirken ve OutOfMemoryException ile karşılaşıldığında faydalıdır. Varsayılan değer `false`'tır (daha iyi performans için bellek optimizasyonu devre dışı bırakılmıştır). |
| [Separator](../../groupdocs.editor.options/delimitedtexteditoptions/separator) { get; set; } | Metin tabanlı Elektronik Tablo belgeleri için bir dize ayırıcı (delimiter) belirtmeye izin verir. |
| [TreatConsecutiveDelimitersAsOne](../../groupdocs.editor.options/delimitedtexteditoptions/treatconsecutivedelimitersasone) { get; set; } | Ardışık ayırıcıların tek bir ayırıcı olarak ele alınıp alınmayacağını tanımlar. Varsayılan değer `false`'tır. |

### Açıklamalar

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Ayrıca Bakınız

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
