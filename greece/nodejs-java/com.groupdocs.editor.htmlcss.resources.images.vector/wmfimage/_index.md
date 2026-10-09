---
title: "WmfImage"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει μια διανυσματική εικόνα σε μορφή WMF Windows MetaFile με τα μεταδεδομένα της και πρόσθετες μεθόδους"
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

Αντιπροσωπεύει μια διανυσματική εικόνα σε μορφή WMF (Windows MetaFile) με τα
μεταδεδομένα και πρόσθετες μεθόδους

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | Δημιουργεί νέο αντικείμενο WmfImage από το περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64 |
συμβολοσειρά, και με το καθορισμένο όνομα
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέο αντικείμενο WmfImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte, |
και με καθορισμένο όνομα
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει εάν η καθορισμένη ροή είναι μια έγκυρη εικόνα WMF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι μια έγκυρη εικόνα WMF |
|
|  | [getType()](#getType--) | Επιστρέφει ImageType.Wmf |
|
|  | [getByteContent()](#getByteContent--) | Επιστρέφει το περιεχόμενο αυτής της εικόνας WMF ως δυαδική ροή |
|
|  | [getTextContent()](#getTextContent--) | Επιστρέφει το περιεχόμενο αυτής της εικόνας WMF ως απλό κείμενο |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Αποθηκεύει αυτήν την εικόνα WMF στο αρχείο |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Αποθηκεύει αυτήν τη διανυσματική εικόνα WMF σε εικόνα raster PNG |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Αποθηκεύει αυτήν τη διανυσματική εικόνα WMF σε διανυσματική εικόνα SVG |
|
|  | [dispose()](#dispose--) | Καταστρέφει αυτήν την εικόνα WMF απελευθερώνοντας το περιεχόμενό της και κάνοντας το μεγαλύτερο μέρος της |
μεθόδους και ιδιότητες μη λειτουργικές
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


Δημιουργεί νέο αντικείμενο WmfImage από το περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64
συμβολοσειρά, και με το καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας WMF. Δεν μπορεί να είναι null, κενό ή με κενά διαστήματα. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη σε base64. Δεν μπορεί να είναι null, κενό ή με κενά διαστήματα. Εάν δεν είναι περιεχόμενο WMF, θα προκληθεί εξαίρεση. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


Δημιουργεί νέο αντικείμενο WmfImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte,
και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας WMF. Δεν μπορεί να είναι null, κενό ή με κενά διαστήματα. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. Εάν αυτό το αντικείμενο αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει εάν η καθορισμένη ροή είναι μια έγκυρη εικόνα WMF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Είσοδος ροής byte. Δεν μπορεί να είναι NULL, πρέπει να υποστηρίζει ανάγνωση και αναζήτηση. |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει μια έγκυρη εικόνα WMF, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι μια έγκυρη εικόνα WMF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Συμβολοσειρά εισόδου, όπου το περιεχόμενο της εικόνας WMF αποθηκεύεται σε κωδικοποίηση base64. Δεν μπορεί να είναι NULL ή κενό. |
|

**Returns:**
boolean - True εάν η καθορισμένη συμβολοσειρά περιέχει μια έγκυρη εικόνα WMF, false διαφορετικά

### getType() {#getType--}
```
public ImageType getType()
```


Επιστρέφει ImageType.Wmf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Επιστρέφει το περιεχόμενο αυτής της εικόνας WMF ως δυαδική ροή


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Επιστρέφει το περιεχόμενο αυτής της εικόνας WMF ως απλό κείμενο


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Αποθηκεύει αυτήν την εικόνα WMF στο αρχείο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Πλήρης διαδρομή προς το αρχείο, το οποίο θα δημιουργηθεί (αν δεν υπάρχει) ή θα αντικατασταθεί (αν υπάρχει) με το περιεχόμενο αυτής της εικόνας WMF |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Αποθηκεύει αυτήν τη διανυσματική εικόνα WMF σε εικόνα raster PNG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Ροή εξόδου, στην οποία θα γραφτεί το περιεχόμενο της εικόνας PNG. Δεν μπορεί να είναι NULL και πρέπει να είναι εγγράψιμη. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Αποθηκεύει αυτήν τη διανυσματική εικόνα WMF σε διανυσματική εικόνα SVG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Ροή εξόδου, στην οποία θα γραφτεί το περιεχόμενο της εικόνας SVG. Δεν μπορεί να είναι NULL και πρέπει να είναι εγγράψιμη. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Καταστρέφει αυτήν την εικόνα WMF απελευθερώνοντας το περιεχόμενό της και κάνοντας το μεγαλύτερο μέρος της
μεθόδους και ιδιότητες μη λειτουργικές


