---
title: TextualFormats
second_title: .NET API Başvurusu için GroupDocs.Editor
description: İşaretleme XML HTML ve diğerleri dahil olmak üzere tüm metinsel metin tabanlı biçimleri kapsüller. Aşağıdaki biçimleri içerir Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /tr/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

İşaretleme (XML, HTML) ve diğerleri dahil olmak üzere tüm metinsel (metin tabanlı) biçimleri kapsüller. Aşağıdaki biçimleri içerir: [`Html`](./html) , [`Txt`](./txt) , [`Xml`](./xml) . [`Md`](./md) , [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | Bu metin biçiminin bir uzantısını (baştaki nokta karakteri olmadan) küçük harfle döndürür |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | Bu biçim için bir MIME kodu döndürür |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | Bu metin biçiminin resmi bir tam adını döndürür |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | örneğini döndürür[`TextualFormats`](../textualformats) yapı, belirtilen dosya adı uzantısıyla ilişkilendirilir veya uzantı düzgün bir şekilde ayrıştırılamazsa bir istisna atar |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | Bu örneğin belirtilen diğer IDocumentFormat örneğine eşit olup olmadığını belirler |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | Bu örneğin, muhtemelen kutulu TextualFormats olan belirtilen diğer nesneye eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | Bu örneğin, belirtilen diğer TextualFormats örneğine eşit olup olmadığını belirler |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | Bu örnek için sabit olan bir karma kodu döndürür |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | 'Ad' özelliğiyle aynı olan bu belirli biçimin adını döndürür |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | Eşitlik üzerinde verilen iki TextualFormats örneğini kontrol eder |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | eşitsizlik üzerinde verilen iki TextualFormats örneğini kontrol eder |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Derlenmiş HTML Yardımı, bir HTML sayfaları koleksiyonu, bir dizin ve diğer gezinme araçlarından oluşan, Microsoft'a özel bir çevrimiçi yardım ikili biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | Köprü Metni Biçimlendirme Dili belgesi (HTML), tarayıcılarda görüntülenmek üzere oluşturulan web sayfalarının uzantısıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation), verileri depolamak ve iletmek için insanlar tarafından okunabilir metin kullanan, verileri paylaşmak için açık standart bir dosya biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown, düz metin düzenleyici kullanarak biçimlendirilmiş metin oluşturmak için hafif bir biçimlendirme dilidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | Toplu HTML belgelerinin MIME kapsüllemesi, tek bir bilgisayar dosyasında HTML kodunu ve yardımcı kaynaklarını birleştirmek için kullanılan bir web sayfası arşiv biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Düz Metin Belgesi (TXT), satır biçiminde düz metin içeren bir metin belgesini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | Genişletilebilir İşaretleme Dili belgesi (XML), HTML'ye benzer, ancak nesneleri tanımlamak için etiket kullanımı farklıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | Varolan tüm Metin biçimlerinde sayısız olasılık sağlayan dahili bir sınıf döndürür. |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | TextualFormats type için 'foreach' olasılığını etkinleştiren IEnumerable genel arabirimini uygular |

### Ayrıca bakınız

* interface [IDocumentFormat](../idocumentformat)
* ad alanı [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
