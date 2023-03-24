---
title: EotFont
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Δημιουργεί νέα κλάση EotFont από περιεχόμενο που αναπαρίσταται ως συμβολοσειρά με κωδικοποίηση base64 και με καθορισμένο όνομα
type: docs
weight: 10
url: /el/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

Δημιουργεί νέα κλάση EotFont από περιεχόμενο, που αναπαρίσταται ως συμβολοσειρά με κωδικοποίηση base64 και με καθορισμένο όνομα

```csharp
public EotFont(string name, string contentInBase64)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα γραμματοσειράς ΕΟΤ. Δεν μπορεί να είναι μηδενικά, κενά ή κενά. |
| contentInBase64 | String | Περιεχόμενο ως συμβολοσειρά με κωδικοποίηση base64. Δεν μπορεί να είναι μηδενικά, κενά ή κενά. Εάν δεν είναι περιεχόμενο EOT, θα γίνει εξαίρεση. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Δείτε επίσης

* class [EotFont](../../eotfont)
* χώρος ονομάτων [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../eotfont)
* συνέλευση [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

Δημιουργεί νέα κλάση EotFont από περιεχόμενο, που αναπαρίσταται ως ροή byte και με καθορισμένο όνομα

```csharp
public EotFont(string name, Stream binaryContent)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Όνομα γραμματοσειράς ΕΟΤ. Δεν μπορεί να είναι μηδενικά, κενά ή κενά. |
| binaryContent | Stream | Το περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι μηδενικό. Θα πρέπει να είναι ευανάγνωστο και αναζητήσιμο. Εάν αυτή η περίπτωση απορριφθεί, θα απορριφθεί και αυτή η ροή. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Δείτε επίσης

* class [EotFont](../../eotfont)
* χώρος ονομάτων [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../eotfont)
* συνέλευση [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->