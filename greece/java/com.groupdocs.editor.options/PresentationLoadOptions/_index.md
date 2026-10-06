---
title: "PresentationLoadOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη φόρτωση εγγράφων όλων των υποστηριζόμενων μορφών Presentation, όπως PPTX, PPTM, PPSX κ.λπ."
type: docs
weight: 33
url: /el/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη φόρτωση εγγράφων όλων των υποστηριζόμενων
Μορφές Presentation όπως PPT(X), PPTM, PPS(X) κ.λπ.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPassword()](#getPassword--) | Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για |
το άνοιγμα του εγγράφου Presentation, εάν είναι κωδικοποιημένο.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για |
το άνοιγμα του εγγράφου Presentation, εάν είναι κωδικοποιημένο.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για
το άνοιγμα του εγγράφου Presentation, εάν είναι κωδικοποιημένο. Ορίστε σε NULL ή κενό
συμβολοσειρά για την αφαίρεση του κωδικού πρόσβασης.


*** ** * ** ***

Από προεπιλογή αυτή η ιδιότητα έχει τιμή NULL — ο κωδικός πρόσβασης δεν έχει οριστεί. Εάν το εισερχόμενο έγγραφο Presentation είναι προστατευμένο με κωδικό, ο κωδικός είναι υποχρεωτικός και θα εξαπολυθεί εξαίρεση εάν ο κωδικός δεν καθοριστεί ή είναι άκυρος. Εάν το εισερχόμενο έγγραφο Presentation ΔΕΝ είναι προστατευμένο με κωδικό, αλλά έχει οριστεί κωδικός, θα αγνοηθεί.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για
το άνοιγμα του εγγράφου Presentation, εάν είναι κωδικοποιημένο. Ορίστε σε NULL ή κενό
συμβολοσειρά για την αφαίρεση του κωδικού πρόσβασης.


*** ** * ** ***

Από προεπιλογή αυτή η ιδιότητα έχει τιμή NULL — ο κωδικός πρόσβασης δεν έχει οριστεί. Εάν το εισερχόμενο έγγραφο Presentation είναι προστατευμένο με κωδικό, ο κωδικός είναι υποχρεωτικός και θα εξαπολυθεί εξαίρεση εάν ο κωδικός δεν καθοριστεί ή είναι άκυρος. Εάν το εισερχόμενο έγγραφο Presentation ΔΕΝ είναι προστατευμένο με κωδικό, αλλά έχει οριστεί κωδικός, θα αγνοηθεί.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

