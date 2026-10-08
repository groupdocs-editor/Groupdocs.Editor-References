---
title: "MailMessageOutput"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengontrol bagian mana dari pesan email yang harus disampaikan ke proses output"
type: docs
weight: 960
url: /id/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

Mengontrol bagian mana dari pesan email yang harus disampaikan ke proses output

```csharp
[Flags]
public enum MailMessageOutput
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | `0` | Tidak ada bagian pesan email yang akan diproses |
| Body | `1` | Proses isi pesan email |
| Subject | `2` | Proses subjek pesan email |
| Date | `4` | Proses tanggal dan waktu saat pesan dikirim |
| To | `8` | Proses semua penerima pesan email |
| Cc | `10` | Proses semua penerima CC pesan email |
| Bcc | `20` | Proses semua penerima BCC pesan email |
| From | `40` | Proses pengirim pesan email |
| Attachments | `80` | Proses semua lampiran pesan email |
| Metadata | `100` | Proses semua metadata teknis lainnya (sensitivitas, prioritas, enkoding, MIME, X-Mailer, dll) |
| Common | `7B` | Output umum - badan dengan semua metadata utama |
| All | `1FF` | Output penuh - badan dengan semua metadata |

### Lihat Juga

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
