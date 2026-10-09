---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "PDF gibi raster görüntü formatlarını hariç tutan fixedlayout fixedpage belge formatlarını temsil eder."
type: docs
weight: 100
url: /tr/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats class

PDF gibi sabit düzen (sabit sayfa) belge formatlarını temsil eder, raster görüntü formatlarını hariç tutar.

```csharp
public class FixedLayoutFormats : DocumentFormatBase
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Belge formatının dosya uzantısını alır. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Belge formatının ait olduğu format ailesini alır. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Format ailesinin benzersiz tanımlayıcısını alır. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Belge formatının MIME tipini alır. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Format ailesinin adını alır. |
| static [All](../../groupdocs.editor.formats/fixedlayoutformats/all) { get; } | Mevcut tüm [`FixedLayoutFormats`](../fixedlayoutformats) örneklerini alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Belirtilen dosya uzantısıyla eşleşen bir [`FixedLayoutFormats`](../fixedlayoutformats) örneğini getirir. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bu örneğin belirtilen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bu örneğin belirtilen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) örneğiyle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bu örneğin belirtilen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) örneğiyle eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Geçerli nesne için bir karma kod (hash code) döndürür. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit) | Bir dosya uzantısı dizesini açıkça bir [`FixedLayoutFormats`](../fixedlayoutformats) örneğine dönüştürür. |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Adobe tarafından tanıtılan Taşınabilir Belge Formatı (PDF), yazılım, donanım ve işletim sistemlerinden bağımsız olarak belgelerin standart bir temsilini sağlar. Daha fazla ayrıntı için: [PDF dosya formatı](https://docs.fileformat.com/pdf/). |

### Açıklamalar

Sabit düzen formatları, içeriğin her sayfada yerleşimini ve işlenmesini kesin olarak belirler. Adobe Acrobat ve Adobe InDesign gibi belge görüntüleme, yayınlama veya düzenleme uygulamalarında yaygın olarak kullanılır. Bu formatlar, sayfa düzenlerini ve içerik konumlandırmasını dahili olarak vektör grafikleri ve metin talimatlarıyla tanımlar.

### Ayrıca Bakınız

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
