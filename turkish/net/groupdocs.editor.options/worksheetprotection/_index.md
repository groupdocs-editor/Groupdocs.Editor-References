---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Belirli bir türde ve belirli bir şifreyle yapılan değişikliklerden çıktı Elektronik Tablo belgesindeki çalışma sayfasını korumayı sağlayan çalışma sayfası koruma seçeneklerini kapsar."
type: docs
weight: 1250
url: /tr/net/groupdocs.editor.options/worksheetprotection/
---
## WorksheetProtection class

Çıktı Spreadsheet belgesindeki bir çalışma sayfasını belirtilen türdeki değişikliklerden ve belirtilen şifreyle korumaya izin veren çalışma sayfası koruma seçeneklerini kapsar.

```csharp
public sealed class WorksheetProtection
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [WorksheetProtection](worksheetprotection#constructor)() | Varsayılan parametrelerle yeni bir örnek oluşturur. Değiştirilmez ve SpreadsheetSaveOptions'a geçirilirse, çalışma sayfası koruması uygulanmaz. |
| [WorksheetProtection](worksheetprotection#constructor_1)(WorksheetProtectionType, string) | Belirtilen çalışma sayfası koruma türü ve şifre ile yeni bir örnek oluşturur. |

## Properties

| Name | Açıklama |
| --- | --- |
| [Password](../../groupdocs.editor.options/worksheetprotection/password) { get; set; } | Çalışma sayfasını korumak için kullanılan şifre. NULL veya boş bir dize ise koruma uygulanmaz. |
| [ProtectionType](../../groupdocs.editor.options/worksheetprotection/protectiontype) { get; set; } | Bir çalışma sayfası koruma türü belirtmeye izin verir. Varsayılan olarak 'None' - koruma uygulanmaz. |

### Açıklamalar

XLSX gibi çoğu Elektronik Tablo formatı, bir çalışma sayfasını şifreyle düzenlemeden korumaya izin verir. Bu sınıf, bu korumayı etkinleştirmeyi ve seçeneklerini belirtmeyi sağlar.

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
