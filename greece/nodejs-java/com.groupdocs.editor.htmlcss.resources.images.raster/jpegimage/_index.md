---
title: "JpegImage"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει μία εικόνα σε μορφή JPEG Joint Photographic Experts Group με τα μεταδεδομένα της και πρόσθετες μεθόδους"
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

Αντιπροσωπεύει μία εικόνα σε μορφή JPEG (Joint Photographic Experts Group) με
τα μεταδεδομένα της και πρόσθετες μεθόδους

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | Δημιουργεί νέο αντικείμενο JpegImage από το περιεχόμενο, που αναπαρίσταται ως |
συμβολοσειρά κωδικοποιημένη σε base64, και με καθορισμένο όνομα
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέο αντικείμενο JpegImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte, |
και με καθορισμένο όνομα
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει εάν η καθορισμένη ροή είναι μια έγκυρη εικόνα JPEG |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι μια έγκυρη εικόνα JPEG |
|
|  | [getType()](#getType--) | Επιστρέφει ImageType.Jpeg |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


Δημιουργεί νέο αντικείμενο JpegImage από το περιεχόμενο, που αναπαρίσταται ως
συμβολοσειρά κωδικοποιημένη σε base64, και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας JPEG. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη base64. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. Εάν δεν είναι περιεχόμενο JPEG, θα προκληθεί εξαίρεση. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


Δημιουργεί νέο αντικείμενο JpegImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte,
και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας JPEG. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. Εάν αυτό το αντικείμενο αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει εάν η καθορισμένη ροή είναι μια έγκυρη εικόνα JPEG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, που προφανώς περιέχει μια εικόνα JPEG |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει έγκυρη εικόνα JPEG, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι μια έγκυρη εικόνα JPEG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της προφανώς εικόνας JPEG με μορφή συμβολοσειράς κωδικοποιημένης base64 |
|

**Returns:**
boolean - True εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα JPEG, false διαφορετικά

### getType() {#getType--}
```
public ImageType getType()
```


Επιστρέφει ImageType.Jpeg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
