---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "EditableDocument../groupdocs.editor/editabledocument örneğini HTML formatında kaydetmek için özel seçenekler belirtmeye izin verir."
type: docs
weight: 900
url: /tr/net/groupdocs.editor.options/htmlsaveoptions/
---
## HtmlSaveOptions class

[`EditableDocument`](../../groupdocs.editor/editabledocument) örneğini HTML formatında kaydetmek için özel seçenekler belirtmeye izin verir.

```csharp
public sealed class HtmlSaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions)() | Varsayılan yapıcı. |

## Properties

| Name | Açıklama |
| --- | --- |
| [AttributeValueDelimiter](../../groupdocs.editor.options/htmlsaveoptions/attributevaluedelimiter) { get; set; } | HTML öğelerindeki öznitelik değerlerinin etrafında hangi ayırıcıların kullanılacağını kontrol eder: tek tırnak (varsayılan değer) veya çift tırnak. |
| [EmbedStylesheetsIntoMarkup](../../groupdocs.editor.options/htmlsaveoptions/embedstylesheetsintomarkup) { get; set; } | CSS stil sayfası(ları) nereye depolanacağını kontrol eder: dış kaynaklar olarak (`false`) veya HTML işaretlemesine, HTML-&gt;HEAD bölümündeki STYLE öğesi içinde gömülmüş olarak (`true`). |
| [HtmlTagCase](../../groupdocs.editor.options/htmlsaveoptions/htmltagcase) { get; set; } | HTML etiket adlarının HTML işaretlemesinde nasıl görüneceğini kontrol eder: Tümü küçük harf (varsayılan değer), Tümü büyük harf veya İlk harf büyük. |
| [SavingCallback](../../groupdocs.editor.options/htmlsaveoptions/savingcallback) { get; set; } | Tüm dış HTML kaynaklarını kaydetmek için son kullanıcı tarafından uygulanması gereken arayüz. Bu özellik **must** `null` olmamalıdır, aksi takdirde GroupDocs.Editor, [`EditableDocument`](../../groupdocs.editor/editabledocument) HTML formatında kaydedilirken bir istisna fırlatır. |

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
