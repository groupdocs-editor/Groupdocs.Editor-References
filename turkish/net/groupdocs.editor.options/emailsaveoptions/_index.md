---
title: "EmailSaveOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Elektronik posta belgelerinin oluşturulması ve kaydedilmesi için özelleştirilmiş seçenekler belirtmeye izin verir."
type: docs
weight: 860
url: /tr/net/groupdocs.editor.options/emailsaveoptions/
---
## EmailSaveOptions class

Elektronik posta (email) belgelerini oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir.

```csharp
public sealed class EmailSaveOptions : ISaveOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [EmailSaveOptions](emailsaveoptions#constructor)() | Tüm seçeneklerin varsayılan değerlere ayarlandığı yeni bir [`EmailSaveOptions`](../emailsaveoptions) sınıf örneğini başlatır. |
| [EmailSaveOptions](emailsaveoptions#constructor_1)(MailMessageOutput) | `[`MailMessageOutput`](./mailmessageoutput)` parametresiyle yeni bir [`EmailSaveOptions`](../emailsaveoptions) sınıf örneğini başlatır. |

## Properties

| Name | Açıklama |
| --- | --- |
| [MailMessageOutput](../../groupdocs.editor.options/emailsaveoptions/mailmessageoutput) { get; set; } | [`Save`](../../groupdocs.editor/editor/save) yöntemiyle oluşturulup kaydedilecek çıktı e-posta belgesine hangi posta mesajı bölümlerinin dahil edileceğini kontrol etmeye izin verir. |

### Ayrıca Bakınız

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
