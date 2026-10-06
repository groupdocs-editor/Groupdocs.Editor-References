---
title: "TiffImage"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά μία εικόνα σε μορφή TIFF Tagged Image File Format με τα μεταδεδομένα της και πρόσθετες μεθόδους"
type: docs
weight: 16
url: /el/java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

Αντιπροσωπεύει μία εικόνα σε μορφή TIFF (Tagged Image File Format) με τα
μεταδεδομένα και πρόσθετες μεθόδους


*** ** * ** ***

Δείτε https://en.wikipedia.org/wiki/TIFF για λεπτομέρειες. Σε πολύ σπάνιες περιπτώσεις το TIFF εμφανίζεται μέσα σε έγγραφα WordProcessing.

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | Δημιουργεί νέο αντικείμενο TiffImage από το περιεχόμενο, που αναπαρίσταται ως |
αλφαριθμητικό κωδικοποιημένο σε base64, και με το καθορισμένο όνομα
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέα παρουσία GifImage από περιεχόμενο, που αντιπροσωπεύεται ως ροή byte, |
και με καθορισμένο όνομα
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει αν η καθορισμένη ροή είναι έγκυρη εικόνα TIFF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει αν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη εικόνα TIFF |
|
|  | [getType()](#getType--) | Επιστρέφει ImageType.Tiff |
|
|  | [getFramesCount()](#getFramesCount--) | Επιστρέφει τον αριθμό των πλαισίων (εικόνων) μέσα σε αυτήν την εικόνα TIFF. |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


Δημιουργεί νέο αντικείμενο TiffImage από το περιεχόμενο, που αναπαρίσταται ως
αλφαριθμητικό κωδικοποιημένο σε base64, και με το καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της εικόνας TIFF. Δεν μπορεί να είναι null, κενό ή με κενά. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη σε base64. Δεν μπορεί να είναι null, κενό ή με κενά. Εάν δεν είναι περιεχόμενο TIFF, θα εξαχθεί εξαίρεση. |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
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

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει αν η καθορισμένη ροή είναι έγκυρη εικόνα TIFF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, που υποτίθεται ότι περιέχει μια εικόνα TIFF |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει έγκυρη εικόνα TIFF, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει αν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη εικόνα TIFF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της υποτιθέμενης εικόνας TIFF με μορφή συμβολοσειράς κωδικοποιημένης σε base64 |
|

**Returns:**
boolean - True εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα TIFF, false διαφορετικά

### getType() {#getType--}
```
public ImageType getType()
```


Επιστρέφει ImageType.Tiff


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


Επιστρέφει τον αριθμό των πλαισίων (εικόνων) μέσα σε αυτήν την εικόνα TIFF. Δεν μπορεί να είναι
μικρότερο από 1.


**Returns:**
int -
