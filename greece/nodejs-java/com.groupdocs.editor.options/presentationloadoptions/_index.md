---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη φόρτωση εγγράφων όλων των υποστηριζόμενων μορφών Παρουσίασης, όπως PPTX, PPTM, PPSX κ.ά."
type: docs
weight: 33
url: /el/nodejs-java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για τη φόρτωση εγγράφων όλων των υποστηριζόμενων
Μορφές Παρουσίασης όπως PPT(X), PPTM, PPS(X) κ.ά.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPassword()](#getPassword--) | Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για |
άνοιγμα του εγγράφου Presentation, εάν είναι κωδικοποιημένο.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για |
άνοιγμα του εγγράφου Presentation, εάν είναι κωδικοποιημένο.
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
άνοιγμα του εγγράφου Presentation, εάν είναι κωδικοποιημένο. Ορίστε σε NULL ή κενό
συμβολοσειρά για την αφαίρεση του κωδικού πρόσβασης.


*** ** * ** ***

Από προεπιλογή, αυτή η ιδιότητα έχει τιμή NULL \\u2014 ο κωδικός πρόσβασης δεν έχει οριστεί. Εάν το εισαγόμενο έγγραφο Presentation είναι προστατευμένο με κωδικό πρόσβασης, ο κωδικός είναι υποχρεωτικός και θα εξαχθεί εξαίρεση εάν ο κωδικός δεν καθοριστεί ή είναι άκυρος. Εάν το εισαγόμενο έγγραφο Presentation ΔΕΝ είναι προστατευμένο με κωδικό πρόσβασης, αλλά ο κωδικός έχει οριστεί, θα αγνοηθεί.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Επιτρέπει τον καθορισμό, την τροποποίηση και την απόκτηση του κωδικού πρόσβασης, ο οποίος θα χρησιμοποιηθεί για
άνοιγμα του εγγράφου Presentation, εάν είναι κωδικοποιημένο. Ορίστε σε NULL ή κενό
συμβολοσειρά για την αφαίρεση του κωδικού πρόσβασης.


*** ** * ** ***

Από προεπιλογή, αυτή η ιδιότητα έχει τιμή NULL \\u2014 ο κωδικός πρόσβασης δεν έχει οριστεί. Εάν το εισαγόμενο έγγραφο Presentation είναι προστατευμένο με κωδικό πρόσβασης, ο κωδικός είναι υποχρεωτικός και θα εξαχθεί εξαίρεση εάν ο κωδικός δεν καθοριστεί ή είναι άκυρος. Εάν το εισαγόμενο έγγραφο Presentation ΔΕΝ είναι προστατευμένο με κωδικό πρόσβασης, αλλά ο κωδικός έχει οριστεί, θα αγνοηθεί.

<br />



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

