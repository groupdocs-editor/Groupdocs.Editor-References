---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belgeyi desteklenen tüm eKitap formatları (ePub, MOBI ve AZW3) içinde oluşturmak ve kaydetmek için özelleştirilmiş seçenekler belirtmeye izin verir."
type: docs
weight: 840
url: /tr/net/groupdocs.editor.options/ebooksaveoptions/
---
## EbookSaveOptions class

Tüm desteklenen e-Kitap formatlarında (ePub, MOBI ve AZW3) belge oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir.

```csharp
public sealed class EbookSaveOptions : ISaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [EbookSaveOptions](ebooksaveoptions#constructor)() | Parametresiz bu yapıcı, ePub çıktı formatına sahip yeni bir EbookSaveOptions örneği oluşturur (daha sonra [`OutputFormat`](./outputformat) özelliğiyle değiştirilebilir). |
| [EbookSaveOptions](ebooksaveoptions#constructor_1)(EBookFormats) | Belirtilen zorunlu e-Kitap çıktı formatı ile [`EbookSaveOptions`](../ebooksaveoptions) sınıfının yeni bir örneğini oluşturur, diğer tüm parametreler varsayılandır. |

## Properties

| Name | Açıklama |
| --- | --- |
| [ExportDocumentProperties](../../groupdocs.editor.options/ebooksaveoptions/exportdocumentproperties) { get; set; } | Sonuç dosyasında yerleşik ve özel belge özelliklerinin dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer `false`. |
| [OutputFormat](../../groupdocs.editor.options/ebooksaveoptions/outputformat) { get; set; } | Sonuç e-Kitap dosyasının formatını belirtir: IDPF ePub, MOBI veya AZW3. |
| [SplitHeadingLevel](../../groupdocs.editor.options/ebooksaveoptions/splitheadinglevel) { get; set; } | e-Kitap dosyasının bölüneceği en yüksek başlık seviyesini belirtir. Varsayılan değer `2`'dir. `0` olarak ayarlandığında bölme devre dışı bırakılır, böylece e-Kitap içeriğinin tamamı sonuç dosyasında tek bir paket içinde birleştirilir. |

### Açıklamalar

Desteklenen e-kitap formatları:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Elektronik Yayın)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Kindle Format 8t)

### Ayrıca Bakınız

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
