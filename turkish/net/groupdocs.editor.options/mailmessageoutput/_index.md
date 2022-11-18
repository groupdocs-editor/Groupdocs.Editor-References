---
title: MailMessageOutput
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Posta iletisinin hangi bölümlerinin çıktı işlemeye teslim edilmesi gerektiğini kontrol eder
type: docs
weight: 790
url: /tr/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

Posta iletisinin hangi bölümlerinin çıktı işlemeye teslim edilmesi gerektiğini kontrol eder

```csharp
[Flags]
public enum MailMessageOutput : ushort
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| None | `0` | E-posta mesajı bölümlerinin hiçbiri işlenmeyecek |
| Body | `1` | Posta mesajının işlem gövdesi |
| Subject | `2` | Posta mesajının işlem konusu |
| Date | `4` | Mesajın teslim edildiği tarih ve saati işlemek |
| To | `8` | Posta mesajının tüm alıcılarını işle |
| Cc | `10` | Posta mesajının tüm CC alıcılarını işle |
| Bcc | `20` | Posta mesajının tüm BCC alıcılarını işle |
| From | `40` | Posta mesajının göndericisini işlet |
| Attachments | `80` | Posta mesajının tüm eklerini işle |
| Metadata | `100` | Diğer tüm teknik meta verileri işleyin (hassasiyet, öncelik, kodlama, MIME, X-Mailer, vb.) |
| Common | `7B` | Ortak çıktı - tüm ana meta verileri içeren gövde |
| All | `1FF` | Tam çıktı - tüm meta verilerle birlikte gövde |

### Ayrıca bakınız

* ad alanı [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->