---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "İkili Spreadsheet Cells Excel uyumlu belgeleri (XLSX, ODS vb.) Editor sınıfına yüklemek için seçenekler içerir"
type: docs
weight: 1120
url: /tr/net/groupdocs.editor.options/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

XLS(X), ODS vb. gibi ikili Elektronik Tablo (Cells, Excel uyumlu) belgelerini Editor sınıfına yükleme seçeneklerini içerir.

```csharp
public sealed class SpreadsheetLoadOptions : ILoadOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Varsayılan parametresiz yapıcı - tüm parametrelerin varsayılan değerleri vardır |

## Properties

| Name | Açıklama |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/spreadsheetloadoptions/optimizememoryusage) { get; set; } | Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir; bu, bazı özel durumlarda performansı düşürebilir, ancak diğer yandan bellek kullanımını azaltır. Büyük belgeler işlenirken ve OutOfMemoryException ile karşılaşıldığında faydalıdır. Varsayılan değer false'tur (daha iyi performans için bellek optimizasyonu devre dışı bırakılmıştır). |
| [Password](../../groupdocs.editor.options/spreadsheetloadoptions/password) { get; set; } | Şifreyi belirtmenizi, değiştirmenizi ve almanızı sağlar; bu şifre, Spreadsheet belgesi şifrelenmişse açmak için kullanılır. Şifreyi kullanmamak için NULL veya boş dize olarak ayarlayın (varsayılan değer). |

### Ayrıca Bakınız

* interface [ILoadOptions](../iloadoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
