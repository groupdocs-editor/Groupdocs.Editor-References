---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Ayırıcı (delimiter) kullanan metin tabanlı Elektronik Tablo belgeleri (CSV, Tab tabanlı vb.) oluşturma ve kaydetme seçeneklerini içerir."
type: docs
weight: 820
url: /tr/net/groupdocs.editor.options/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions class

Ayırıcı (delimiter) kullanan metin tabanlı Spreadsheet belgelerini (CSV, Tab-based etc.) oluşturma ve kaydetme seçeneklerini içerir

```csharp
public sealed class DelimitedTextSaveOptions : ISaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor)() | Bu parametresiz yapıcı, varsayılan ayırıcı olarak noktalı virgül (;) kullanılan bir DelimitedTextSaveOptions yeni örneği oluşturur (daha sonra [`Separator`](./separator) özelliği aracılığıyla değiştirilebilir). |
| [DelimitedTextSaveOptions](delimitedtextsaveoptions#constructor_1)(string) | Zorunlu ayırıcı (delimiter) ile ayrılmış metin için seçenek sınıfının bir örneğini oluşturur. |

## Properties

| Name | Açıklama |
| --- | --- |
| [Encoding](../../groupdocs.editor.options/delimitedtextsaveoptions/encoding) { get; set; } | Metin tabanlı Elektronik Tablo belgesi için bir kodlama ayarlamaya izin verir. Varsayılan olarak (ve belirtilmezse) UTF8'dir. |
| [KeepSeparatorsForBlankRow](../../groupdocs.editor.options/delimitedtextsaveoptions/keepseparatorsforblankrow) { get; set; } | Boş satır için ayırıcıların çıktılanıp çıktılanmayacağını gösterir. Varsayılan değer `false` olup, boş satırın içeriğinin boş olacağı anlamına gelir. |
| [Separator](../../groupdocs.editor.options/delimitedtextsaveoptions/separator) { get; set; } | Metin tabanlı Elektronik Tablo belgeleri için bir dize ayırıcı (delimiter) belirtmeye izin verir. |
| [TrimLeadingBlankRowAndColumn](../../groupdocs.editor.options/delimitedtextsaveoptions/trimleadingblankrowandcolumn) { get; set; } | MS Excel'in yaptığı gibi baştaki boş satır ve sütunların kırpılıp kırpılmayacağını gösterir. |

### Açıklamalar

https://en.wikipedia.org/wiki/Delimiter-separated_values

### Ayrıca Bakınız

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
