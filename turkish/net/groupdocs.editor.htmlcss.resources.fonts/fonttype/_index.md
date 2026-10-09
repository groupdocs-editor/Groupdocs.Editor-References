---
title: "FontType"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Desteklenen bir yazı tipi türünü temsil eder"
type: docs
weight: 360
url: /tr/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
## FontType structure

Desteklenen bir yazı tipi türünü temsil eder

```csharp
public struct FontType : IEquatable<FontType>, IResourceType
```

## Properties

| Name | Açıklama |
| --- | --- |
| static [Eot](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/eot) { get; } | Bir EOT (Embedded OpenType) yazı tipi türünü temsil eder |
| static [Otf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/otf) { get; } | Bir OTF (OpenType Font) yazı tipi türünü temsil eder |
| static [Ttc](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttc) { get; } | Bir TrueType Collection (TTC) yazı tipini temsil eder |
| static [Ttf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttf) { get; } | Bir TTF (TrueType Font) yazı tipi türünü temsil eder |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/undefined) { get; } | Tanımsız, bilinmeyen veya desteklenmeyen yazı tipi kaynağını işaret eden özel değer |
| static [Woff](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff) { get; } | Bir WOFF (Web Open Font Format) yazı tipi türünü temsil eder |
| static [Woff2](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff2) { get; } | WOFF2 (Web Open Font Format version 2) font tipini temsil eder |
| [CssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/cssname) { get; } | Bu font tipinin @font-face at-rule'unda kullanılan CSS uyumlu adını döndürür |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fileextension) { get; } | Bu font tipi için dosya adı uzantısı (nokta karakteri olmadan) |
| [FontFormat](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fontformat) { get; } | @font-face formatı için font biçimi |
| [FormalName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/formalname) { get; } | Bu font tipinin resmi adını döndürür |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/mimecode) { get; } | Belirli bir font tipinin MIME kodu |

## Methods

| Name | Açıklama |
| --- | --- |
| static [GetFirstDefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined)(params FontType[]) | Belirtilen kümeden "Undefined" olmayan ilk font tipini döndürür, aksi takdirde (tüm öğeler "Undefined" olduğunda) "Undefined" font tipini döndürür |
| static [ParseFromCssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromcssname)(string) | Belirtilen font tipinin CSS uyumlu adının eşdeğeri olan FontType değerini döndürür |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromfilenamewithextension)(string) | Belirtilen dosya adından çıkarılan dosya adı uzantısının eşdeğeri olan FontType değerini döndürür |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefrommime)(string) | Belirtilen MIME kodunun eşdeğeri olan FontType değerini döndürür |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals)(FontType) | Bu örneğin belirtilen "FontType" örneğiyle eşit olup olmadığını belirler |
| override [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals_1)(object) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesneyle (muhtemelen başka bir "FontType" örneği) eşit olup olmadığını belirler |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/gethashcode)() | Bu belirli değer türü için sabit bir sayı olan hash kodunu döndürür |
| [operator ==](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_equality) | İki "FontType" değerinin eşit olup olmadığını kontrol eder |
| [operator !=](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_inequality) | İki "FontType" değerinin eşit olmamasını kontrol eder |

### Ayrıca Bakınız

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
