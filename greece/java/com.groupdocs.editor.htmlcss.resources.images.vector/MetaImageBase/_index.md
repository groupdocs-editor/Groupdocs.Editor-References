---
title: "MetaImageBase"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Βασική αφηρημένη κλάση για τις μορφές εικόνας WMF και EMF."
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

Βασική αφηρημένη κλάση για τις μορφές εικόνας WMF και EMF.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Κοινός κατασκευαστής, που προετοιμάζει τη δημιουργία μιας WMF ή EMF instance από |
κωδικοποιημένη σε base64 συμβολοσειρά
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Κοινός κατασκευαστής, που προετοιμάζει τη δημιουργία μιας WMF ή EMF instance από |
ροή byte
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Καθορίζει εάν η καθορισμένη ροή byte περιέχει έγκυρη εικόνα WMF |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Καθορίζει εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα WMF, η οποία είναι |
κωδικοποιημένη με base64
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Καθορίζει εάν η καθορισμένη ροή byte περιέχει έγκυρη εικόνα EMF |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Καθορίζει εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα EMF, η οποία είναι |
κωδικοποιημένη με base64
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Στην υλοποίηση, ο τύπος πρέπει να αποθηκεύσει την τρέχουσα διανυσματική meta-image στο |
διανυσματική μορφή SVG σε καθορισμένη ροή byte
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Κοινός κατασκευαστής, που προετοιμάζει τη δημιουργία μιας WMF ή EMF instance από
κωδικοποιημένη σε base64 συμβολοσειρά


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Υποχρεωτικό όνομα |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά base64. Δεν πρέπει να είναι NULL ή κενό. |
|
|  | isWmf | boolean | true για WMF, false για EMF |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Κοινός κατασκευαστής, που προετοιμάζει τη δημιουργία μιας WMF ή EMF instance από
ροή byte


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Υποχρεωτικό όνομα |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Πρέπει να είναι έγκυρο. |
|
|  | isWmf | boolean | true για WMF, false για EMF |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


Καθορίζει εάν η καθορισμένη ροή byte περιέχει έγκυρη εικόνα WMF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Είσοδος ροής byte. Πρέπει να είναι έγκυρο. |
|

**Returns:**
boolean - Επιστρέφει 'true' εάν είναι έγκυρο και 'false' εάν είναι μη έγκυρο

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


Καθορίζει εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα WMF, η οποία είναι
κωδικοποιημένη με base64


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Συμβολοσειρά, η οποία θεωρείται ότι περιέχει κωδικοποιημένη σε base64 εικόνα WMF |
|

**Returns:**
boolean - Επιστρέφει 'true' εάν είναι έγκυρο και 'false' εάν είναι μη έγκυρο

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


Καθορίζει εάν η καθορισμένη ροή byte περιέχει έγκυρη εικόνα EMF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Είσοδος ροής byte. Πρέπει να είναι έγκυρο. |
|

**Returns:**
boolean - Επιστρέφει 'true' εάν είναι έγκυρο και 'false' εάν είναι μη έγκυρο

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


Καθορίζει εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα EMF, η οποία είναι
κωδικοποιημένη με base64


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Συμβολοσειρά, η οποία θεωρείται ότι περιέχει μια εικόνα EMF κωδικοποιημένη σε base64 |
|

**Returns:**
boolean - Επιστρέφει 'true' εάν είναι έγκυρο και 'false' εάν είναι μη έγκυρο

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


Στην υλοποίηση, ο τύπος πρέπει να αποθηκεύσει την τρέχουσα διανυσματική meta-image στο
διανυσματική μορφή SVG σε καθορισμένη ροή byte


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Ροή byte, στην οποία θα αποθηκευτεί η έκδοση SVG αυτής της διανυσματικής μετα-εικόνας. Δεν πρέπει να είναι NULL και πρέπει να υποστηρίζει εγγραφή. |
|

