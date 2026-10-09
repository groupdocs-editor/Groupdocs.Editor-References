---
title: "Mp3Audio"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "İstediğiniz formatta bir ses kaynağını temsil eder"
type: docs
weight: 330
url: /tr/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
## Mp3Audio class

İstediğiniz formatta bir ses kaynağını temsil eder

```csharp
public sealed class Mp3Audio : IEquatable<Mp3Audio>, IHtmlResource
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [Mp3Audio](mp3audio)(string, Stream) | MP3 içeriğinden, bayt akışı olarak temsil edilen ve belirtilen adla yeni Mp3Audio sınıfı oluşturur |

## Properties

| Name | Açıklama |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/bytecontent) { get; } | Bu yazı tipinin içeriğini bayt akışı olarak döndürür |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/filenamewithextension) { get; } | Bu MP3 içeriğinin ad ve uzantıdan oluşan doğru dosya adını döndürür. Teorik olarak isimden farklı olabilir. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isdisposed) { get; } | Bu MP3 içeriğinin imha edilip edilmediğini belirler |
| [Name](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/name) { get; } | Bu MP3 içeriğinin adını döndürür. Genellikle dosya uzantısı içermez ve teorik olarak dosya adından farklı olabilir. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/textcontent) { get; } | Bu MP3 kaynağının içeriğini base64 kodlu dize olarak döndürür. Bu değer ilk çağrıdan sonra önbelleğe alınır. |
| [Type](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/type) { get; } | AudioType.Mp3 değerini döndürür |

## Methods

| Name | Açıklama |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/dispose)() | Bu MP3 kaynağını imha eder, içeriğini imha eder ve çoğu yöntem ve özelliği çalışmaz hâle getirir |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals_1)(IHtmlResource) | Bu örneği belirtilen HTML kaynağıyla referans eşitliği açısından kontrol eder |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals)(Mp3Audio) | Bu örneği belirtilen yazı tipi kaynağıyla referans eşitliği açısından kontrol eder |
| [Save](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/save)(string) | Bu MP3 kaynağını belirtilen dosyaya kaydeder |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isvalid)(Stream) | Belirtilen akışın geçerli bir MP3 içeriği olup olmadığını kontrol eder |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/disposed) | Bu MP3 içeriği serbest bırakıldığında gerçekleşen olay |

### Ayrıca Bakınız

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
