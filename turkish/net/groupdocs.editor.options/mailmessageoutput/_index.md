---
title: "MailMessageOutput"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "E-posta mesajının hangi bölümlerinin çıktı işleme teslim edileceğini kontrol eder"
type: docs
weight: 960
url: /tr/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

E-posta mesajının hangi bölümlerinin çıktı işleme teslim edileceğini kontrol eder

```csharp
[Flags]
public enum MailMessageOutput
```

### Değerler

| Name | Değer | Açıklama |
| --- | --- | --- |
| None | `0` | E-posta mesajının hiçbir bölümü işlenmeyecek. |
| Body | `1` | E-posta mesajının gövdesini işle. |
| Subject | `2` | E-posta mesajının konusunu işle. |
| Date | `4` | Mesajın teslim edildiği tarih ve saati işle. |
| To | `8` | Posta mesajının tüm alıcılarını işle |
| Cc | `10` | Posta mesajının tüm CC alıcılarını işle |
| Bcc | `20` | Posta mesajının tüm BCC alıcılarını işle |
| From | `40` | Posta mesajının gönderenini işle |
| Attachments | `80` | Posta mesajının tüm eklerini işle |
| Metadata | `100` | Diğer tüm teknik üst verileri (duyarlılık, öncelik, kodlama, MIME, X-Mailer, vb.) işle |
| Common | `7B` | Ortak çıktı - gövde tüm ana üst verilerle |
| All | `1FF` | Tam çıktı - gövde tüm üst verilerle |

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
