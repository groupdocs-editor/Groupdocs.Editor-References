---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "WordProcessing belgelerinin desteklenen tüm WordProcessing uyumlu formatları (DOCX, RTF, ODT vb.) düzenlemek için özel seçenekler belirtmeye olanak tanır."
type: docs
weight: 1200
url: /tr/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

DOC(X), RTF, ODT vb. gibi desteklenen tüm WordProcessing (Words uyumlu) formatlarındaki belgeleri düzenlemek için özel seçenekler belirtmeye olanak tanır

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | WordProcessingEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür; tüm seçenekler varsayılan değerlere ayarlanmıştır. |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | Belirtilen sayfalama ile WordProcessingEditOptions sınıfının yeni bir örneğini oluşturur ve döndürür; diğer tüm seçenekler varsayılan olarak ayarlanır. |

## Properties

| Name | Açıklama |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | Dil bilgisinin HTML işaretlemesine 'lang' HTML öznitelikleri şeklinde dışa aktarılıp aktarılmayacağını belirtir. Bu seçenek çok dilli belgelerin çift yönlü dönüşümünde faydalı olabilir. Varsayılan olarak devre dışıdır (false). |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | Ortaya çıkan HTML belgesinde sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir. Varsayılan olarak devre dışıdır (false). |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | Belgenin metin içeriğinde kullanılan yalnızca yazı tipi kaynaklarını çıkarıp çıkarmayacağını gösteren bir değeri alır veya ayarlar. |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | Giriş WordProcessing belgesinde kullanılan yazı tipi kaynaklarını çıkarmaktan sorumludur. Varsayılan olarak hiçbir yazı tipi çıkarmaz (NotExtract). |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | Giriş WordProcessing belgesindeki bir alanı temsil eden her HTML öğesine 'class' özniteliklerine yerleştirilecek bir sınıf adı belirtmeye olanak tanır. Varsayılan olarak NULL'dır - 'class' öznitelikleri uygulanmaz. |
| [UseInlineStyles](../../groupdocs.editor.options/wordprocessingeditoptions/useinlinestyles) { get; set; } | Giriş WordProcessing belgesinin stil ve biçimlendirme verilerinin nerede saklanacağını kontrol eder: harici stil sayfasında (`false`) veya HTML işaretlemesinde satır içi stil olarak (`true`). Varsayılan olarak harici stiller kullanılır (`false`). |

### Ayrıca Bakınız

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
