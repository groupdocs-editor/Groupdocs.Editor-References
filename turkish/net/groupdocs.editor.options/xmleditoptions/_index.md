---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "XML (eXtensible Markup Language) belgelerini düzenlemek ve HTML'ye dönüştürmek için özel seçenekler belirlemenize olanak tanır."
type: docs
weight: 1270
url: /tr/net/groupdocs.editor.options/xmleditoptions/
---
## XmlEditOptions class

XML (eXtensible Markup Language) belgelerini düzenlemek ve HTML'ye dönüştürmek için özel seçenekler belirtmeye olanak tanır

```csharp
public sealed class XmlEditOptions : IEditOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [XmlEditOptions](xmleditoptions)() | Varsayılan yapıcı. |

## Properties

| Name | Açıklama |
| --- | --- |
| [AttributeValuesQuoteType](../../groupdocs.editor.options/xmleditoptions/attributevaluesquotetype) { get; set; } | Özellik değerleri için alıntı tipini (tek veya çift tırnak) belirlemenize olanak tanır. Varsayılan çift tırnaktır. |
| [Encoding](../../groupdocs.editor.options/xmleditoptions/encoding) { get; set; } | Metin belgesinin karakter kodlaması, açılışta uygulanacaktır. Varsayılan olarak null'dır — iç belge kodlaması uygulanır. |
| [FixIncorrectStructure](../../groupdocs.editor.options/xmleditoptions/fixincorrectstructure) { get; set; } | Bozuk XML yapısını düzeltmek için mekanizmayı etkinleştirmenize veya devre dışı bırakmanıza olanak tanır. Varsayılan olarak devredışı bırakılmıştır (false). |
| [FormatOptions](../../groupdocs.editor.options/xmleditoptions/formatoptions) { get; } | HTML'de temsil edildiğinde XML yapısına uygulanacak XML biçimlendirmesini ayarlamaya izin verir. Varsayılan biçimlendirme kullanılır ve ayarlanabilir. Null olamaz. |
| [HighlightOptions](../../groupdocs.editor.options/xmleditoptions/highlightoptions) { get; } | HTML'de temsil edildiğinde XML yapısına uygulanacak XML vurgulamasını ayarlamaya izin verir. Varsayılan vurgulama kullanılır ve ayarlanabilir. Null olamaz. |
| [RecognizeEmails](../../groupdocs.editor.options/xmleditoptions/recognizeemails) { get; set; } | Özellik değerlerinde e-posta adreslerini tanıma algoritmasını etkinleştirmeye izin verir. |
| [RecognizeUris](../../groupdocs.editor.options/xmleditoptions/recognizeuris) { get; set; } | URI tanıma algoritmasını etkinleştirmeye izin verir. |
| [TrimTrailingWhitespaces](../../groupdocs.editor.options/xmleditoptions/trimtrailingwhitespaces) { get; set; } | İç etiket metnindeki sondaki boşlukların kırpılmasını etkinleştirmeye izin verir. Varsayılan olarak devre dışıdır (false) — sondaki boşluklar korunur. |

### Ayrıca Bakınız

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
