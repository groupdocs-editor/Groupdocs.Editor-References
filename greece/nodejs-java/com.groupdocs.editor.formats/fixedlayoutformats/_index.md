---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Περιλαμβάνει όλες τις μορφές σταθερής διάταξης, επίσης γνωστές ως μορφές σταθερής σελίδας, που περιλαμβάνουν PDF και XPS· αυτό δεν περιλαμβάνει εικόνες raster."
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

Περιλαμβάνει όλες τις μορφές σταθερής διάταξης (γνωστές επίσης ως "fixed-page"), που περιλαμβάνουν PDF και XPS (αυτό δεν περιλαμβάνει ραστερ εικόνες)

<br />

*** ** * ** ***

Διάφορες εφαρμογές προβολής ή δημοσίευσης εγγράφων επιτρέπουν στους χρήστες να ανοίγουν (Adobe Acrobat, XPS Viewer) και μερικές φορές να επεξεργάζονται (Adobe InDesign) έγγραφα συγκεκριμένων μορφών. Αυτές οι εφαρμογές συνήθως παράγουν τα λεγόμενα \u201cfixed-page\u201d έγγραφα μορφής. Μια τέτοια μορφή εγγράφου περιγράφει με ακρίβεια πού το περιεχόμενο ενός εγγράφου τοποθετείται σε κάθε σελίδα. Εσωτερικά, η μορφή PDF ή XPS περιέχει περιγραφή κάθε σελίδας, καθώς και οδηγίες σχεδίασης, που καθορίζουν τη διάταξη του περιεχομένου στη σελίδα. Αυτό είναι παρόμοιο με τις μορφές εικόνας, περιγράφοντας πού εμφανίζεται το περιεχόμενο είτε σε raster είτε σε διανυσματική μορφή.

<br />


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Pdf](#Pdf) | Το Portable Document Format (PDF) είναι ένας τύπος εγγράφου που δημιουργήθηκε από την Adobe τη δεκαετία του 1990. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAll()](#getAll--) | Λαμβάνει μια συλλογή με δυνατότητα επανάληψης όλων των [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ανακτά μια παρουσία του καθορισμένου τύπου [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) που έχει την καθορισμένη επέκταση αρχείου. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει επέκταση αρχείου σε αντικείμενο [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Το Portable Document Format (PDF) είναι ένας τύπος εγγράφου που δημιουργήθηκε από την Adobe τη δεκαετία του 1990. Ο σκοπός αυτού του μορφότυπου αρχείου ήταν η εισαγωγή ενός προτύπου για την αναπαράσταση εγγράφων και άλλου υλικού αναφοράς σε μορφή που είναι ανεξάρτητη από λογισμικό εφαρμογών, υλικό καθώς και λειτουργικό σύστημα.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Λαμβάνει μια συλλογή με δυνατότητα επανάληψης όλων των [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).
Τιμή: Μια IEnumerable{FixedLayoutFormats} που περιέχει όλες τις περιπτώσεις του [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Ανακτά μια παρουσία του καθορισμένου τύπου [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) που έχει την καθορισμένη επέκταση αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | επέκταση | java.lang.String | Η επέκταση αρχείου της μορφής εγγράφου. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει επέκταση αρχείου σε αντικείμενο [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | επέκταση | java.lang.String | Η επέκταση αρχείου για μετατροπή. Εάν η επέκταση περιέχει πολλαπλές τελείες, χρησιμοποιείται το τμήμα μετά την τελευταία τελεία. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

