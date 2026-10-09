---
title: "FontResourceBase"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "HTML belgesi için tüm özellikleriyle desteklenen herhangi bir yazı tipi türü kaynağı için temel sınıf."
type: docs
weight: 350
url: /tr/net/groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
## FontResourceBase class

HTML belgesi için tüm özellikleriyle desteklenen herhangi bir yazı tipi türü kaynağı için temel sınıf.

```csharp
public abstract class FontResourceBase : IEquatable<FontResourceBase>, IHtmlResource
```

## Properties

| Name | Açıklama |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Bu yazı tipinin içeriğini bayt akışı olarak döndürür |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Ad ve uzantıdan oluşan bu yazı tipi kaynağının doğru dosya adını döndürür. Teorik olarak isimden farklı olabilir. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Bu yazı tipinin serbest bırakılıp bırakılmadığını belirler |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Bu yazı tipi kaynağının adını döndürür. Genellikle dosya uzantısı içermez ve teorik olarak dosya adından farklı olabilir. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Bu yazı tipinin içeriğini base64 kodlu dize olarak döndürür. Bu değer ilk çağrıdan sonra önbelleğe alınır. |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/type) { get; } | Uygulayan tür, tüm tür‑özel bilgileri kapsayan belirli bir FontType örneği olarak belirli font kaynağının türü hakkında bilgi döndürmelidir |

## Methods

| Name | Açıklama |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Bu yazı tipi kaynağını serbest bırakır, içeriğini serbest bırakır ve çoğu yöntem ve özelliği çalışmaz hâle getirir |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals)(FontResourceBase) | Bu örneği belirtilen yazı tipi kaynağıyla referans eşitliği açısından kontrol eder |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals_1)(IHtmlResource) | Bu örneği belirtilen HTML kaynağıyla referans eşitliği açısından kontrol eder |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Bu yazı tipini belirtilen dosyaya kaydeder |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Bu yazı tipi serbest bırakıldığında gerçekleşen olay |

### Ayrıca Bakınız

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
