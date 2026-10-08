---
title: "EmailFormats"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Περιλαμβάνει όλες τις μορφές email. Συμπεριλαμβάνει τους ακόλουθους τύπους αρχείων Tnef./emailformats/tnef Eml./emailformats/eml Emlx./emailformats/emlx Msg./emailformats/msg Html./emailformats/html Mhtml./emailformats/mhtml."
type: docs
weight: 90
url: /el/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats class

Περιλαμβάνει όλες τις μορφές email. Συμπεριλαμβάνει τους ακόλουθους τύπους αρχείων: [`Tnef`](./tnef), [`Eml`](./eml), [`Emlx`](./emlx), [`Msg`](./msg), [`Html`](./html), [`Mhtml`](./mhtml).

```csharp
public class EmailFormats : DocumentFormatBase
```

## Properties

| Name | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Λαμβάνει την επέκταση αρχείου της μορφής εγγράφου. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Λαμβάνει την οικογένεια μορφής στην οποία ανήκει η μορφή εγγράφου. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Λαμβάνει το μοναδικό αναγνωριστικό για την οικογένεια μορφής. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Λαμβάνει τον τύπο MIME της μορφής εγγράφου. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Λαμβάνει το όνομα της οικογένειας μορφής. |
| static [All](../../groupdocs.editor.formats/emailformats/all) { get; } | Λαμβάνει μια επαναληπτική συλλογή όλων των [`EmailFormats`](../emailformats). |

## Methods

| Name | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Ανακτά μια παρουσία του καθορισμένου τύπου [`EmailFormats`](../emailformats) που έχει την καθορισμένη επέκταση αρχείου. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [explicit operator](../../groupdocs.editor.formats/emailformats/op_explicit) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [`EmailFormats`](../emailformats). |

## Πεδία

| Name | Περιγραφή |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | Η μορφή αρχείου EML αντιπροσωπεύει μηνύματα email που αποθηκεύονται χρησιμοποιώντας το Outlook και άλλες σχετικές εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/email/eml/). |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Η μορφή αρχείου EMLX υλοποιείται και αναπτύσσεται από την Apple. Η εφαρμογή Apple Mail χρησιμοποιεί τη μορφή αρχείου EMLX για την εξαγωγή των email. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/email/emlx/). |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | Emails μορφοποιημένα σε HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Η προδιαγραφή Internet Calendaring and Scheduling Core Object Specification (iCalendar) είναι ένα πρότυπο διαδικτύου (RFC 2445) για την ανταλλαγή και υλοποίηση γεγονότων ημερολογίου και προγραμματισμού. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/email/ics/). |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | Η μορφή αρχείου MBox είναι ένας γενικός όρος που αντιπροσωπεύει ένα δοχείο για τη συλλογή ηλεκτρονικών μηνυμάτων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/email/mbox/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, ένα ακρωνύμιο του "MIME encapsulation of aggregate HTML documents". |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | Το MSG είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων email, επαφών, ραντεβού ή άλλων εργασιών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/email/msg/). |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Τα αρχεία με επέκταση .oft είναι αρχεία προτύπου που δημιουργούνται χρησιμοποιώντας το Microsoft Outlook. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/email/oft/). |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Το αρχείο Offline Storage Table (OST) αντιπροσωπεύει τα δεδομένα του γραμματοκιβωτίου του χρήστη σε λειτουργία εκτός σύνδεσης στον τοπικό υπολογιστή κατά την εγγραφή με τον Exchange Server χρησιμοποιώντας το Microsoft Outlook. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/email/ost/). |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Τα αρχεία με επέκταση .pst αντιπροσωπεύουν τα Outlook Personal Storage Files (επίσης γνωστά ως Personal Storage Table) που αποθηκεύουν ποικιλία πληροφοριών χρήστη. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/email/pst/). |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Το Transport Neutral Encapsulation Format (TNEF) είναι ένα ιδιόκτητο μορφότυπο της Microsoft για την ενσωμάτωση συνημμένων email βασισμένο στο Messaging Application Programming Interface (MAPI). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/email/tnef/). |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | Το VCF (Virtual Card Format) ή vCard είναι ένα ψηφιακό μορφότυπο αρχείου για την αποθήκευση πληροφοριών επαφών. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/email/vcf/). |

### Σχόλια

Μάθετε περισσότερα για το μορφότυπο email [εδώ](https://docs.fileformat.com/email/).

### Δείτε επίσης

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
