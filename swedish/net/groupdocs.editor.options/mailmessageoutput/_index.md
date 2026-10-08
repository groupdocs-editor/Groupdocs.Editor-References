---
title: "MailMessageOutput"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Styr vilka delar av e‑postmeddelandet som ska levereras till utdatahanteringen"
type: docs
weight: 960
url: /sv/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

Styr vilka delar av e‑postmeddelandet som ska levereras till utdatahanteringen

```csharp
[Flags]
public enum MailMessageOutput
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Ingen av e‑postmeddelandets delar kommer att bearbetas |
| Body | `1` | Bearbeta meddelandekroppen i e‑postmeddelandet |
| Subject | `2` | Bearbeta ämnet i e‑postmeddelandet |
| Date | `4` | Bearbeta datum och tid då meddelandet levererades |
| To | `8` | Bearbeta alla mottagare av e‑postmeddelandet |
| Cc | `10` | Bearbeta alla CC‑mottagare av e‑postmeddelandet |
| Bcc | `20` | Bearbeta alla BCC‑mottagare av e‑postmeddelandet |
| From | `40` | Bearbeta avsändaren av e‑postmeddelandet |
| Attachments | `80` | Bearbeta alla bilagor i e‑postmeddelandet |
| Metadata | `100` | Bearbeta all annan teknisk metadata (känslighet, prioritet, kodning, MIME, X-Mailer, etc.) |
| Common | `7B` | Vanlig utdata – kropp med all huvudmetadata |
| All | `1FF` | Fullständig utdata – kropp med all metadata |

### Se även

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
