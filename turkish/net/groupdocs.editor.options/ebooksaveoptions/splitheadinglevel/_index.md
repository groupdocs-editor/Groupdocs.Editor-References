---
title: "SplitHeadingLevel"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "eKitap dosyasının bölüneceği en yüksek başlık seviyesini belirtir. Varsayılan değer 2'dir. 0 olarak ayarlandığında bölme devre dışı bırakılır ve eKitabın tüm içeriği sonuç dosyasında tek bir paket içinde birleştirilir."
type: docs
weight: 40
url: /tr/net/groupdocs.editor.options/ebooksaveoptions/splitheadinglevel/
---
## EbookSaveOptions.SplitHeadingLevel property

e-Kitap dosyasının bölüneceği en yüksek başlık seviyesini belirtir. Varsayılan değer `2`'dir. `0` olarak ayarlandığında bölme devre dışı bırakılır, böylece e-Kitap içeriğinin tamamı sonuç dosyasında tek bir paket içinde birleştirilir.

```csharp
public int SplitHeadingLevel { get; set; }
```

### Açıklamalar

Bu özellik 1 ile 9 arasında bir değere ayarlandığında, belge belirtilen başlık seviyesine kadar **Heading 1**, **Heading 2**, **Heading 3** vb. stilleriyle biçimlendirilmiş paragraflarda bölünür.

Varsayılan olarak, yalnızca **Heading 1** ve **Heading 2** paragrafları belgenin bölünmesine neden olur. Bu özelliği sıfıra (veya sıfırdan daha düşük bir değere) ayarlamak, belgenin başlık paragraflarında hiç bölünmemesini sağlar.

### Ayrıca Bakınız

* class [EbookSaveOptions](../../ebooksaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
