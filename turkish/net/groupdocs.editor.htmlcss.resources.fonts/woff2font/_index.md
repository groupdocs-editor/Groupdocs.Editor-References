---
title: "Woff2Font"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "WOFF2 Web Open Font Format formatında bir fontu temsil eder"
type: docs
weight: 400
url: /tr/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
## Woff2Font class

WOFF2 (Web Open Font Format) formatındaki bir yazı tipini temsil eder.

```csharp
public sealed class Woff2Font : FontResourceBase
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [Woff2Font](woff2font#constructor)(string, Stream) | İçeriği bayt akışı olarak temsil eden ve belirtilen adla yeni bir Woff2Font sınıfı oluşturur |
| [Woff2Font](woff2font#constructor_1)(string, string) | İçeriği base64 kodlu dize olarak temsil eden ve belirtilen adla yeni bir Woff2Font sınıfı oluşturur |

## Properties

| Name | Açıklama |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Bu yazı tipinin içeriğini bayt akışı olarak döndürür |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Ad ve uzantıdan oluşan bu yazı tipi kaynağının doğru dosya adını döndürür. Teorik olarak isimden farklı olabilir. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Bu yazı tipinin serbest bırakılıp bırakılmadığını belirler |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Bu yazı tipi kaynağının adını döndürür. Genellikle dosya uzantısı içermez ve teorik olarak dosya adından farklı olabilir. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Bu yazı tipinin içeriğini base64 kodlu dize olarak döndürür. Bu değer ilk çağrıdan sonra önbelleğe alınır. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/type) { get; } | Returns FontType.Woff2 |

## Methods

| Name | Açıklama |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Bu yazı tipi kaynağını serbest bırakır, içeriğini serbest bırakır ve çoğu yöntem ve özelliği çalışmaz hâle getirir |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | Bu örneği belirtilen yazı tipi kaynağıyla referans eşitliği açısından kontrol eder |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | Bu örneği belirtilen HTML kaynağıyla referans eşitliği açısından kontrol eder |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Bu yazı tipini belirtilen dosyaya kaydeder |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/isvalid#isvalid)(Stream) | Belirtilen akışın geçerli bir WOFF2 fontu olup olmadığını kontrol eder |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/isvalid#isvalid_1)(string) | Belirtilen base64 kodlu dizenin geçerli bir WOFF2 fontu olup olmadığını kontrol eder |

## Alanlar

| Name | Açıklama |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/woff2font/requiredheadersize) | Doğrulama için gerekli olan WOFF2 başlık boyutu (bayt cinsinden) |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Bu yazı tipi serbest bırakıldığında gerçekleşen olay |

### Ayrıca Bakınız

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
