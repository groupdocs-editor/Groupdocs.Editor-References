---
title: "EmfImage"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά μία διανυσματική εικόνα σε μορφή Enhanced Metafile (EMF) με τα μεταδεδομένα της και πρόσθετες μεθόδους"
type: docs
weight: 10
url: /el/java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

Αναπαριστά μία διανυσματική εικόνα σε μορφή Enhanced Metafile (EMF) με το
μεταδεδομένα και πρόσθετες μεθόδους

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | Δημιουργεί νέο αντικείμενο EmfImage από το περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο σε base64 |
συμβολοσειρά, και με καθορισμένο όνομα
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέο αντικείμενο EmfImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte, |
και με καθορισμένο όνομα
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει αν η καθορισμένη ροή είναι έγκυρη εικόνα EMF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει αν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη εικόνα EMF |
|
|  | [getType()](#getType--) | Επιστρέφει ImageType.Emf |
|
|  | [getByteContent()](#getByteContent--) | Επιστρέφει το περιεχόμενο αυτής της εικόνας EMF ως δυαδική ροή |
|
|  | [getTextContent()](#getTextContent--) | Επιστρέφει το περιεχόμενο αυτής της εικόνας EMF ως απλό κείμενο |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Αποθηκεύει αυτή την εικόνα EMF στο αρχείο |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Αποθηκεύει αυτή τη διανυσματική εικόνα EMF σε raster εικόνα PNG |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Αποθηκεύει αυτή τη διανυσματική εικόνα EMF σε διανυσματική εικόνα SVG |
|
|  | [dispose()](#dispose--) | Καταστρέφει αυτή την εικόνα EMF απελευθερώνοντας το περιεχόμενό της και καθιστώντας το μεγαλύτερο μέρος της |
μεθόδους και ιδιότητες μη λειτουργικές
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


Δημιουργεί νέο αντικείμενο EmfImage από το περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο σε base64
συμβολοσειρά, και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της εικόνας EMF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη σε base64. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. Εάν δεν είναι περιεχόμενο EMF, θα ριχθεί εξαίρεση. |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


Δημιουργεί νέο αντικείμενο EmfImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte,
και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της εικόνας EMF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμη και αναζητήσιμη. Εάν αυτή η παρουσία αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει αν η καθορισμένη ροή είναι έγκυρη εικόνα EMF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Είσοδος ροής byte. Δεν μπορεί να είναι NULL, πρέπει να υποστηρίζει ανάγνωση και αναζήτηση. |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει έγκυρη εικόνα EMF, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει αν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη εικόνα EMF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Συμβολοσειρά εισόδου, όπου το περιεχόμενο της εικόνας EMF αποθηκεύεται σε κωδικοποίηση base64. Δεν μπορεί να είναι NULL ή κενό. |
|

**Returns:**
boolean - Αληθές εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα EMF, ψευδές διαφορετικά

### getType() {#getType--}
```
public ImageType getType()
```


Επιστρέφει ImageType.Emf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Επιστρέφει το περιεχόμενο αυτής της εικόνας EMF ως δυαδική ροή


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Επιστρέφει το περιεχόμενο αυτής της εικόνας EMF ως απλό κείμενο


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Αποθηκεύει αυτή την εικόνα EMF στο αρχείο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Πλήρης διαδρομή προς το αρχείο, το οποίο θα δημιουργηθεί (αν δεν υπάρχει) ή θα αντικατασταθεί (αν υπάρχει) με το περιεχόμενο αυτής της εικόνας EMF |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Αποθηκεύει αυτή τη διανυσματική εικόνα EMF σε raster εικόνα PNG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Ροή εξόδου, στην οποία θα γραφτεί το περιεχόμενο της εικόνας PNG. Δεν μπορεί να είναι NULL και πρέπει να είναι εγγράψιμη. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Αποθηκεύει αυτή τη διανυσματική εικόνα EMF σε διανυσματική εικόνα SVG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Ροή εξόδου, στην οποία θα γραφτεί το περιεχόμενο της εικόνας SVG. Δεν μπορεί να είναι NULL και πρέπει να είναι εγγράψιμη. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Καταστρέφει αυτή την εικόνα EMF απελευθερώνοντας το περιεχόμενό της και καθιστώντας το μεγαλύτερο μέρος της
μεθόδους και ιδιότητες μη λειτουργικές


