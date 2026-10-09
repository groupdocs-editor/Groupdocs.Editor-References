---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "ePub, MOBI ve AZW3 dahil olmak üzere tüm desteklenen formatlarda Ebook belgelerini düzenlemek için özel seçenekleri belirtmeye ve ayarlamaya izin verir."
type: docs
weight: 830
url: /tr/net/groupdocs.editor.options/ebookeditoptions/
---
## EbookEditOptions class

Tüm desteklenen formatlarda (ePub, MOBI ve AZW3) E-kitap belgelerini düzenlemek için özel seçenekleri belirtmeye ve ayarlamaya izin verir.

```csharp
public sealed class EbookEditOptions : IEditOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [EbookEditOptions](ebookeditoptions#constructor)() | Tüm seçeneklerin varsayılan değerlere ayarlandığı [`EbookEditOptions`](../ebookeditoptions) sınıfının yeni bir örneğini başlatır |
| [EbookEditOptions](ebookeditoptions#constructor_1)(bool) | Belirtilen sayfalama modu ile [`EbookEditOptions`](../ebookeditoptions) sınıfının yeni bir örneğini başlatır |

## Properties

| Name | Açıklama |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/ebookeditoptions/enablelanguageinformation) { get; set; } | Dil bilgisinin HTML işaretlemesine 'lang' HTML öznitelikleri şeklinde aktarılıp aktarılmayacağını belirtir. Bu seçenek çok dilli belgelerin çift yönlü dönüşümü için faydalı olabilir. Varsayılan olarak devre dışıdır (`false`). |
| [EnablePagination](../../groupdocs.editor.options/ebookeditoptions/enablepagination) { get; set; } | Ortaya çıkan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. Varsayılan olarak devre dışıdır (`false`). |

### Açıklamalar

Desteklenen e-kitap formatları:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Elektronik Yayın)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Kindle Format 8t)

### Ayrıca Bakınız

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
