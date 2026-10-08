---
title: "TextualFormats"
second_title: "GroupDocs.Editor για .NET αναφορά API"
description: "Περιλαμβάνει όλες τις κειμενικές μορφές βασισμένες σε κείμενο, συμπεριλαμβανομένων των σήμανσης XML HTML και άλλων. Περιλαμβάνει τις ακόλουθες μορφές Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /el/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

Περιλαμβάνει όλες τις κειμενικές (βασισμένες σε κείμενο) μορφές, συμπεριλαμβανομένης της σήμανσης (XML, HTML) και άλλων. Περιλαμβάνει τις ακόλουθες μορφές: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## Properties

| Name | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Λαμβάνει την επέκταση αρχείου της μορφής εγγράφου. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Λαμβάνει την οικογένεια μορφής στην οποία ανήκει η μορφή εγγράφου. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Λαμβάνει το μοναδικό αναγνωριστικό για την οικογένεια μορφής. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Λαμβάνει τον τύπο MIME της μορφής εγγράφου. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Λαμβάνει το όνομα της οικογένειας μορφής. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | Λαμβάνει μια επαναλήψιμη συλλογή όλων των [`TextualFormats`](../textualformats). |

## Methods

| Name | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Ανακτά ένα παράδειγμα του καθορισμένου τύπου [`TextualFormats`](../textualformats) που έχει την καθορισμένη επέκταση αρχείου. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Καθορίζει εάν αυτό το παράδειγμα είναι ίσο με το καθορισμένο παράδειγμα [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [`TextualFormats`](../textualformats). |

## Πεδία

| Name | Περιγραφή |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Το Microsoft Compiled HTML Help είναι ένα ιδιόκτητο δυαδικό μορφότυπο online βοήθειας της Microsoft, που αποτελείται από μια συλλογή σελίδων HTML, ένα ευρετήριο και άλλα εργαλεία πλοήγησης. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | Το έγγραφο HyperText Markup Language (HTML) είναι η επέκταση για ιστοσελίδες που δημιουργούνται για προβολή σε προγράμματα περιήγησης. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | Το JSON (JavaScript Object Notation) είναι ένα ανοιχτό πρότυπο μορφότυπο αρχείου για ανταλλαγή δεδομένων που χρησιμοποιεί κείμενο αναγνώσιμο από άνθρωπο για αποθήκευση και μετάδοση δεδομένων. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Το Markdown είναι μια ελαφριά γλώσσα σήμανσης για δημιουργία μορφοποιημένου κειμένου χρησιμοποιώντας έναν επεξεργαστή απλού κειμένου. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | Η ενσωμάτωση MIME συγκεντρωτικών εγγράφων HTML είναι μια μορφή αρχειοθέτησης ιστοσελίδων που χρησιμοποιείται για τη συνένωση, σε ένα ενιαίο αρχείο υπολογιστή, του κώδικα HTML και των συνοδευτικών πόρων του. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Το Απλό Κείμενο Έγγραφο (TXT) αντιπροσωπεύει ένα έγγραφο κειμένου που περιέχει απλό κείμενο με μορφή γραμμών. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | Έγγραφο eXtensible Markup Language (XML) που είναι παρόμοιο με το HTML αλλά διαφέρει στη χρήση ετικετών για τον ορισμό αντικειμένων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://wiki.fileformat.com/web/xml). |

### Δείτε επίσης

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
