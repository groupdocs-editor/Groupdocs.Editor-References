---
title: SpreadsheetSaveOptions
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Hesap Çizelgesi Excel uyumlu belgeleri oluşturmak ve kaydetmek için özel seçenekleri belirlemeye izin verir
type: docs
weight: 910
url: /tr/net/groupdocs.editor.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

Hesap Çizelgesi (Excel uyumlu) belgeleri oluşturmak ve kaydetmek için özel seçenekleri belirlemeye izin verir

```csharp
public sealed class SpreadsheetSaveOptions : ISaveOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions)(SpreadsheetFormats) | Diğer tüm parametreler default iken, belirtilen zorunlu Elektronik Tablo çıktı biçimiyle yeni bir SpreadsheetSaveOptions örneği oluşturur. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [InsertAsNewWorksheet](../../groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet) { get; set; } | Düzenlenen çalışma sayfasının orijinal elektronik tablodaki mevcut çalışma sayfasını, konum tarafından belirtilen konumda değiştirip değiştirmeyeceğini belirten Boole bayrağı[`WorksheetNumber`](./worksheetnumber) özelliği, veya içeriği değiştirilmeden mevcut çalışma sayfası ile önceki çalışma sayfası arasına enjekte edilmelidir. Varsayılan olarak yanlıştır — mevcut çalışma sayfası değiştirilecektir. değeri ise bu özellik göz ardı edilir.[`WorksheetNumber`](./worksheetnumber) özellik '0' olarak ayarlandı. |
| [OutputFormat](../../groupdocs.editor.options/spreadsheetsaveoptions/outputformat) { get; set; } | Document dosyasını kaydetmek için kullanılacak bir Hesap Tablosu formatı belirlemeye izin verir. |
| [Password](../../groupdocs.editor.options/spreadsheetsaveoptions/password) { get; set; } | Oluşturulan Elektronik Tablo belgesini kodlamak için kullanılacak bir parolanın belirlenmesine, değiştirilmesine, alınmasına veya kaldırılmasına izin verir, bu belge biçimi parola korumasını destekliyorsa. Parolayı kaldırmak (temizlemek) için NULL veya boş dize belirtin. |
| [WorksheetNumber](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber) { get; set; } | Yeni bir tek çalışma sayfası elektronik tablosu oluşturmak yerine, düzenlenmiş çalışma sayfasının mevcut elektronik tablonun kopyasına eklenmesine izin verir (varsayılan davranış). WorksheetNumber, Editor sınıfına yüklenen elektronik tablodaki bir çalışma sayfasının 1 tabanlı sayısıdır. 0 (varsayılan değer) ise, yeni elektronik tablo tek bir düzenlenmiş çalışma sayfasıyla oluşturulur. Sıfırdan büyük veya küçükse ve Editör sınıfına yüklenmiş, düzenlenmiş çalışma sayfası ile temsil edilen geçerli bir elektronik tablo varsa giriş EditableDocument örneği, bu e-tabloya eklenecek. |
| [WorksheetProtection](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetprotection) { get; set; } | Çıktı Elektronik Tablo belgesi için bir çalışma sayfası korumasının etkinleştirilmesine izin verir. Varsayılan olarak NULL'dur - koruma uygulanmaz. Tüm biçimler çalışma sayfası korumasını desteklemez. |

### Ayrıca bakınız

* interface [ISaveOptions](../isaveoptions)
* ad alanı [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->