---
title: "EotFont"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "EOT Embedded OpenType formatında bir yazı tipini temsil eder"
type: docs
weight: 340
url: /tr/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
## EotFont class

EOT (Embedded OpenType) formatındaki bir yazı tipini temsil eder.

```csharp
public sealed class EotFont : FontResourceBase
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [EotFont](eotfont#constructor)(string, Stream) | İçeriği bayt akışı olarak temsil edilen ve belirtilen adla yeni bir EotFont sınıfı oluşturur |
| [EotFont](eotfont#constructor_1)(string, string) | İçeriği base64 kodlu dize olarak temsil edilen ve belirtilen adla yeni bir EotFont sınıfı oluşturur |

## Properties

| Name | Açıklama |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Bu yazı tipinin içeriğini bayt akışı olarak döndürür |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Ad ve uzantıdan oluşan bu yazı tipi kaynağının doğru dosya adını döndürür. Teorik olarak isimden farklı olabilir. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Bu yazı tipinin serbest bırakılıp bırakılmadığını belirler |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Bu yazı tipi kaynağının adını döndürür. Genellikle dosya uzantısı içermez ve teorik olarak dosya adından farklı olabilir. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Bu yazı tipinin içeriğini base64 kodlu dize olarak döndürür. Bu değer ilk çağrıdan sonra önbelleğe alınır. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/type) { get; } | FontType.Eot değerini döndürür |

## Methods

| Name | Açıklama |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Bu yazı tipi kaynağını serbest bırakır, içeriğini serbest bırakır ve çoğu yöntem ve özelliği çalışmaz hâle getirir |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | Bu örneği belirtilen yazı tipi kaynağıyla referans eşitliği açısından kontrol eder |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | Bu örneği belirtilen HTML kaynağıyla referans eşitliği açısından kontrol eder |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Bu yazı tipini belirtilen dosyaya kaydeder |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/isvalid#isvalid)(Stream) | Belirtilen akışın geçerli bir EOT yazı tipi olup olmadığını denetler |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/isvalid#isvalid_1)(string) | Belirtilen base64 kodlu dize geçerli bir EOT yazı tipi mi kontrol eder |

## Alanlar

| Name | Açıklama |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/eotfont/requiredheadersize) | EOT başlık boyutu (bayt cinsinden), doğrulama için gereklidir |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Bu yazı tipi serbest bırakıldığında gerçekleşen olay |

### Ayrıca Bakınız

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
