---
title: EmailFormats
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Tüm eposta biçimlerini kapsüller. Aşağıdaki dosya türlerini içerir Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /tr/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

Tüm e-posta biçimlerini kapsüller. Aşağıdaki dosya türlerini içerir: [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | Tür uygulamasında dosya uzantısı biçiminde dönmelidir (baştaki nokta karakteri olmadan). |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | Uygulama türü, verilen format için bir MIME kodu döndürmelidir |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | Uygulama türü, tam resmi biçim name döndürmelidir |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | örneğini döndürür[`EmailFormats`](../emailformats) yapı, belirtilen dosya adı uzantısıyla ilişkilendirilir veya uzantı düzgün bir şekilde ayrıştırılamazsa bir istisna atar |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | Bu örneğin belirtilen diğer E-posta örneğine eşit olup olmadığını belirler |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | Bu örneğin belirtilen diğer IDocumentFormat örneğine eşit olup olmadığını belirler |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | Bu örneğin, muhtemelen kutulu Email olan belirtilen diğer nesneye eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | Bu örnek için sabit olan bir karma kodu döndürür |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | Bu format için bir format adı döndürür |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | Verilen iki E-posta örneğini eşitlikte kontrol eder |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | Eşitsizlik üzerinde verilen iki E-posta örneğini kontrol eder |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML dosya biçimi, Outlook ve diğer ilgili uygulamalar kullanılarak kaydedilen e-posta mesajlarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | EMLX dosya formatı Apple tarafından uygulanır ve geliştirilir. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya biçimini kullanır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML biçimli e-postalar. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | İnternet Takvimi ve Çizelgeleme Temel Nesne Spesifikasyonu (iCalendar), takvim olaylarını ve programlamayı değiş tokuş etmek ve dağıtmak için bir internet standardıdır (RFC 2445). Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox dosya formatı, elektronik posta mesajlarının toplanması için bir kapsayıcıyı temsil eden genel bir terimdir. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, "Birleştirilmiş HTML belgelerinin MIME kapsüllemesi"nin baş harfi |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajlarını, kişileri, randevuları veya diğer görevleri depolamak için kullanılan bir dosya biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | .oft uzantılı dosyalar, Microsoft Outlook kullanılarak oluşturulan şablon dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Çevrimdışı Depolama Tablosu (OST) dosyası, Microsoft Outlook kullanılarak Exchange Server'a kaydolduktan sonra yerel makinede çevrimdışı modda kullanıcının posta kutusu verilerini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | .pst uzantılı dosyalar, çeşitli kullanıcı bilgilerini depolayan Outlook Kişisel Depolama Dosyalarını (Kişisel Depolama Tablosu olarak da adlandırılır) temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Aktarım Tarafsız Kapsülleme Formatı (TNEF), Mesajlaşma Uygulama Programlama Arayüzüne (MAPI) dayalı e-posta eklerini kapsüllemek için Microsoft'a aittir. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Sanal Kart Formatı) veya vCard, iletişim bilgilerini saklamak için kullanılan bir dijital dosya formatıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | Mevcut tüm e-posta biçimleri üzerinde sayısız olasılık sağlayan dahili bir sınıf döndürür |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | E-posta type için 'foreach' olasılığını etkinleştiren IEnumerable genel arabirimini uygular |

### Notlar

E-posta formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/email/) .

### Ayrıca bakınız

* interface [IDocumentFormat](../idocumentformat)
* ad alanı [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
