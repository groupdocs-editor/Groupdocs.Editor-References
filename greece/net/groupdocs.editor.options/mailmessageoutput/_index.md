---
title: MailMessageOutput
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Ελέγχει ποια μέρη του μηνύματος αλληλογραφίας πρέπει να παραδοθούν στην έξοδο processing
type: docs
weight: 950
url: /el/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

Ελέγχει ποια μέρη του μηνύματος αλληλογραφίας πρέπει να παραδοθούν στην έξοδο processing

```csharp
[Flags]
public enum MailMessageOutput : ushort
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| None | `0` | Κανένα από τα μέρη του μηνύματος email δεν θα υποβληθεί σε επεξεργασία |
| Body | `1` | Σώμα επεξεργασίας του μηνύματος αλληλογραφίας |
| Subject | `2` | Επεξεργασία θέματος του μηνύματος αλληλογραφίας |
| Date | `4` | Επεξεργασία ημερομηνία και ώρα παράδοσης του μηνύματος |
| To | `8` | Επεξεργασία όλων των παραληπτών του μηνύματος αλληλογραφίας |
| Cc | `10` | Επεξεργασία όλων των παραληπτών CC του μηνύματος αλληλογραφίας |
| Bcc | `20` | Επεξεργασία όλων των παραληπτών BCC του μηνύματος αλληλογραφίας |
| From | `40` | Επεξεργασία αποστολέα του μηνύματος αλληλογραφίας |
| Attachments | `80` | Επεξεργασία όλων των συνημμένων του μηνύματος αλληλογραφίας |
| Metadata | `100` | Επεξεργασία όλων των άλλων τεχνικών μεταδεδομένων (ευαισθησία, προτεραιότητα, κωδικοποίηση, MIME, X-Mailer, κ.λπ.) |
| Common | `7B` | Κοινή έξοδος - σώμα με όλα τα κύρια μεταδεδομένα |
| All | `1FF` | Πλήρης έξοδος - σώμα με όλα τα μεταδεδομένα |

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
