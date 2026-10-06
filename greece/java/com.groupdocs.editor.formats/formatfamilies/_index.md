---
title: "FormatFamilies"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει τις διαφορετικές οικογένειες μορφών που είναι διαθέσιμες στο σύστημα."
type: docs
weight: 13
url: /el/java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

Αντιπροσωπεύει τις διαφορετικές οικογένειες μορφών που είναι διαθέσιμες στο σύστημα.

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [EBook](#EBook) | Αναπαριστά την οικογένεια μορφής eBook. |
|
|  | [Email](#Email) | Αναπαριστά την οικογένεια μορφής Email. |
|
|  | [FixedLayout](#FixedLayout) | Αναπαριστά την οικογένεια μορφής Fixed Layout. |
|
|  | [Presentation](#Presentation) | Αναπαριστά την οικογένεια μορφής Presentation. |
|
|  | [Spreadsheet](#Spreadsheet) | Αναπαριστά την οικογένεια μορφής Spreadsheet. |
|
|  | [Textual](#Textual) | Αναπαριστά την οικογένεια μορφής Textual. |
|
|  | [WordProcessing](#WordProcessing) | Αναπαριστά την οικογένεια μορφής Word Processing. |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


Αναπαριστά την οικογένεια μορφής eBook.
Μάθετε περισσότερα για τη μορφή Mobi
[here](../https://docs.fileformat.com/ebook/mobi/)
,
σχετικά με τη μορφή AZW3
[here](../https://docs.fileformat.com/ebook/azw3/)
,
και σχετικά με τη μορφή ePub
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


Αναπαριστά την οικογένεια μορφής Email.
Μάθετε περισσότερα για τη μορφή email
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Αναπαριστά την οικογένεια μορφής Fixed Layout.
Διάφορες εφαρμογές προβολής ή δημοσίευσης εγγράφων επιτρέπουν στους χρήστες να ανοίγουν (Adobe Acrobat, XPS Viewer) και μερικές φορές να επεξεργάζονται (Adobe InDesign) έγγραφα συγκεκριμένων μορφών.
Αυτές οι εφαρμογές συνήθως παράγουν τα λεγόμενα “fixed-page” έγγραφα μορφής.
Μια τέτοια μορφή εγγράφου περιγράφει ακριβώς πού το περιεχόμενο ενός εγγράφου τοποθετείται σε κάθε σελίδα.
Εσωτερικά, η μορφή PDF ή XPS περιέχει περιγραφή κάθε σελίδας, καθώς και οδηγίες σχεδίασης, που καθορίζουν τη διάταξη του περιεχομένου στη σελίδα.
Αυτό είναι παρόμοιο με τις μορφές εικόνας, περιγράφοντας πού εμφανίζεται το περιεχόμενο είτε σε raster είτε σε διανυσματική μορφή.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Αναπαριστά την οικογένεια μορφής Presentation.
Μάθετε περισσότερα για τις μορφές Παρουσίασης.
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Αναπαριστά την οικογένεια μορφής Spreadsheet.
Όλες οι δυαδικές, XML και κειμενικές μορφές Φύλλων Εργασίας (εξαιρουμένων όλων των κειμενικών μορφών που βασίζονται σε διαχωριστικά όπως CSV, TSV, διαχωρισμένα με ερωτηματικό κ.λπ.), στις οποίες μπορεί να αποθηκευτεί το βιβλίο εργασίας.


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Αναπαριστά την οικογένεια μορφής Textual.
Περιλαμβάνει όλες τις κειμενικές (βασισμένες σε κείμενο) μορφές, συμπεριλαμβανομένων των σήμανσης (XML, HTML) και άλλων.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Αναπαριστά την οικογένεια μορφής Word Processing.
Μάθετε περισσότερα για τις μορφές Επεξεργασίας Κειμένου.
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

Οι κωδικοί MIME λαμβάνονται από τους παρακάτω πόρους: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



