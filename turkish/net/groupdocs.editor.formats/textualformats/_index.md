---
title: "TextualFormats"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Metin tabanlı tüm biçimleri, işaretleme XML HTML ve diğerlerini kapsar. Aşağıdaki biçimleri içerir Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /tr/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

Metin (metin tabanlı) biçimlerinin tümünü, işaretleme (XML, HTML) ve diğerlerini kapsar. Aşağıdaki biçimleri içerir: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Belge formatının dosya uzantısını alır. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Belge formatının ait olduğu format ailesini alır. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Format ailesinin benzersiz tanımlayıcısını alır. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Belge formatının MIME tipini alır. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Format ailesinin adını alır. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | Tüm [`TextualFormats`](../textualformats) öğelerinin yinelenebilir bir koleksiyonunu alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Belirtilen dosya uzantısına sahip belirtilen tipteki [`TextualFormats`](../textualformats) örneğini getirir. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bu örneğin belirtilen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bu örneğin belirtilen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) örneğiyle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bu örneğin belirtilen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) örneğiyle eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Geçerli nesne için bir karma kod (hash code) döndürür. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | Dosya uzantısını temsil eden bir dizeyi bir [`TextualFormats`](../textualformats) nesnesine dönüştürür. |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help, HTML sayfalarından, bir indeks ve diğer gezinme araçlarından oluşan Microsoft'a ait bir çevrimiçi yardım ikili biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | HyperText Markup Language belgesi (HTML), tarayıcılarda görüntülenmek üzere oluşturulan web sayfaları için uzantıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation), verileri depolamak ve iletmek için insan tarafından okunabilir metin kullanan açık bir standart dosya biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown, düz metin editörü kullanarak biçimlendirilmiş metin oluşturmak için hafif bir işaretleme dilidir. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME kapsülleme, birden fazla HTML belgesini tek bir bilgisayar dosyasında HTML kodu ve ilgili kaynakları birleştirmek için kullanılan bir web sayfası arşiv biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Düz Metin Belgesi (TXT), satır biçiminde düz metin içeren bir metin belgesini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | eXtensible Markup Language belgesi (XML) HTML'ye benzer ancak nesneleri tanımlamak için etiketler kullanma konusunda farklıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/web/xml). |

### Ayrıca Bakınız

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
