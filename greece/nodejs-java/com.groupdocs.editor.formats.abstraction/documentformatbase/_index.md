---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει την βασική κλάση για μορφές εγγράφων που παρέχει κοινή λειτουργικότητα για τις παρουσίες μορφής."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Αντιπροσωπεύει τη βασική κλάση για μορφότυπα εγγράφων, παρέχοντας κοινή λειτουργικότητα για τις περιπτώσεις μορφής.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getMime()](#getMime--) | Λαμβάνει τον τύπο MIME της μορφής εγγράφου. |
|
|  | [getExtension()](#getExtension--) | Λαμβάνει την επέκταση αρχείου της μορφής εγγράφου. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Λαμβάνει την οικογένεια μορφής στην οποία ανήκει ο μορφότυπος του εγγράφου. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου |
T
που έχει τον καθορισμένο τύπο MIME.
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το καθορισμένο [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) στιγμιότυπο. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το καθορισμένο [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) στιγμιότυπο. |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Μετατρέπει ένα [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) στιγμιότυπο σε συμβολοσειρά έμμεσα. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


Λαμβάνει τον τύπο MIME της μορφής εγγράφου.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Λαμβάνει την επέκταση αρχείου της μορφής εγγράφου.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Λαμβάνει την οικογένεια μορφής στην οποία ανήκει ο μορφότυπος του εγγράφου.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου
T
που έχει τον καθορισμένο τύπο MIME.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | Ο τύπος MIME του μορφότυπου εγγράφου. |


T
: Ο τύπος του μορφότυπου εγγράφου.
|

**Returns:**
T - Ένα στιγμιότυπο του καθορισμένου τύπου  T  με τον καθορισμένο τύπο MIME.

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


Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το καθορισμένο [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) στιγμιότυπο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | Το [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) στιγμιότυπο για σύγκριση με το τρέχον στιγμιότυπο. |
|

**Returns:**
boolean -  true  εάν το καθορισμένο [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) είναι ίσο με το τρέχον στιγμιότυπο· διαφορετικά,  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτό το στιγμιότυπο είναι ίσο με το καθορισμένο [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) στιγμιότυπο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Το [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) στιγμιότυπο για σύγκριση με το τρέχον στιγμιότυπο. |
|

**Returns:**
boolean -  true  εάν το καθορισμένο [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) είναι ίσο με το τρέχον στιγμιότυπο· διαφορετικά,  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


Μετατρέπει ένα [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) στιγμιότυπο σε συμβολοσειρά έμμεσα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | Το [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) στιγμιότυπο για μετατροπή. |
|

**Returns:**
java.lang.String - Η επέκταση αρχείου του [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) στιγμιότυπου.

