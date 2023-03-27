---
title: EmailFormats
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Ενσωματώνει όλες τις μορφές email. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Tnef./emailformats/tnef  Eml./emailformats/eml  Emlx./emailformats/emlx  Msg./emailformats/msg  Html./emailformats/html  Mhtml./emailformats/mhtml .
type: docs
weight: 60
url: /el/net/groupdocs.editor.formats/emailformats/
---
## EmailFormats structure

Ενσωματώνει όλες τις μορφές email. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Tnef`](./tnef) , [`Eml`](./eml) , [`Emlx`](./emlx) , [`Msg`](./msg) , [`Html`](./html) , [`Mhtml`](./mhtml) .

```csharp
public struct EmailFormats : IDocumentFormat, IEquatable<EmailFormats>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/emailformats/extension) { get; } | Κατά την υλοποίηση του τύπου θα πρέπει να επιστρέψει την επέκταση αρχείου μορφής (χωρίς τον χαρακτήρα της κύριας κουκκίδας). |
| [Mime](../../groupdocs.editor.formats/emailformats/mime) { get; } | Κατά την υλοποίηση του τύπου θα πρέπει να επιστρέψει έναν κωδικό MIME για τη δεδομένη μορφή |
| [Name](../../groupdocs.editor.formats/emailformats/name) { get; } | Στον τύπο υλοποίησης θα πρέπει να επιστρέψει την πλήρη επίσημη μορφή name |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/emailformats/fromextension)(string) | Επιστρέφει την παρουσία του[`EmailFormats`](../emailformats) δομή, συσχετίζεται με καθορισμένη επέκταση ονόματος αρχείου ή δημιουργεί μια εξαίρεση, εάν η επέκταση δεν μπορεί να αναλυθεί σωστά |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals)(EmailFormats) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη παρουσία email |
| [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_1)(IDocumentFormat) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/emailformats/equals#equals_2)(object) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το άλλο καθορισμένο αντικείμενο, που πιθανώς είναι του κουτιού Email |
| override [GetHashCode](../../groupdocs.editor.formats/emailformats/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι αμετάβλητος για αυτήν την περίπτωση |
| override [ToString](../../groupdocs.editor.formats/emailformats/tostring)() | Επιστρέφει ένα όνομα μορφής αυτής της μορφής |
| [operator ==](../../groupdocs.editor.formats/emailformats/op_equality) | Ελέγχει δύο δεδομένες περιπτώσεις ηλεκτρονικού ταχυδρομείου για την ισοτιμία |
| [operator !=](../../groupdocs.editor.formats/emailformats/op_inequality) | Ελέγχει δύο δεδομένες περιπτώσεις ηλεκτρονικού ταχυδρομείου σχετικά με την ανισότητα |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [Eml](../../groupdocs.editor.formats/emailformats/eml) | Η μορφή αρχείου EML αντιπροσωπεύει μηνύματα email που έχουν αποθηκευτεί με χρήση του Outlook και άλλων σχετικών εφαρμογών. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/email/eml/) . |
| static readonly [Emlx](../../groupdocs.editor.formats/emailformats/emlx) | Η μορφή αρχείου EMX υλοποιείται και αναπτύσσεται από την Apple. Η εφαρμογή Apple Mail χρησιμοποιεί τη μορφή αρχείου EMLX για την εξαγωγή των email. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/email/emlx/) . |
| static readonly [Html](../../groupdocs.editor.formats/emailformats/html) | email με μορφή HTML. |
| static readonly [Ics](../../groupdocs.editor.formats/emailformats/ics) | Η Προδιαγραφή Βασικού Αντικειμένου Ημερολογίου και Προγραμματισμού Διαδικτύου (iCalendar) είναι ένα πρότυπο Διαδικτύου (RFC 2445) για την ανταλλαγή και την ανάπτυξη των συμβάντων ημερολογίου και του προγραμματισμού. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/email/ics/) . |
| static readonly [Mbox](../../groupdocs.editor.formats/emailformats/mbox) | Η μορφή αρχείου MBox είναι ένας γενικός όρος που αντιπροσωπεύει ένα κοντέινερ για συλλογή μηνυμάτων ηλεκτρονικού ταχυδρομείου. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/email/mbox/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/emailformats/mhtml) | MHTML, μια αρχικοποίηση της "ενθυλάκωσης MIME συγκεντρωτικών εγγράφων HTML" |
| static readonly [Msg](../../groupdocs.editor.formats/emailformats/msg) | Το MSG είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων email, επαφών, συναντήσεων ή άλλων εργασιών. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/email/msg/) . |
| static readonly [Oft](../../groupdocs.editor.formats/emailformats/oft) | Τα αρχεία με επέκταση .oft είναι αρχεία προτύπων που δημιουργούνται χρησιμοποιώντας το Microsoft Outlook. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/email/oft/) . |
| static readonly [Ost](../../groupdocs.editor.formats/emailformats/ost) | Το αρχείο Πίνακας αποθήκευσης εκτός σύνδεσης (OST) αντιπροσωπεύει τα δεδομένα γραμματοκιβωτίου του χρήστη σε λειτουργία εκτός σύνδεσης σε τοπικό μηχάνημα κατά την εγγραφή στον Exchange Server χρησιμοποιώντας το Microsoft Outlook. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/email/ost/) . |
| static readonly [Pst](../../groupdocs.editor.formats/emailformats/pst) | Τα αρχεία με επέκταση .pst αντιπροσωπεύουν τα προσωπικά αρχεία αποθήκευσης του Outlook (ονομάζονται επίσης Personal Storage Table) που αποθηκεύουν ποικιλία πληροφοριών χρήστη. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/email/pst/) . |
| static readonly [Tnef](../../groupdocs.editor.formats/emailformats/tnef) | Το Transport Neutral Encapsulation Format (TNEF) είναι ιδιόκτητο της Microsoft, για την ενθυλάκωση συνημμένων email με βάση τη διεπαφή προγραμματισμού εφαρμογών μηνυμάτων (MAPI). Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/email/tnef/) . |
| static readonly [Vcf](../../groupdocs.editor.formats/emailformats/vcf) | Το VCF (Virtual Card Format) ή vCard είναι μια ψηφιακή μορφή αρχείου για την αποθήκευση πληροφοριών επικοινωνίας. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/email/vcf/) . |
| static readonly [All](../../groupdocs.editor.formats/emailformats/all) | Επιστρέφει μια εσωτερική κλάση, που παρέχει αναρίθμητες δυνατότητες σε όλες τις υπάρχουσες μορφές email |

## Άλλα Μέλη

| Ονομα | Περιγραφή |
| --- | --- |
| class [AllEnumerable](emailformats.allenumerable) | Εφαρμόζει IEnumerable γενική διεπαφή, που επιτρέπει τη δυνατότητα 'foreach' για τον τύπο email |

### Παρατηρήσεις

Μάθετε περισσότερα σχετικά με τη μορφή μηνυμάτων ηλεκτρονικού ταχυδρομείου[εδώ](https://docs.fileformat.com/email/) .

### Δείτε επίσης

* interface [IDocumentFormat](../idocumentformat)
* χώρος ονομάτων [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
