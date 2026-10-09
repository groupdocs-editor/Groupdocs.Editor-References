---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Birleştirilmiş HTML belgelerinin MHTML MIME kapsüllemesini oluşturmak ve kaydetmek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 1020
url: /tr/net/groupdocs.editor.options/mhtmlsaveoptions/
---
## MhtmlSaveOptions class

MHTML (MIME encapsulation of aggregate HTML documents) belgelerini oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir.

```csharp
public sealed class MhtmlSaveOptions : ISaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [MhtmlSaveOptions](mhtmlsaveoptions)() | Varsayılan yapıcı. |

## Properties

| Name | Açıklama |
| --- | --- |
| [ExportCidUrls](../../groupdocs.editor.options/mhtmlsaveoptions/exportcidurls) { get; set; } | MHTML belgelerinde bulunan kaynakları (görseller, yazı tipleri, CSS) referanslamak için CID (Content-ID) URL'lerinin kullanılıp kullanılmayacağını belirtir. Varsayılan değer `false`. |
| [ExportDocumentProperties](../../groupdocs.editor.options/mhtmlsaveoptions/exportdocumentproperties) { get; set; } | Yerleşik ve özel belge özelliklerinin MHTML'ye dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer `false`. |
| [ExportLanguageInformation](../../groupdocs.editor.options/mhtmlsaveoptions/exportlanguageinformation) { get; set; } | Dil bilgisinin MHTML'ye dışa aktarılıp aktarılmayacağını belirtir. Varsayılan değer `false`. |

### Ayrıca Bakınız

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
