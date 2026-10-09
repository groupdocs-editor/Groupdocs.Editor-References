---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Düz metin TXT belgeleri oluşturmak ve kaydetmek için özel seçenekler belirtmeye izin verir."
type: docs
weight: 1170
url: /tr/net/groupdocs.editor.options/textsaveoptions/
---
## TextSaveOptions class

Düz metin (TXT) belgelerini oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir.

```csharp
public sealed class TextSaveOptions : ISaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [TextSaveOptions](textsaveoptions)() | Varsayılan yapıcı. |

## Properties

| Name | Açıklama |
| --- | --- |
| [AddBidiMarks](../../groupdocs.editor.options/textsaveoptions/addbidimarks) { get; set; } | Düz metin formatında dışa aktarırken her BiDi çalıştırmasından önce çift yönlü işaretlerin eklenip eklenmeyeceğini belirtir. Varsayılan değer 'false' — BiDi işaretleri eklenmez. |
| [Encoding](../../groupdocs.editor.options/textsaveoptions/encoding) { get; set; } | Metin belgesinin kaydedilirken uygulanacak karakter kodlaması. |
| [PreserveTableLayout](../../groupdocs.editor.options/textsaveoptions/preservetablelayout) { get; set; } | Programın düz metin formatında kaydederken tabloların düzenini korumaya çalışıp çalışmayacağını belirtir. Varsayılan değer false. |

### Ayrıca Bakınız

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
