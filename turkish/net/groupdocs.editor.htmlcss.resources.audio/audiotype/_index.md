---
title: "AudioType"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Desteklenebilir bir ses türü biçimini temsil eder"
type: docs
weight: 320
url: /tr/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

Desteklenebilir bir ses türünü (formatını) temsil eder

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## Properties

| Name | Açıklama |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | MPEG-1 Audio Layer III ses biçimini temsil eder |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | Tanımsız, bilinmeyen veya desteklenmeyen ses biçimini işaretleyen özel değer |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | Bu ses biçimi için dosya uzantısı (nokta karakteri olmadan) |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | Bu ses biçiminin resmi adı |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | Bu ses biçimi için MIME kodu |

## Methods

| Name | Açıklama |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | Belirtilen dosya adından çıkarılan dosya uzantısına eşdeğer AudioType değerini döndürür |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | Bu örneğin belirtilen "AudioType" örneğiyle eşit olup olmadığını belirler |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | Bu örneğin belirtilen tip dönüştürülmemiş nesneyle eşit olup olmadığını belirler; bu nesne muhtemelen başka bir "AudioType" örneğidir |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | Bu belirli değer türü için sabit bir sayı olan hash kodunu döndürür |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | İki "AudioType" değerinin eşit olup olmadığını kontrol eder |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | İki "AudioType" değerinin eşit olmamasını kontrol eder |

### Ayrıca Bakınız

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
