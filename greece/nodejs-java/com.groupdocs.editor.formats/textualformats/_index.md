---
title: "TextualFormats"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Περιλαμβάνει όλες τις κειμενικές μορφές βασισμένες σε κείμενο, συμπεριλαμβανομένων των μορφών σήμανσης XML, HTML και άλλων."
type: docs
weight: 16
url: /el/nodejs-java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

Περιλαμβάνει όλες τις κειμενικές (βασισμένες σε κείμενο) μορφές, συμπεριλαμβανομένων των γλωσσών σήμανσης (XML, HTML) και άλλων.
Περιλαμβάνει τις ακόλουθες μορφές:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Html](#Html) | Το έγγραφο HyperText Markup Language (HTML) είναι η επέκταση για ιστοσελίδες που δημιουργούνται για προβολή σε προγράμματα περιήγησης. |
|
|  | [Xml](#Xml) | Το έγγραφο eXtensible Markup Language (XML) είναι παρόμοιο με το HTML αλλά διαφέρει στη χρήση ετικετών για τον ορισμό αντικειμένων. |
|
|  | [Txt](#Txt) | Το έγγραφο Plain Text (TXT) αντιπροσωπεύει ένα κειμενικό έγγραφο που περιέχει απλό κείμενο με τη μορφή γραμμών. |
|
|  | [Md](#Md) | Το Markdown είναι μια ελαφριά γλώσσα σήμανσης για τη δημιουργία μορφοποιημένου κειμένου χρησιμοποιώντας έναν επεξεργαστή απλού κειμένου. |
|
|  | [Json](#Json) | Το JSON (JavaScript Object Notation) είναι ένα ανοιχτό πρότυπο μορφής αρχείου για την ανταλλαγή δεδομένων που χρησιμοποιεί κείμενο αναγνώσιμο από άνθρωπο για την αποθήκευση και μετάδοση των δεδομένων. |
|
|  | [Mhtml](#Mhtml) | Η ενσωμάτωση MIME συγκεντρωτικών εγγράφων HTML είναι μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που χρησιμοποιείται για τη συνένωση, σε ένα ενιαίο αρχείο υπολογιστή, του κώδικα HTML και των συνοδευτικών πόρων του. |
|
|  | [Chm](#Chm) | Το Microsoft Compiled HTML Help είναι μια ιδιόκτητη δυαδική μορφή online βοήθειας της Microsoft, που αποτελείται από μια συλλογή σελίδων HTML, ένα ευρετήριο και άλλα εργαλεία πλοήγησης. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAll()](#getAll--) | Λαμβάνει μια συλλογή με δυνατότητα επανάληψης όλων των [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ανακτά μια παρουσία του καθορισμένου τύπου [TextualFormats](../../com.groupdocs.editor.formats/textualformats) που έχει την καθορισμένη επέκταση αρχείου. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
### Html {#Html}
```
public static final TextualFormats Html
```


Το έγγραφο HyperText Markup Language (HTML) είναι η επέκταση για ιστοσελίδες που δημιουργούνται για προβολή σε προγράμματα περιήγησης.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


Το έγγραφο eXtensible Markup Language (XML) είναι παρόμοιο με το HTML αλλά διαφέρει στη χρήση ετικετών για τον ορισμό αντικειμένων.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


Το έγγραφο Plain Text (TXT) αντιπροσωπεύει ένα κειμενικό έγγραφο που περιέχει απλό κείμενο με τη μορφή γραμμών.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Το Markdown είναι μια ελαφριά γλώσσα σήμανσης για τη δημιουργία μορφοποιημένου κειμένου χρησιμοποιώντας έναν επεξεργαστή απλού κειμένου.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


Το JSON (JavaScript Object Notation) είναι ένα ανοιχτό πρότυπο μορφής αρχείου για την ανταλλαγή δεδομένων που χρησιμοποιεί κείμενο αναγνώσιμο από άνθρωπο για την αποθήκευση και μετάδοση των δεδομένων.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


Η ενσωμάτωση MIME συγκεντρωτικών εγγράφων HTML είναι μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που χρησιμοποιείται για τη συνένωση, σε ένα ενιαίο αρχείο υπολογιστή, του κώδικα HTML και των συνοδευτικών πόρων του.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Το Microsoft Compiled HTML Help είναι μια ιδιόκτητη δυαδική μορφή online βοήθειας της Microsoft, που αποτελείται από μια συλλογή σελίδων HTML, ένα ευρετήριο και άλλα εργαλεία πλοήγησης.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


Λαμβάνει μια συλλογή με δυνατότητα επανάληψης όλων των [TextualFormats](../../com.groupdocs.editor.formats/textualformats).
Τιμή: Μια IEnumerable{TextualFormats} που περιέχει όλες τις παρουσίες των [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Ανακτά μια παρουσία του καθορισμένου τύπου [TextualFormats](../../com.groupdocs.editor.formats/textualformats) που έχει την καθορισμένη επέκταση αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | επέκταση | java.lang.String | Η επέκταση αρχείου της μορφής εγγράφου. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | επέκταση | java.lang.String | Η επέκταση αρχείου για μετατροπή. Εάν η επέκταση περιέχει πολλαπλές τελείες, χρησιμοποιείται το τμήμα μετά την τελευταία τελεία. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

