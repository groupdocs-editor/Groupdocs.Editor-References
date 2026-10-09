---
title: "MetaImageBase"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Βασική αφηρημένη κλάση για μορφές εικόνας WMF και EMF"
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

Βασική αφηρημένη κλάση για μορφές εικόνας WMF και EMF

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Κοινός κατασκευαστής, ο οποίος προετοιμάζει τη δημιουργία ενός στιγμιότυπου WMF ή EMF από |
αλφαριθμητικό κωδικοποιημένο σε base64
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Κοινός κατασκευαστής, ο οποίος προετοιμάζει τη δημιουργία ενός στιγμιότυπου WMF ή EMF από |
ροή byte
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Καθορίζει εάν η καθορισμένη ροή byte περιέχει έγκυρη εικόνα WMF |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Καθορίζει εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα WMF, η οποία είναι |
κωδικοποιημένο με base64
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Καθορίζει εάν η καθορισμένη ροή byte περιέχει έγκυρη εικόνα EMF |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Καθορίζει εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα EMF, η οποία είναι |
κωδικοποιημένο με base64
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Στην υλοποίηση, ο τύπος πρέπει να αποθηκεύσει την τρέχουσα διανυσματική meta-εικόνα στο |
μορφή vector SVG σε καθορισμένη ροή byte
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Κοινός κατασκευαστής, ο οποίος προετοιμάζει τη δημιουργία ενός στιγμιότυπου WMF ή EMF από
αλφαριθμητικό κωδικοποιημένο σε base64


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Υποχρεωτικό όνομα |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως αλφαριθμητικό base64. Δεν πρέπει να είναι NULL ή κενό. |
|
|  | isWmf | boolean | αληθές για WMF, ψευδές για EMF |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Κοινός κατασκευαστής, ο οποίος προετοιμάζει τη δημιουργία ενός στιγμιότυπου WMF ή EMF από
ροή byte


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Υποχρεωτικό όνομα |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Πρέπει να είναι έγκυρο. |
|
|  | isWmf | boolean | αληθές για WMF, ψευδές για EMF |
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
κωδικοποιημένο με base64


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Συμβολοσειρά, η οποία θεωρείται ότι περιέχει μια εικόνα WMF κωδικοποιημένη σε base64 |
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
κωδικοποιημένο με base64


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


Στην υλοποίηση, ο τύπος πρέπει να αποθηκεύσει την τρέχουσα διανυσματική meta-εικόνα στο
μορφή vector SVG σε καθορισμένη ροή byte


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Ροή byte, στην οποία θα αποθηκευτεί η έκδοση SVG αυτής της διανυσματικής meta-εικόνας. Δεν πρέπει να είναι NULL και πρέπει να υποστηρίζει εγγραφή. |
|

