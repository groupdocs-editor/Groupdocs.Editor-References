---
title: "EBookFormats"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Περιλαμβάνει όλες τις μορφές eBook."
type: docs
weight: 10
url: /el/java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

Περιλαμβάνει όλες τις μορφές eBook. Συμπεριλαμβάνει τους ακόλουθους τύπους αρχείων:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Μάθετε περισσότερα για τη μορφή Mobi [εδώ](../https://docs.fileformat.com/ebook/mobi/), και για τη μορφή ePub [εδώ](../https://docs.fileformat.com/ebook/epub/).

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Mobi](#Mobi) | Το MOBI είναι το όνομα που δόθηκε στη μορφή που αναπτύχθηκε για το MobiPocket Reader. |
|
|  | [Epub](#Epub) | Η μορφή Electronic Publication (IDPF ePub) είναι μια μορφή αρχείου e‑book που παρέχει ένα τυπικό ψηφιακό φορμά δημοσίευσης για εκδότες και καταναλωτές. |
|
|  | [Azw3](#Azw3) | Το AZW3, επίσης γνωστό ως Kindle Format 8 (KF8), είναι η τροποποιημένη έκδοση της ψηφιακής μορφής αρχείου ebook AZW που αναπτύχθηκε για συσκευές Amazon Kindle. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAll()](#getAll--) | Λαμβάνει μια επαναλήψιμη συλλογή όλων των [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ανακτά μια παρουσία του καθορισμένου τύπου [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) που έχει την καθορισμένη επέκταση αρχείου. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


Το MOBI είναι το όνομα που δόθηκε στη μορφή που αναπτύχθηκε για το MobiPocket Reader. Επίσης ονομάζεται PRC, AZW.
Αυτή τη στιγμή χρησιμοποιείται από την Amazon με ελαφρώς διαφορετικό σχήμα DRM και ονομάζεται AZW.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Η μορφή Electronic Publication (IDPF ePub) είναι μια μορφή αρχείου e‑book που παρέχει ένα τυπικό ψηφιακό φορμά δημοσίευσης για εκδότες και καταναλωτές.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


Το AZW3, επίσης γνωστό ως Kindle Format 8 (KF8), είναι η τροποποιημένη έκδοση της ψηφιακής μορφής αρχείου ebook AZW που αναπτύχθηκε για συσκευές Amazon Kindle.
Η μορφή είναι μια βελτίωση των παλαιότερων αρχείων AZW.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


Λαμβάνει μια επαναλήψιμη συλλογή όλων των [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).
Τιμή: Μια  IEnumerable{EBookFormats}  που περιέχει όλες τις παρουσίες του [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Ανακτά μια παρουσία του καθορισμένου τύπου [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) που έχει την καθορισμένη επέκταση αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | extension | java.lang.String | Η επέκταση αρχείου της μορφής εγγράφου. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | extension | java.lang.String | Η κατάληξη αρχείου για μετατροπή. Εάν η κατάληξη περιέχει πολλαπλές τελείες, χρησιμοποιείται το τμήμα μετά την τελευταία τελεία. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

