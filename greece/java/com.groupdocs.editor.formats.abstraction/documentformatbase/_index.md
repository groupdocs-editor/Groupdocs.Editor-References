---
title: "DocumentFormatBase"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει τη βασική κλάση για μορφές εγγράφων που παρέχει κοινή λειτουργικότητα για τις παρουσίες μορφής."
type: docs
weight: 10
url: /el/java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Αντιπροσωπεύει τη βασική κλάση για μορφότυπους εγγράφων, παρέχοντας κοινή λειτουργικότητα για τις περιπτώσεις μορφής.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMime()](#getMime--) | Αποκτά τον τύπο MIME της μορφής εγγράφου. |
|
|  | [getExtension()](#getExtension--) | Αποκτά την επέκταση αρχείου της μορφής εγγράφου. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Αποκτά την οικογένεια μορφής στην οποία ανήκει η μορφή εγγράφου. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Ανακτά μια παρουσία του καθορισμένου τύπου |
T
που έχει τον καθορισμένο τύπο MIME.
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο αντικείμενο του [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat). |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο αντικείμενο του [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase). |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Μετατρέπει ένα αντικείμενο του [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) σε συμβολοσειρά έμμεσα. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


Αποκτά τον τύπο MIME της μορφής εγγράφου.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Αποκτά την επέκταση αρχείου της μορφής εγγράφου.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Αποκτά την οικογένεια μορφής στην οποία ανήκει η μορφή εγγράφου.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Ανακτά μια παρουσία του καθορισμένου τύπου
T
που έχει τον καθορισμένο τύπο MIME.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | Ο τύπος MIME της μορφής εγγράφου. |


T
: Ο τύπος της μορφής εγγράφου.
|

**Returns:**
T - Ένα αντικείμενο του καθορισμένου τύπου T με τον καθορισμένο τύπο MIME.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο.


**Returns:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο, ο οποίος συνδυάζει τους κωδικούς κατακερματισμού του βασικού αντικειμένου, του τύπου MIME, της επέκτασης αρχείου και της οικογένειας μορφής.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο αντικείμενο του [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | Το αντικείμενο του [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) για σύγκριση με το τρέχον αντικείμενο. |
|

**Returns:**
boolean -  true  εάν το καθορισμένο [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) είναι ίσο με το τρέχον αντικείμενο· διαφορετικά,  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο αντικείμενο του [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Το αντικείμενο του [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) για σύγκριση με το τρέχον αντικείμενο. |
|

**Returns:**
boolean -  true  εάν το καθορισμένο [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) είναι ίσο με το τρέχον αντικείμενο· διαφορετικά,  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


Μετατρέπει ένα αντικείμενο του [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) σε συμβολοσειρά έμμεσα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | Το αντικείμενο του [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) για μετατροπή. |
|

**Returns:**
java.lang.String - Η επέκταση αρχείου του αντικειμένου του [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase).

