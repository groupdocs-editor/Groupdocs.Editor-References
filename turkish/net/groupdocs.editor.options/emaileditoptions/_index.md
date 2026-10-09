---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Farklı elektronik posta formatlarında belgeleri düzenlemek için özel seçenekleri belirtmeye izin verir"
type: docs
weight: 850
url: /tr/net/groupdocs.editor.options/emaileditoptions/
---
## EmailEditOptions class

Farklı elektronik posta (email) formatlarındaki belgeleri düzenlemek için özel seçenekleri belirtmeye izin verir.

```csharp
public sealed class EmailEditOptions : IEditOptions
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [EmailEditOptions](emaileditoptions#constructor)() | Tüm seçeneklerin varsayılan değerlere ayarlandığı yeni bir [`EmailEditOptions`](../emaileditoptions) sınıf örneğini başlatır |
| [EmailEditOptions](emaileditoptions#constructor_1)(MailMessageOutput) | [`MailMessageOutput`](./mailmessageoutput) parametresiyle yeni bir [`EmailEditOptions`](../emaileditoptions) sınıf örneğini başlatır |

## Properties

| Name | Açıklama |
| --- | --- |
| [MailMessageOutput](../../groupdocs.editor.options/emaileditoptions/mailmessageoutput) { get; set; } | E-posta mesajının hangi bölümlerinin çıktıya [`EditableDocument`](../../groupdocs.editor/editabledocument) ve ardından oluşturulan HTML'ye teslim edileceğini kontrol etmeyi sağlar |

### Ayrıca Bakınız

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
