---
title: "EmailFormats"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Περιλαμβάνει όλες τις μορφές email."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.editor.formats/emailformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EmailFormats extends DocumentFormatBase
```

Περιλαμβάνει όλες τις μορφές email. Συμπεριλαμβάνει τους ακόλουθους τύπους αρχείων:
[Tnef](../../com.groupdocs.editor.formats/emailformats#Tnef),
[Eml](../../com.groupdocs.editor.formats/emailformats#Eml),
[Emlx](../../com.groupdocs.editor.formats/emailformats#Emlx),
[Msg](../../com.groupdocs.editor.formats/emailformats#Msg),
[Html](../../com.groupdocs.editor.formats/emailformats#Html),
[Mhtml](../../com.groupdocs.editor.formats/emailformats#Mhtml).

<br />

*** ** * ** ***

Μάθετε περισσότερα για τη μορφή email [εδώ](../https://docs.fileformat.com/email/).

<br />


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Tnef](#Tnef) | Το Transport Neutral Encapsulation Format (TNEF) είναι μια ιδιόκτητη μορφή της Microsoft για την ενσωμάτωση συνημμένων email βάσει του Messaging Application Programming Interface (MAPI). |
|
|  | [Eml](#Eml) | Η μορφή αρχείου EML αντιπροσωπεύει μηνύματα email που αποθηκεύονται χρησιμοποιώντας το Outlook και άλλες σχετικές εφαρμογές. |
|
|  | [Emlx](#Emlx) | Η μορφή αρχείου EMLX υλοποιείται και αναπτύσσεται από την Apple. |
|
|  | [Msg](#Msg) | Το MSG είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων email, επαφών, ραντεβού ή άλλων εργασιών. |
|
|  | [Html](#Html) | Emails μορφοποιημένα σε HTML. |
|
|  | [Mhtml](#Mhtml) | MHTML, ένα αρχικό γράμμα του "MIME encapsulation of aggregate HTML documents". |
|
|  | [Ics](#Ics) | Η Προδιαγραφή Πυρήνα Αντικειμένου Ηλεκτρονικού Ημερολογίου και Προγραμματισμού (iCalendar) είναι ένα πρότυπο διαδικτύου (RFC 2445) για την ανταλλαγή και ανάπτυξη γεγονότων ημερολογίου και προγραμματισμού. |
|
|  | [Vcf](#Vcf) | VCF (Virtual Card Format) ή vCard είναι μια ψηφιακή μορφή αρχείου για την αποθήκευση πληροφοριών επαφών. |
|
|  | [Pst](#Pst) | Αρχεία με επέκταση .pst αντιπροσωπεύουν τα Outlook Personal Storage Files (επίσης γνωστά ως Personal Storage Table) που αποθηκεύουν διάφορες πληροφορίες χρήστη. |
|
|  | [Mbox](#Mbox) | Η μορφή αρχείου MBox είναι ένας γενικός όρος που αντιπροσωπεύει ένα δοχείο για τη συλλογή ηλεκτρονικών μηνυμάτων. |
|
|  | [Oft](#Oft) | Αρχεία με επέκταση .oft είναι αρχεία προτύπων που δημιουργούνται με τη χρήση του Microsoft Outlook. |
|
|  | [Ost](#Ost) | Το αρχείο Offline Storage Table (OST) αντιπροσωπεύει τα δεδομένα του γραμματοκιβωτίου του χρήστη\\u2019s σε offline λειτουργία στον τοπικό υπολογιστή μετά την εγγραφή με τον Exchange Server χρησιμοποιώντας το Microsoft Outlook. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAll()](#getAll--) | Λαμβάνει μια επαναληπτική συλλογή όλων των [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ανακτά μια παρουσία του καθορισμένου τύπου [EmailFormats](../../com.groupdocs.editor.formats/emailformats) που έχει την καθορισμένη επέκταση αρχείου. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [EmailFormats](../../com.groupdocs.editor.formats/emailformats). |
|
### Tnef {#Tnef}
```
public static final EmailFormats Tnef
```


Το Transport Neutral Encapsulation Format (TNEF) είναι μια ιδιόκτητη μορφή της Microsoft για την ενσωμάτωση συνημμένων email βάσει του Messaging Application Programming Interface (MAPI).
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/email/tnef/)
.


### Eml {#Eml}
```
public static final EmailFormats Eml
```


Η μορφή αρχείου EML αντιπροσωπεύει μηνύματα email που αποθηκεύονται χρησιμοποιώντας το Outlook και άλλες σχετικές εφαρμογές.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/email/eml/)
.


### Emlx {#Emlx}
```
public static final EmailFormats Emlx
```


Η μορφή αρχείου EMLX υλοποιείται και αναπτύσσεται από την Apple. Η εφαρμογή Apple Mail χρησιμοποιεί τη μορφή αρχείου EMLX για την εξαγωγή των emails.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/email/emlx/)
.


### Msg {#Msg}
```
public static final EmailFormats Msg
```


Το MSG είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων email, επαφών, ραντεβού ή άλλων εργασιών.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/email/msg/)
.


### Html {#Html}
```
public static final EmailFormats Html
```


Emails μορφοποιημένα σε HTML.


### Mhtml {#Mhtml}
```
public static final EmailFormats Mhtml
```


MHTML, ένα αρχικό γράμμα του "MIME encapsulation of aggregate HTML documents".


### Ics {#Ics}
```
public static final EmailFormats Ics
```


Η Προδιαγραφή Πυρήνα Αντικειμένου Ηλεκτρονικού Ημερολογίου και Προγραμματισμού (iCalendar) είναι ένα πρότυπο διαδικτύου (RFC 2445) για την ανταλλαγή και ανάπτυξη γεγονότων ημερολογίου και προγραμματισμού.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/email/ics/)
.


### Vcf {#Vcf}
```
public static final EmailFormats Vcf
```


VCF (Virtual Card Format) ή vCard είναι μια ψηφιακή μορφή αρχείου για την αποθήκευση πληροφοριών επαφών.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/email/vcf/)
.


### Pst {#Pst}
```
public static final EmailFormats Pst
```


Αρχεία με επέκταση .pst αντιπροσωπεύουν τα Outlook Personal Storage Files (επίσης γνωστά ως Personal Storage Table) που αποθηκεύουν διάφορες πληροφορίες χρήστη.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/email/pst/)
.


### Mbox {#Mbox}
```
public static final EmailFormats Mbox
```


Η μορφή αρχείου MBox είναι ένας γενικός όρος που αντιπροσωπεύει ένα δοχείο για τη συλλογή ηλεκτρονικών μηνυμάτων.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/email/mbox/)
.


### Oft {#Oft}
```
public static final EmailFormats Oft
```


Αρχεία με επέκταση .oft είναι αρχεία προτύπων που δημιουργούνται με τη χρήση του Microsoft Outlook.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/email/oft/)
.


### Ost {#Ost}
```
public static final EmailFormats Ost
```


Το αρχείο Offline Storage Table (OST) αντιπροσωπεύει τα δεδομένα του γραμματοκιβωτίου του χρήστη\\u2019s σε offline λειτουργία στον τοπικό υπολογιστή μετά την εγγραφή με τον Exchange Server χρησιμοποιώντας το Microsoft Outlook.
Μάθετε περισσότερα για αυτή τη μορφή αρχείου
[here](../https://docs.fileformat.com/email/ost/)
.


### getAll() {#getAll--}
```
public static List<EmailFormats> getAll()
```


Λαμβάνει μια επαναληπτική συλλογή όλων των [EmailFormats](../../com.groupdocs.editor.formats/emailformats).
Τιμή: Ένα  IEnumerable{EmailFormats}  που περιέχει όλες τις παρουσίες του [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EmailFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EmailFormats fromExtension(String extension)
```


Ανακτά μια παρουσία του καθορισμένου τύπου [EmailFormats](../../com.groupdocs.editor.formats/emailformats) που έχει την καθορισμένη επέκταση αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | επέκταση | java.lang.String | Η επέκταση αρχείου της μορφής εγγράφου. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - An instance of the specified type [EmailFormats](../../com.groupdocs.editor.formats/emailformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EmailFormats fromString(String extension)
```


Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει μια επέκταση αρχείου σε αντικείμενο [EmailFormats](../../com.groupdocs.editor.formats/emailformats).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | επέκταση | java.lang.String | Η επέκταση αρχείου για μετατροπή. Εάν η επέκταση περιέχει πολλαπλές τελείες, χρησιμοποιείται το τμήμα μετά την τελευταία τελεία. |
|

**Returns:**
[EmailFormats](../../com.groupdocs.editor.formats/emailformats) - A [EmailFormats](../../com.groupdocs.editor.formats/emailformats) object corresponding to the specified file extension.

