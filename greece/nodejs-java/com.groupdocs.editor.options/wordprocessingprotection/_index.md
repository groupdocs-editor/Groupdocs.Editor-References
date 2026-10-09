---
title: "WordProcessingProtection"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Περιλαμβάνει επιλογές προστασίας εγγράφου για το έγγραφο WordProcessing που δημιουργείται από HTML"
type: docs
weight: 46
url: /el/nodejs-java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

Περιλαμβάνει επιλογές προστασίας εγγράφου για το έγγραφο WordProcessing,
που δημιουργείται από HTML

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | Κατασκευαστής χωρίς παραμέτρους - όλες οι παράμετροι έχουν προεπιλεγμένες τιμές |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | Επιτρέπει τον ορισμό όλων των παραμέτρων κατά τη δημιουργία της κλάσης |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Επιτρέπει τον ορισμό ενός τύπου προστασίας του εγγράφου. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Επιτρέπει τον ορισμό ενός τύπου προστασίας του εγγράφου. |
|
|  | [getPassword()](#getPassword--) | Ο κωδικός πρόσβασης για την προστασία του εγγράφου. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ο κωδικός πρόσβασης για την προστασία του εγγράφου. |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


Κατασκευαστής χωρίς παραμέτρους - όλες οι παράμετροι έχουν προεπιλεγμένες τιμές


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


Επιτρέπει τον ορισμό όλων των παραμέτρων κατά τη δημιουργία της κλάσης


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | protectionType | int | Ορίστε τον τύπο προστασίας του εγγράφου |
|
|  | κωδικός πρόσβασης | java.lang.String | Ορίστε τον κωδικό προστασίας |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Επιτρέπει τον ορισμό τύπου προστασίας του εγγράφου. Από προεπιλογή είναι ορισμένο σε μη
προστατεύει το έγγραφο καθόλου.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Επιτρέπει τον ορισμό τύπου προστασίας του εγγράφου. Από προεπιλογή είναι ορισμένο σε μη
προστατεύει το έγγραφο καθόλου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ο κωδικός για την προστασία του εγγράφου. Εάν είναι null ή κενή συμβολοσειρά - ο
η προστασία δεν θα εφαρμοστεί στο έγγραφο.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ο κωδικός για την προστασία του εγγράφου. Εάν είναι null ή κενή συμβολοσειρά - ο
η προστασία δεν θα εφαρμοστεί στο έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
