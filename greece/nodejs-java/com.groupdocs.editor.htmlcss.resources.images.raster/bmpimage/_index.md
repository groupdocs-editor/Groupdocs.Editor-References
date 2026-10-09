---
title: "BmpImage"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει μία εικόνα σε μορφή BMP BitMap Picture με τα μεταδεδομένα της και πρόσθετες μεθόδους"
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

Αντιπροσωπεύει μία εικόνα σε μορφή BMP (BitMap Picture) με τα μεταδεδομένα της και
πρόσθετες μεθόδους

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | Δημιουργεί νέο αντικείμενο BmpImage από το περιεχόμενο, που αναπαρίσταται ως base64-encoded |
συμβολοσειρά, και με το καθορισμένο όνομα
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέο αντικείμενο BmpImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte, |
και με καθορισμένο όνομα
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει εάν η καθορισμένη ροή είναι έγκυρη εικόνα BMP |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη εικόνα BMP |
|
|  | [getType()](#getType--) | Επιστρέφει ImageType.Bmp |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


Δημιουργεί νέο αντικείμενο BmpImage από το περιεχόμενο, που αναπαρίσταται ως base64-encoded
συμβολοσειρά, και με το καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας BMP. Δεν μπορεί να είναι null, κενό ή κενά διαστήματα. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη σε base64. Δεν μπορεί να είναι null, κενό ή κενά διαστήματα. Εάν δεν είναι περιεχόμενο BMP, θα εξαχθεί εξαίρεση. |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


Δημιουργεί νέο αντικείμενο BmpImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte,
και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας BMP. Δεν μπορεί να είναι null, κενό ή κενά διαστήματα. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. Εάν αυτό το αντικείμενο αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει εάν η καθορισμένη ροή είναι έγκυρη εικόνα BMP


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, που προφανώς περιέχει μια εικόνα BMP |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει έγκυρη εικόνα BMP, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη εικόνα BMP


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της προφανώς BMP εικόνας με μορφή συμβολοσειράς κωδικοποιημένης σε base64 |
|

**Returns:**
boolean - True εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα BMP, false διαφορετικά

### getType() {#getType--}
```
public ImageType getType()
```


Επιστρέφει ImageType.Bmp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
