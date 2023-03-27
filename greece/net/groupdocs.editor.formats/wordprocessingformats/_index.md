---
title: WordProcessingFormats
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Ενσωματώνει όλες τις μορφές επεξεργασίας κειμένου. Περιλαμβάνει τους ακόλουθους τύπους αρχείων Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . Μάθετε περισσότερα σχετικά με τις μορφές επεξεργασίας κειμένουεδώhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /el/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

Ενσωματώνει όλες τις μορφές επεξεργασίας κειμένου. Περιλαμβάνει τους ακόλουθους τύπους αρχείων: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . Μάθετε περισσότερα σχετικά με τις μορφές επεξεργασίας κειμένου[εδώ](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | Επιστρέφει μια επέκταση (χωρίς χαρακτήρα κύριας κουκκίδας) αυτής της μορφής WordProcessing σε πεζά |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | Επιστρέφει έναν κωδικό MIME για αυτήν τη μορφή |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | Επιστρέφει ένα επίσημο πλήρες όνομα αυτής της μορφής επεξεργασίας κειμένου |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Επιστρέφει την παρουσία του[`WordProcessingFormats`](../wordprocessingformats) δομή, συσχετίζεται με καθορισμένη επέκταση ονόματος αρχείου ή δημιουργεί μια εξαίρεση, εάν η επέκταση δεν μπορεί να αναλυθεί σωστά |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το άλλο καθορισμένο αντικείμενο, το οποίο είναι πιθανώς σε πλαίσιο WordProcessingFormats |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη περίπτωση WordProcessingFormats instance |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι αμετάβλητος για αυτήν την περίπτωση |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | Επιστρέφει το όνομα αυτής της συγκεκριμένης μορφής, όπως και η ιδιότητα "Όνομα" |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | Ελέγχει δύο δεδομένες περιπτώσεις WordProcessingFormats στο equality |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | Επιστρέφει μια τιμή byte από το υποκείμενο πεδίο του καθορισμένου WordProcessingFormats instance (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | Ελέγχει δύο δεδομένες περιπτώσεις WordProcessingFormats στο inequality |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | Το MS Word 97-2007 Μορφή δυαδικού αρχείου (DOC) αντιπροσωπεύει έγγραφα που δημιουργούνται από το Microsoft Word ή άλλα έγγραφα επεξεργασίας κειμένου σε μορφή δυαδικού αρχείου. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML Τα αρχεία εγγράφων με δυνατότητα μακροεντολής (DOCM) είναι έγγραφα του Microsoft Word 2007 ή νεότερης έκδοσης που δημιουργούνται με δυνατότητα εκτέλεσης μακροεντολών. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Το έγγραφο χωρίς μακροεντολή (DOCX) είναι μια πολύ γνωστή μορφή για έγγραφα του Microsoft Word. Παρουσιάστηκε από το 2007 με την κυκλοφορία του Microsoft Office 2007, η δομή αυτής της νέας μορφής εγγράφου άλλαξε από απλό δυαδικό σε συνδυασμό XML και δυαδικών αρχείων. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | Το MS Word 97-2007 Template είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προδιαμορφωμένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Το πρότυπο με δυνατότητα μακροεντολής (DOTM) αντιπροσωπεύει το αρχείο προτύπου που δημιουργήθηκε με Microsoft Word 2007 ή νεότερη έκδοση. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Πρότυπο χωρίς μακροεντολή (DOTX) είναι αρχεία προτύπων που δημιουργήθηκαν από το Microsoft Word για να έχουν προδιαμορφωμένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML αποθηκευμένο σε επίπεδο αρχείο XML αντί για πακέτο ZIP |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Τα αρχεία εγγράφου κειμένου ανοιχτής μορφής εγγράφου (ODT) είναι τύποι εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου που βασίζονται στη μορφή αρχείου κειμένου OpenDocument. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | OpenDocument Format Text Document Template (OTT) αντιπροσωπεύει έγγραφα προτύπου που δημιουργούνται από εφαρμογές σε συμμόρφωση με την τυπική μορφή OpenDocument του OASIS. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Η Μορφή εμπλουτισμένου κειμένου (RTF) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Μορφή XML Microsoft Office Word 2003 — WordProcessingML ή WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | Επιστρέφει μια εσωτερική κλάση, η οποία παρέχει αναρίθμητες δυνατότητες σε όλες τις υπάρχουσες μορφές επεξεργασίας κειμένου |

## Άλλα Μέλη

| Ονομα | Περιγραφή |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | Υλοποιεί IEnumerable γενική διεπαφή, που επιτρέπει μια δυνατότητα «foreach» για το WordProcessingFormats type |

### Παρατηρήσεις

Οι κωδικοί MIME λαμβάνονται από τους δεδομένους πόρους: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### Δείτε επίσης

* interface [IDocumentFormat](../idocumentformat)
* χώρος ονομάτων [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
