---
title: "XmlText"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "XML olan bir metin kaynağını temsil eder."
type: docs
weight: 650
url: /tr/net/groupdocs.editor.htmlcss.resources.textual/xmltext/
---
## XmlText class

XML olan bir metin kaynağını temsil eder.

```csharp
public sealed class XmlText : TextResourceBase
```

## Properties

| Name | Açıklama |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | Bu metin kaynağının içeriğini orijinal kodlamasıyla bayt akışı olarak döndürür. |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | Bu metin kaynağının kodlamasını döndürür. Genellikle UTF-8 döndürür. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | Bu metin kaynağının ad ve uzantıdan oluşan doğru dosya adını döndürür. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | Bu metin kaynağının atılmış (disposed) olup olmadığını belirler. |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | Bu metin kaynağının dosya uzantısı olmadan adını döndürür. |
| [ParsedDocument](../../groupdocs.editor.htmlcss.resources.textual/xmltext/parseddocument) { get; } | Bu XML kaynağından bir "XmlDocument" döndürür. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | Bu metin kaynağının içeriğini standart bir dize olarak döndürür. |
| override [Type](../../groupdocs.editor.htmlcss.resources.textual/xmltext/type) { get; } | TextType.Xml değerini döndürür. |

## Methods

| Name | Açıklama |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | Bu metin kaynağını atar, içeriğini serbest bırakır ve çoğu yöntem ve özelliği çalışmaz hâle getirir. Birden çok çağrıya toleranslıdır. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals)(IHtmlResource) | Bu örneği belirtilen eşitlik üzerinde kontrol eder. |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | Bu metin kaynağını belirtilen dosyaya kaydeder. |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | Bu metin kaynağı atıldığında gerçekleşen olay. |

### Ayrıca Bakınız

* class [TextResourceBase](../textresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
