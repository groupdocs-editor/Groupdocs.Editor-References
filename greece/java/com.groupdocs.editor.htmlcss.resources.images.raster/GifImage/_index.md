---
title: "GifImage"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά μία εικόνα σε μορφή GIF Graphics Interchange Format με τα μεταδεδομένα της και πρόσθετες μεθόδους."
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

Αναπαριστά μία εικόνα σε μορφή GIF (Graphics Interchange Format) με τα
μεταδεδομένα και πρόσθετες μεθόδους

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | Δημιουργεί νέα παρουσία GifImage από περιεχόμενο, που αντιπροσωπεύεται ως κωδικοποιημένο base64 |
συμβολοσειρά, και με καθορισμένο όνομα
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέα παρουσία GifImage από περιεχόμενο, που αντιπροσωπεύεται ως ροή byte, |
και με καθορισμένο όνομα
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει εάν η καθορισμένη ροή είναι έγκυρη εικόνα GIF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι έγκυρη εικόνα GIF |
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


Δημιουργεί νέα παρουσία GifImage από περιεχόμενο, που αντιπροσωπεύεται ως κωδικοποιημένο base64
συμβολοσειρά, και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της εικόνας GIF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη σε base64. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. Εάν δεν είναι περιεχόμενο GIF, θα εξαχθεί εξαίρεση. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
```


Δημιουργεί νέα παρουσία GifImage από περιεχόμενο, που αντιπροσωπεύεται ως ροή byte,
και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της εικόνας GIF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμη και αναζητήσιμη. Εάν αυτή η παρουσία αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει εάν η καθορισμένη ροή είναι έγκυρη εικόνα GIF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, που προφανώς περιέχει μια εικόνα GIF |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει έγκυρη εικόνα GIF, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι έγκυρη εικόνα GIF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της προφανώς εικόνας GIF σε μορφή συμβολοσειράς κωδικοποιημένης σε base64 |
|

**Returns:**
boolean - True εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα GIF, false διαφορετικά

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
