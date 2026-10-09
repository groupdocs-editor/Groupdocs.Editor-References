---
title: "IHtmlResource"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Bilinmeyen HTML kaynağının raster veya vektör görüntü, stil sayfası, yazı tipi, metin kaynağı, CSS, XML, ses vb. bir örneğini temsil eder."
type: docs
weight: 430
url: /tr/net/groupdocs.editor.htmlcss.resources/ihtmlresource/
---
## IHtmlResource interface

Bilinmeyen HTML kaynağının (raster veya vektör görüntü, stil sayfası, yazı tipi, metin kaynağı (CSS, XML), ses vb.) bir örneğini temsil eder

```csharp
public interface IHtmlResource : IAuxDisposable, IEquatable<IHtmlResource>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/bytecontent) { get; } | HTML kaynağının içeriği bayt akışı biçiminde |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) { get; } | Belirtilen kaynağın uygun dosya uzantısıyla doğru dosya adı |
| [Name](../../groupdocs.editor.htmlcss.resources/ihtmlresource/name) { get; } | HTML kaynağının adı |
| [TextContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/textcontent) { get; } | HTML kaynağının içeriği, ikili kaynaklar için base64 kodlu metin dizesi biçiminde veya metin kaynakları için basit metin biçiminde |
| [Type](../../groupdocs.editor.htmlcss.resources/ihtmlresource/type) { get; } | HTML kaynağının türü |

## Methods

| Name | Açıklama |
| --- | --- |
| [Save](../../groupdocs.editor.htmlcss.resources/ihtmlresource/save)(string) | Mevcut kaynağı belirtilen dosyaya kaydeder |

### Ayrıca Bakınız

* interface [IAuxDisposable](../iauxdisposable)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
