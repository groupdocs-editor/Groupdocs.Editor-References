---
title: "TextType"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Desteklenebilir bir metin kaynağı türünü temsil eder"
type: docs
weight: 640
url: /tr/net/groupdocs.editor.htmlcss.resources.textual/texttype/
---
## TextType structure

Desteklenebilir bir metin kaynağı türünü temsil eder

```csharp
public struct TextType : IEquatable<TextType>, IResourceType
```

## Properties

| Name | Açıklama |
| --- | --- |
| static [Css](../../groupdocs.editor.htmlcss.resources.textual/texttype/css) { get; } | Metinsel kaynağın CSS türü |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.textual/texttype/undefined) { get; } | Tanımsız, bilinmeyen veya desteklenmeyen metinsel kaynağı işaretleyen özel değer |
| static [Xml](../../groupdocs.editor.htmlcss.resources.textual/texttype/xml) { get; } | Metinsel kaynağın XML türü |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/fileextension) { get; } | Belirli bir metinsel kaynağın dosya uzantısı (baştaki nokta karakteri olmadan) |
| [FormalName](../../groupdocs.editor.htmlcss.resources.textual/texttype/formalname) { get; } | Bu metinsel kaynak türünün resmi adını döndürür |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/mimecode) { get; } | Belirli bir metinsel kaynak türünün MIME kodu |

## Methods

| Name | Açıklama |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/parsefromfilenamewithextension)(string) | Belirtilen dosya adıyla birlikte uzantıdan veya yalnızca uzantıdan çıkarılan dosya uzantısına eşdeğer TextType değerini döndürür. |
| override [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals_1)(object) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesneyle eşit olup olmadığını belirler; bu nesne muhtemelen başka bir "TextType" örneğidir. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals)(TextType) | Bu örneğin belirtilen "TextType" örneğiyle eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/gethashcode)() | Bu belirli değer türü için sabit bir sayı olan hash kodunu döndürür |
| [operator ==](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_equality) | İki belirli "TextType" örneğinin eşit olup olmadığını tanımlar. |
| [operator !=](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_inequality) | İki belirli "TextType" örneğinin eşit olmama durumunu tanımlar. |

### Ayrıca Bakınız

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
