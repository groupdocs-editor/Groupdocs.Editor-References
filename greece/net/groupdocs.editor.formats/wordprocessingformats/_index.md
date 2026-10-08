---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Περιλαμβάνει όλες τις μορφές WordProcessing. Περιλαμβάνει τους παρακάτω τύπους αρχείων"
type: docs
weight: 150
url: /el/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

Περιλαμβάνει όλες τις μορφές Επεξεργασίας Κειμένου. Συμπεριλαμβάνει τους ακόλουθους τύπους αρχείων:

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

Μάθετε περισσότερα για τις μορφές Επεξεργασίας Κειμένου [εδώ](https://wiki.fileformat.com/word-processing).

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## Properties

| Name | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Λαμβάνει την επέκταση αρχείου της μορφής εγγράφου. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Λαμβάνει την οικογένεια μορφής στην οποία ανήκει η μορφή εγγράφου. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Λαμβάνει το μοναδικό αναγνωριστικό για την οικογένεια μορφής. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Λαμβάνει τον τύπο MIME της μορφής εγγράφου. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Λαμβάνει το όνομα της οικογένειας μορφής. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | Λαμβάνει μια επαναληπτική συλλογή όλων των [`WordProcessingFormats`](../wordprocessingformats). |

## Methods

| Name | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου [`WordProcessingFormats`](../wordprocessingformats) που έχει την καθορισμένη επέκταση αρχείου. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [`WordProcessingFormats`](../wordprocessingformats). |

## Πεδία

| Name | Περιγραφή |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | Δυαδική Μορφή Αρχείου MS Word 97-2007 (DOC) αντιπροσωπεύει έγγραφα που δημιουργήθηκαν από το Microsoft Word ή άλλα έγγραφα επεξεργασίας κειμένου σε δυαδική μορφή. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Τα αρχεία Office Open XML WordProcessingML Macro-Enabled Document (DOCM) είναι έγγραφα που δημιουργούνται από το Microsoft Word 2007 ή νεότερο με δυνατότητα εκτέλεσης μακροεντολών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Το Office Open XML WordProcessingML Macro-Free Document (DOCX) είναι μια ευρέως γνωστή μορφή για έγγραφα Microsoft Word. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | Το MS Word 97-2007 Template (DOT) είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προ-μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Το Office Open XML WordprocessingML Macro-Enabled Template (DOTM) αντιπροσωπεύει αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Word 2007 ή νεότερο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Το Office Open XML WordprocessingML Macro-Free Template (DOTX) είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προ-μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Το Office Open XML WordprocessingML αποθηκεύεται σε ένα επίπεδο αρχείο XML αντί για πακέτο ZIP. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Τα αρχεία Open Document Format Text Document (ODT) είναι τύπος εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου που βασίζονται στη μορφή αρχείου OpenDocument Text. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Το Open Document Format Text Document Template (OTT) αντιπροσωπεύει έγγραφα προτύπων που δημιουργούνται από εφαρμογές σύμφωνα με το πρότυπο OpenDocument του OASIS. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Το Rich Text Format (RTF) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML Format — WordProcessingML ή WordML (.XML). |

### Δείτε επίσης

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
