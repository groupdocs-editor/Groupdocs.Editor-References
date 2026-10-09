---
title: "EmailFormats"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Tüm e-posta formatlarını kapsar. Aşağıdaki dosya türlerini içerir Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /tr/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

Tüm e-posta formatlarını kapsar. Aşağıdaki dosya türlerini içerir: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Belge formatının dosya uzantısını alır. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Belge formatının ait olduğu format ailesini alır. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Format ailesinin benzersiz tanımlayıcısını alır. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Belge formatının MIME tipini alır. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Format ailesinin adını alır. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | Tüm [`EmailFormats`](../emailformats) koleksiyonunu enumerable olarak alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Belirtilen dosya uzantısına sahip belirtilen türdeki [`EmailFormats`](../emailformats) örneğini alır. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bu örneğin belirtilen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bu örneğin belirtilen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat) örneğiyle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bu örneğin belirtilen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase) örneğiyle eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Geçerli nesne için bir karma kod (hash code) döndürür. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | Bir dosya uzantısını temsil eden dizeyi bir [`EmailFormats`](../emailformats) nesnesine dönüştürür. |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | EML dosya formatı, Outlook ve diğer ilgili uygulamalar kullanılarak kaydedilen e-posta mesajlarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | EMLX dosya formatı Apple tarafından uygulanmış ve geliştirilmiştir. Apple Mail uygulaması, e-postaları dışa aktarmak için EMLX dosya formatını kullanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | HTML biçimlendirilmiş e-postalar. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Internet Calendaring and Scheduling Core Object Specification (iCalendar), takvim etkinliklerini ve planlamayı değiş tokuş etmek ve dağıtmak için bir internet standardıdır (RFC 2445). Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | MBox dosya formatı, elektronik posta mesajları koleksiyonunu içeren bir konteyneri temsil eden genel bir terimdir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, "MIME encapsulation of aggregate HTML documents" ifadesinin kısaltmasıdır. |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | MSG, Microsoft Outlook ve Exchange tarafından e-posta mesajları, kişi, randevu veya diğer görevleri depolamak için kullanılan bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | .oft uzantılı dosyalar, Microsoft Outlook kullanılarak oluşturulan şablon dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Offline Storage Table (OST) dosyası, Microsoft Outlook kullanarak Exchange Server'a kaydolduktan sonra yerel makinede çevrim dışı modda kullanıcının posta kutusu verilerini temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | .pst uzantılı dosyalar, çeşitli kullanıcı bilgilerini depolayan Outlook Kişisel Depolama Dosyaları (aynı zamanda Personal Storage Table olarak da adlandırılır) temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Transport Neutral Encapsulation Format (TNEF), Messaging Application Programming Interface (MAPI) tabanlı e-posta eklerini kapsüllemek için Microsoft'a ait bir formattır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | VCF (Virtual Card Format) veya vCard, iletişim bilgilerini depolamak için kullanılan dijital bir dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/vcf/). |

### Açıklamalar

E-posta formatları hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/email/).

### Ayrıca Bakınız

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
