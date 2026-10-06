---
title: "PdfLoadOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Περιέχει επιλογές για τη φόρτωση εγγράφων PDF στην κλάση Editor"
type: docs
weight: 30
url: /el/java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

Περιέχει επιλογές για τη φόρτωση εγγράφων PDF στην κλάση Editor

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPassword()](#getPassword--) | Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για το άνοιγμα ενός PDF εγγράφου, εάν είναι κωδικοποιημένο. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για το άνοιγμα ενός PDF εγγράφου, εάν είναι κωδικοποιημένο. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για το άνοιγμα ενός PDF εγγράφου, εάν είναι κωδικοποιημένο.
Ορίστε σε NULL ή κενή συμβολοσειρά για να μην χρησιμοποιηθεί ο κωδικός πρόσβασης (προεπιλεγμένη τιμή).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για το άνοιγμα ενός PDF εγγράφου, εάν είναι κωδικοποιημένο.
Ορίστε σε NULL ή κενή συμβολοσειρά για να μην χρησιμοποιηθεί ο κωδικός πρόσβασης (προεπιλεγμένη τιμή).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

