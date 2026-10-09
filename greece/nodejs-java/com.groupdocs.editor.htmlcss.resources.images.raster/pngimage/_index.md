---
title: "PngImage"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει μία εικόνα σε μορφή PNG Portable Network Graphics με τα μεταδεδομένα της και πρόσθετες μεθόδους"
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

Αντιπροσωπεύει μία εικόνα σε μορφή PNG (Portable Network Graphics) με τα
μεταδεδομένα και πρόσθετες μεθόδους

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | Δημιουργεί νέο αντικείμενο PngImage από το περιεχόμενο, που αντιπροσωπεύεται ως base64-encoded |
συμβολοσειρά, και με το καθορισμένο όνομα
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέο αντικείμενο PngImage από το περιεχόμενο, που αντιπροσωπεύεται ως byte stream, |
και με καθορισμένο όνομα
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει αν η καθορισμένη ροή είναι έγκυρη εικόνα PNG |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει αν η καθορισμένη συμβολοσειρά base64-encoded είναι έγκυρη εικόνα PNG |
|
|  | [getType()](#getType--) | Επιστρέφει ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


Δημιουργεί νέο αντικείμενο PngImage από το περιεχόμενο, που αντιπροσωπεύεται ως base64-encoded
συμβολοσειρά, και με το καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας PNG. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά base64-encoded. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. Εάν δεν είναι περιεχόμενο PNG, θα ριχθεί εξαίρεση. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


Δημιουργεί νέο αντικείμενο PngImage από το περιεχόμενο, που αντιπροσωπεύεται ως byte stream,
και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας PNG. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. Εάν αυτό το αντικείμενο αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει αν η καθορισμένη ροή είναι έγκυρη εικόνα PNG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, που προφανώς περιέχει μια εικόνα PNG |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει έγκυρη εικόνα PNG, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει αν η καθορισμένη συμβολοσειρά base64-encoded είναι έγκυρη εικόνα PNG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της προφανώς εικόνας PNG με μορφή συμβολοσειράς κωδικοποιημένης base64 |
|

**Returns:**
boolean - True εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα PNG, false διαφορετικά

### getType() {#getType--}
```
public ImageType getType()
```


Επιστρέφει ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
