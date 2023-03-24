---
title: PresentationFormats
second_title: GroupDocs.Editor για Αναφορά API .NET
description: Ενσωματώνει όλες τις μορφές παρουσίασης. Περιλαμβάνει τις ακόλουθες μορφές Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. Μάθετε περισσότερα σχετικά με τις μορφές παρουσίασηςεδώhttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /el/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

Ενσωματώνει όλες τις μορφές παρουσίασης. Περιλαμβάνει τις ακόλουθες μορφές: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). Μάθετε περισσότερα σχετικά με τις μορφές παρουσίασης[εδώ](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | Επιστρέφει μια επέκταση (χωρίς χαρακτήρα κύριας κουκκίδας) αυτής της μορφής παρουσίασης σε πεζά |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | Επιστρέφει έναν κωδικό MIME για αυτήν τη μορφή |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | Επιστρέφει ένα επίσημο πλήρες όνομα αυτής της μορφής παρουσίασης |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Επιστρέφει την παρουσία του[`PresentationFormats`](../presentationformats) δομή, συσχετίζεται με καθορισμένη επέκταση ονόματος αρχείου ή δημιουργεί μια εξαίρεση, εάν η επέκταση δεν μπορεί να αναλυθεί σωστά |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη IDocumentFormat instance |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το άλλο καθορισμένο αντικείμενο, που πιθανώς είναι του κουτιού PresentationFormats |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη καθορισμένη παρουσίαση Formats instance |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι αμετάβλητος για αυτήν την περίπτωση |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | Ελέγχει δύο δεδομένες παρουσίες PresentationFormats στο equality |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | Ελέγχει δύο δεδομένες παρουσίες PresentationFormats στο inequality |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | Το αρχείο OpenDocument Presentation (ODP) αντιπροσωπεύει τη μορφή αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASISOpen. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | Το αρχείο προτύπου παρουσίασης OpenDocument (OTP) αντιπροσωπεύει αρχεία προτύπων παρουσίασης που έχουν δημιουργηθεί από εφαρμογές σε τυπική μορφή OASIS OpenDocument. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Το αρχείο προτύπου παρουσίασης (POT) του Microsoft PowerPoint 97-2003 αντιπροσωπεύει τα αρχεία προτύπων του Microsoft PowerPoint που δημιουργήθηκαν από τις εκδόσεις του PowerPoint 97-2003. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Template με δυνατότητα μακροεντολής (POTM) είναι αρχεία με υποστήριξη για μακροεντολές. Τα αρχεία POTM δημιουργούνται με PowerPoint 2007 ή νεότερη έκδοση και περιέχουν προεπιλεγμένες ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία περαιτέρω αρχείων παρουσίασης. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Αρχείο Πρότυπο χωρίς μακροεντολή (POTX) αντιπροσωπεύει παρουσιάσεις προτύπων Microsoft PowerPoint που δημιουργούνται με το Microsoft PowerPoint 2007 και μεταγενέστερη έκδοση. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Τα αρχεία Παρουσίασης Παρουσίασης (PPS) του Microsoft PowerPoint 97-2003 δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint για σκοπούς προβολής διαφανειών. Η ανάγνωση και η δημιουργία αρχείων PPS υποστηρίζεται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Τα αρχεία Slideshow (PPSM) με δυνατότητα μακροεντολής δημιουργούνται με Microsoft PowerPoint 2007 ή νεότερη έκδοση. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Το αρχείο παρουσίασης παρουσίασης χωρίς μακροεντολή (PPSX) δημιουργείται χρησιμοποιώντας το Microsoft PowerPoint 2007 και νεότερη έκδοση για σκοπούς προβολής διαφανειών. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | Η Παρουσίαση PowerPoint (.ppt) αντιπροσωπεύει το αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για εμφάνιση ως Παρουσίαση. Καθορίζει τη μορφή δυαδικού αρχείου που χρησιμοποιείται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Παρουσίαση Microsoft PowerPoint 95 (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Αρχεία εγγράφου με δυνατότητα μακροεντολής (PPTM) του Microsoft Office Open XML Presentation που δημιουργούνται με Microsoft PowerPoint 2007 ή νεότερες εκδόσεις. Μοιάζουν με τα αρχεία PPTX με τη διαφορά ότι το πλευρικό δεν μπορεί να εκτελέσει μακροεντολές αν και μπορεί να περιέχει μακροεντολές. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | Η PowerPoint Open XML Presentation (.pptx) είναι ένα αρχείο παρουσίασης που δημιουργήθηκε με τη δημοφιλή εφαρμογή Microsoft PowerPoint. Σε αντίθεση με την προηγούμενη έκδοση της μορφής αρχείου παρουσίασης PPT που ήταν δυαδική, η μορφή PPTX βασίζεται στη μορφή αρχείου παρουσίασης ανοιχτής XML του Microsoft PowerPoint. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | Επιστρέφει μια εσωτερική κλάση, που παρέχει αναρίθμητες δυνατότητες σε όλες τις υπάρχουσες μορφές παρουσίασης |

## Άλλα Μέλη

| Ονομα | Περιγραφή |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | Υλοποιεί IEnumerable γενική διεπαφή, που επιτρέπει μια δυνατότητα «foreach» για το PresentationFormats type |

### Δείτε επίσης

* interface [IDocumentFormat](../idocumentformat)
* χώρος ονομάτων [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* συνέλευση [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
