---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Spreadsheet Excel uyumlu belgeleri oluşturmak ve kaydetmek için özel seçenekleri belirtmeye izin verir."
type: docs
weight: 1130
url: /tr/net/groupdocs.editor.options/spreadsheetsaveoptions/
---
## SpreadsheetSaveOptions class

Elektronik Tablo (Excel uyumlu) belgelerini oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir.

```csharp
public sealed class SpreadsheetSaveOptions : ISaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor)() | Bu parametresiz yapıcı, XLSX çıktı formatı ile bir SpreadsheetSaveOptions yeni örneği oluşturur (daha sonra [`OutputFormat`](./outputformat) özelliği aracılığıyla değiştirilebilir). |
| [SpreadsheetSaveOptions](spreadsheetsaveoptions#constructor_1)(SpreadsheetFormats) | Belirtilen zorunlu Spreadsheet çıktı formatı ile bir SpreadsheetSaveOptions yeni örneği oluşturur, diğer tüm parametreler varsayılan olur. |

## Properties

| Name | Açıklama |
| --- | --- |
| [InsertAsNewWorksheet](../../groupdocs.editor.options/spreadsheetsaveoptions/insertasnewworksheet) { get; set; } | Bu, düzenlenen çalışma sayfasının, [`WorksheetNumber`](./worksheetnumber) özelliği ile belirtilen konumda orijinal elektronik tabloda mevcut çalışma sayfasının yerine geçip geçmeyeceğini veya içeriğini değiştirmeden mevcut çalışma sayfası ile öncekisi arasına eklenip eklenmeyeceğini belirten Boolean bayrağıdır. Varsayılan olarak false'tur — mevcut çalışma sayfası değiştirilecektir. [`WorksheetNumber`](./worksheetnumber) özelliğinin değeri '0' olarak ayarlanmışsa bu özellik yok sayılır. |
| [OutputFormat](../../groupdocs.editor.options/spreadsheetsaveoptions/outputformat) { get; set; } | Belgeyi kaydetmek için kullanılacak bir Spreadsheet formatı belirtmeye izin verir. |
| [Password](../../groupdocs.editor.options/spreadsheetsaveoptions/password) { get; set; } | Oluşturulan Spreadsheet belgesini şifrelemek için kullanılacak bir şifreyi belirtmeye, değiştirmeye, almaya veya kaldırmaya izin verir; bu belge formatı şifre korumasını destekliyorsa. Şifreyi kaldırmak (temizlemek) için NULL veya boş bir dize belirtin. |
| [WorksheetNumber](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumber) { get; set; } | Yeni tek çalışma sayfası içeren bir elektronik tablo oluşturmak yerine (varsayılan davranış) düzenlenmiş çalışma sayfasını mevcut elektronik tablonun bir kopyasına eklemeye izin verir. WorksheetNumber, Editor sınıfında yüklü elektronik tablodaki çalışma sayfasının 1 tabanlı numarasıdır. 0 (varsayılan değer) ise yeni elektronik tablo tek düzenlenmiş çalışma sayfası ile oluşturulur. Sıfırdan büyük veya küçük bir değer ve Editor sınıfında geçerli bir elektronik tablo yüklüyse, giriş EditableDocument örneğiyle temsil edilen düzenlenmiş çalışma sayfası bu elektronik tabloya eklenir. |
| [WorksheetNumbersToDelete](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetnumberstodelete) { get; set; } | Düzenlenmiş çalışma sayfası mevcut elektronik tabloya eklendiğinde, kaydetme sırasında elektronik tablodan silinmesi gereken 1 tabanlı çalışma sayfası numaralarını içeren bir dizi belirtmeye izin verir. |
| [WorksheetProtection](../../groupdocs.editor.options/spreadsheetsaveoptions/worksheetprotection) { get; set; } | Çıktı Spreadsheet belgesi için çalışma sayfası korumasını etkinleştirmeye izin verir. Varsayılan olarak NULL'dır - koruma uygulanmaz. Tüm formatlar çalışma sayfası korumasını desteklemez. |

### Ayrıca Bakınız

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
