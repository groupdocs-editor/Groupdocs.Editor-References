---
title: "GifImage"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει μία εικόνα σε μορφή GIF Graphics Interchange Format με τα μεταδεδομένα της και πρόσθετες μεθόδους"
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

Αντιπροσωπεύει μία εικόνα σε μορφή GIF (Graphics Interchange Format) με τα
μεταδεδομένα και πρόσθετες μεθόδους

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | Δημιουργεί νέο αντικείμενο GifImage από το περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64 |
συμβολοσειρά, και με το καθορισμένο όνομα
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέο αντικείμενο GifImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte, |
και με καθορισμένο όνομα
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει αν η καθορισμένη ροή είναι μια έγκυρη εικόνα GIF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει αν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι μια έγκυρη εικόνα GIF |
|
|  | [getType()](#getType--) | Επιστρέφει ImageType.Gif |
|
|  | [getVersion()](#getVersion--) | Επιστρέφει την εσωτερική έκδοση αυτής της εικόνας GIF (η έκδοση εξάγεται από |
την κεφαλίδα)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


Δημιουργεί νέο αντικείμενο GifImage από το περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64
συμβολοσειρά, και με το καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας GIF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη base64. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. Εάν δεν είναι περιεχόμενο GIF, θα ριχθεί εξαίρεση. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
```


Δημιουργεί νέο αντικείμενο GifImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte,
και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας GIF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. Εάν αυτό το αντικείμενο αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει αν η καθορισμένη ροή είναι μια έγκυρη εικόνα GIF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, που προφανώς περιέχει μια εικόνα GIF |
|

**Returns:**
boolean - True αν η καθορισμένη ροή περιέχει έγκυρη εικόνα GIF, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει αν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι μια έγκυρη εικόνα GIF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της προφανώς εικόνας GIF με μορφή συμβολοσειράς κωδικοποιημένης base64 |
|

**Returns:**
boolean - True αν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα GIF, false διαφορετικά

### getType() {#getType--}
```
public ImageType getType()
```


Επιστρέφει ImageType.Gif


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Επιστρέφει την εσωτερική έκδοση αυτής της εικόνας GIF (η έκδοση εξάγεται από
την κεφαλίδα)


**Returns:**
java.lang.String
