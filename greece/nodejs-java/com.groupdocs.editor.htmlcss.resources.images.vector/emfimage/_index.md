---
title: "EmfImage"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει μία διανυσματική εικόνα σε μορφή Enhanced metafile (EMF) με τα μεταδεδομένα της και πρόσθετες μεθόδους"
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

Αντιπροσωπεύει μία διανυσματική εικόνα σε μορφή Enhanced metafile (EMF) με τα
μεταδεδομένα και πρόσθετες μεθόδους

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | Δημιουργεί νέο αντικείμενο EmfImage από το περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64 |
συμβολοσειρά, και με το καθορισμένο όνομα
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέο αντικείμενο EmfImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte, |
και με καθορισμένο όνομα
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει εάν η καθορισμένη ροή είναι μια έγκυρη εικόνα EMF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι μια έγκυρη εικόνα EMF |
|
|  | [getType()](#getType--) | Επιστρέφει ImageType.Emf |
|
|  | [getByteContent()](#getByteContent--) | Επιστρέφει το περιεχόμενο αυτής της εικόνας EMF ως δυαδική ροή |
|
|  | [getTextContent()](#getTextContent--) | Επιστρέφει το περιεχόμενο αυτής της εικόνας EMF ως απλό κείμενο |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Αποθηκεύει αυτήν την εικόνα EMF στο αρχείο |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Αποθηκεύει αυτήν τη διανυσματική εικόνα EMF σε εικόνα raster PNG |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Αποθηκεύει αυτήν τη διανυσματική εικόνα EMF σε εικόνα vector SVG |
|
|  | [dispose()](#dispose--) | Αποδεσμεύει αυτήν την εικόνα EMF απελευθερώνοντας το περιεχόμενό της και κάνοντας το μεγαλύτερο μέρος της |
μεθόδους και ιδιότητες μη λειτουργικές
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


Δημιουργεί νέο αντικείμενο EmfImage από το περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64
συμβολοσειρά, και με το καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας EMF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη base64. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. Εάν δεν είναι περιεχόμενο EMF, θα ριχτεί εξαίρεση. |
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
|  | name | java.lang.String | Όνομα της εικόνας EMF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. Εάν αυτό το αντικείμενο αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει εάν η καθορισμένη ροή είναι μια έγκυρη εικόνα EMF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Είσοδος ροής byte. Δεν μπορεί να είναι NULL, πρέπει να υποστηρίζει ανάγνωση και αναζήτηση. |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει μια έγκυρη εικόνα EMF, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι μια έγκυρη εικόνα EMF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Συμβολοσειρά εισόδου, όπου το περιεχόμενο της εικόνας EMF αποθηκεύεται σε κωδικοποίηση base64. Δεν μπορεί να είναι NULL ή κενό. |
|

**Returns:**
boolean - True εάν η καθορισμένη συμβολοσειρά περιέχει μια έγκυρη εικόνα EMF, false διαφορετικά

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


Αποθηκεύει αυτήν την εικόνα EMF στο αρχείο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Πλήρης διαδρομή προς το αρχείο, το οποίο θα δημιουργηθεί (αν δεν υπάρχει) ή θα αντικατασταθεί (αν υπάρχει) με το περιεχόμενο αυτής της εικόνας EMF |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Αποθηκεύει αυτήν τη διανυσματική εικόνα EMF σε εικόνα raster PNG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Ροή εξόδου, στην οποία θα γραφτεί το περιεχόμενο της εικόνας PNG. Δεν μπορεί να είναι NULL και πρέπει να είναι εγγράψιμη. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Αποθηκεύει αυτήν τη διανυσματική εικόνα EMF σε εικόνα vector SVG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Ροή εξόδου, στην οποία θα γραφτεί το περιεχόμενο της εικόνας SVG. Δεν μπορεί να είναι NULL και πρέπει να είναι εγγράψιμη. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Αποδεσμεύει αυτήν την εικόνα EMF απελευθερώνοντας το περιεχόμενό της και κάνοντας το μεγαλύτερο μέρος της
μεθόδους και ιδιότητες μη λειτουργικές


