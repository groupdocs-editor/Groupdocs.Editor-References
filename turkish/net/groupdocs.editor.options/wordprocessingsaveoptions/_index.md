---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Düzenlendikten sonra WordProcessing uyumlu belgelerin oluşturulması ve kaydedilmesi için özel seçenekler belirlemenize olanak tanır."
type: docs
weight: 1240
url: /tr/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Düzenlendikten sonra WordProcessing uyumlu belgeler oluşturmak ve kaydetmek için özel seçenekler belirtmeye olanak tanır

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Bu parametresiz yapıcı, DOCX çıktı formatına sahip bir WordProcessingSaveOptions örneği oluşturur (daha sonra [`OutputFormat`](./outputformat) özelliği aracılığıyla değiştirilebilir). |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | Belirtilen zorunlu WordProcessing çıktı formatı ile yeni bir WordProcessingSaveOptions örneği oluşturur; diğer tüm parametreler varsayılan olur. |

## Properties

| Name | Açıklama |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | WordProcessing belgesinin kaydedilmesinde kullanılacak sayfalama özelliğini etkinleştirmenize veya devre dışı bırakmanıza olanak tanır. Orijinal belge sayfalama modunda açılıp düzenlendiyse bu seçenek de etkin olmalıdır. Varsayılan olarak devredışı bırakılmıştır. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Çıktı WordProcessing belgesine yazı tipi kaynaklarını gömmekten sorumludur. Varsayılan olarak hiçbir yazı tipi gömülmez (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | WordProcessing belgesi oluşturulurken uygulanacak varsayılan yerel ayarı (dili) geçersiz kılmanıza olanak tanır. Belirtilmezse (varsayılan değer), MS Word (veya başka bir program) belge yerel ayarını kendi ayarları veya diğer faktörlere göre algılar (veya seçer). |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | WordProcessing belgesinin RTL (sağdan sola) metinleri için yerel ayarını (dil) geçersiz kılmanıza olanak tanır; bu ayar oluşturma sırasında uygulanır. Belirtilmezse (varsayılan değer), MS Word (veya başka bir program) belge RTL yerel ayarını kendi ayarları veya diğer faktörlere göre algılar (veya seçer). |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | WordProcessing belgesinin Doğu Asya metinleri için yerel ayarını (dil) geçersiz kılmanıza olanak tanır; bu ayar oluşturma sırasında uygulanır. Belirtilmezse (varsayılan değer), MS Word (veya başka bir program) belge Doğu Asya yerel ayarını kendi ayarları veya diğer faktörlere göre algılar (veya seçer). |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | HTML'den belge oluşturma sırasında bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir. Bu seçeneği true olarak ayarlamak, büyük belgeler oluşturulurken bellek tüketimini önemli ölçüde azaltabilir, ancak kaydetme süresini yavaşlatır. Varsayılan değer false'tur (daha iyi performans için bellek optimizasyonu devre dışı bırakılmıştır). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Belgeyi kaydetmek için kullanılacak bir WordProcessing formatı belirlemenize olanak tanır. |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Oluşturulan WordProcessing belgesini kodlamak için kullanılacak bir şifreyi belirlemenize, değiştirmenize, almanıza veya kaldırmanıza olanak tanır. Şifreyi kaldırmak (temizlemek) için NULL veya boş dize belirtin. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Belge korumasını destekleyen herhangi bir formatta WordProcessing belgesi için belge koruma seçeneklerini kontrol etmenize ve uygulamanıza olanak tanır. Varsayılan olarak NULL'dır - belge koruması kullanılmaz. |

## Methods

| Name | Açıklama |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Bu WordProcessingSaveOptions sınıfı örneğinin tam bir kopyasını oluşturur ve döndürür. |

### Açıklamalar

WordProcessingSaveOptions, düzenlenmiş belge içeriğini içeren bir EditableDocument sınıfı örneği bulunduğunda ve bu içeriğin yeni bir WordProcessing formatındaki belgeye kaydedilmesi gerektiğinde uygulanır.

### Ayrıca Bakınız

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
