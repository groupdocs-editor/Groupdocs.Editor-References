---
title: FixedLayoutFormats
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Ενσωματώνει όλες τις μορφές σταθερής διάταξης γνωστές και ως σταθερή σελίδα οι οποίες περιλαμβάνουν PDF και XPS αυτό δεν περιλαμβάνει εικόνες ράστερ
type: docs
weight: 80
url: /el/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats structure

Ενσωματώνει όλες τις μορφές σταθερής διάταξης (γνωστές και ως "σταθερή σελίδα"), οι οποίες περιλαμβάνουν PDF και XPS (αυτό δεν περιλαμβάνει εικόνες ράστερ)

```csharp
public struct FixedLayoutFormats : IDocumentFormat, IEquatable<FixedLayoutFormats>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/fixedlayoutformats/extension) { get; } | Επιστρέφει μια επέκταση (χωρίς χαρακτήρα κουκκίδας) αυτής της μορφής σταθερής διάταξης σε πεζά |
| [Mime](../../groupdocs.editor.formats/fixedlayoutformats/mime) { get; } | Επιστρέφει έναν κωδικό MIME για αυτήν τη μορφή |
| [Name](../../groupdocs.editor.formats/fixedlayoutformats/name) { get; } | Επιστρέφει ένα επίσημο πλήρες όνομα αυτής της σταθερής διάταξης format |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Επιστρέφει την παρουσία του[`FixedLayoutFormats`](../fixedlayoutformats) δομή, συσχετίζεται με καθορισμένη επέκταση ονόματος αρχείου ή δημιουργεί μια εξαίρεση, εάν η επέκταση δεν μπορεί να αναλυθεί σωστά |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals)(FixedLayoutFormats) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το άλλο καθορισμένο FixedLayoutFormats instance |
| [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_1)(IDocumentFormat) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/fixedlayoutformats/equals#equals_2)(object) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το άλλο καθορισμένο αντικείμενο, το οποίο πιθανώς είναι του κουτιού FixedLayoutFormats |
| override [GetHashCode](../../groupdocs.editor.formats/fixedlayoutformats/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι αμετάβλητος για αυτήν την περίπτωση |
| override [ToString](../../groupdocs.editor.formats/fixedlayoutformats/tostring)() | Επιστρέφει το όνομα αυτής της συγκεκριμένης μορφής, όπως και η ιδιότητα "Όνομα" |
| [operator ==](../../groupdocs.editor.formats/fixedlayoutformats/op_equality) | Ελέγχει δύο δεδομένες περιπτώσεις FixedLayoutFormats στο equality |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit#op_explicit) | Επιστρέφει μια τιμή byte από το υποκείμενο πεδίο του καθορισμένου FixedLayoutFormats instance (2 operators) |
| [operator !=](../../groupdocs.editor.formats/fixedlayoutformats/op_inequality) | Ελέγχει δύο δεδομένες περιπτώσεις FixedLayoutFormats στο inequality |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Το Portable Document Format (PDF) είναι ένας τύπος εγγράφου που δημιουργήθηκε από την Adobe στη δεκαετία του 1990. Ο σκοπός αυτής της μορφής αρχείου ήταν να εισαγάγει ένα πρότυπο για την αναπαράσταση εγγράφων και άλλου υλικού αναφοράς σε μορφή που είναι ανεξάρτητη από το λογισμικό εφαρμογής, το υλικό καθώς και το λειτουργικό σύστημα. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/pdf/) . |
| static readonly [Xps](../../groupdocs.editor.formats/fixedlayoutformats/xps) | Το αρχείο XPS αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται σε Προδιαγραφές χαρτιού XML που δημιουργήθηκαν από τη Microsoft. Αναπτύχθηκε ως αντικατάσταση της μορφής αρχείου EMF και είναι παρόμοια με τη μορφή αρχείου PDF, αλλά χρησιμοποιεί XML στη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/page-description-language/xps/) . |
| static readonly [All](../../groupdocs.editor.formats/fixedlayoutformats/all) | Επιστρέφει μια εσωτερική κλάση, που παρέχει αναρίθμητες δυνατότητες σε όλες τις υπάρχουσες μορφές σταθερής διάταξης |

## Άλλα Μέλη

| Ονομα | Περιγραφή |
| --- | --- |
| class [AllEnumerable](fixedlayoutformats.allenumerable) | Υλοποιεί IEnumerable γενική διεπαφή, που επιτρέπει μια δυνατότητα «foreach» για το FixedLayoutFormats type |

### Παρατηρήσεις

Διάφορες εφαρμογές προβολής ή δημοσίευσης εγγράφων επιτρέπουν στους χρήστες να ανοίγουν (Adobe Acrobat, XPS Viewer) και μερικές φορές να επεξεργάζονται (Adobe InDesign) έγγραφα συγκεκριμένων μορφών. Αυτές οι εφαρμογές συνήθως παράγουν τα λεγόμενα έγγραφα μορφής «σταθερής σελίδας». Μια τέτοια μορφή εγγράφου περιγράφει ακριβώς πού τοποθετείται το περιεχόμενο ενός εγγράφου σε κάθε σελίδα. Εσωτερικά, η μορφή PDF ή XPS περιέχει μια περιγραφή κάθε σελίδας, καθώς και οδηγίες σχεδίασης, καθορίζοντας τη διάταξη του περιεχομένου στη σελίδα. Αυτό είναι παρόμοιο με τις μορφές εικόνας, που περιγράφει πού εμφανίζεται το περιεχόμενο είτε σε μορφή ράστερ είτε σε διανυσματική μορφή.

### Δείτε επίσης

* interface [IDocumentFormat](../idocumentformat)
* χώρος ονομάτων [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
