---
title: "IconImage"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά μία εικόνα σε μορφή ICON με τα μεταδεδομένα της και πρόσθετες μεθόδους."
type: docs
weight: 12
url: /el/java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

Αναπαριστά μία εικόνα σε μορφή ICON με τα μεταδεδομένα της και πρόσθετες μεθόδους.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Δημιουργεί νέο αντικείμενο IconImage από περιεχόμενο, που αναπαρίσταται ως |
αλφαριθμητικό κωδικοποιημένο σε base64, και με το καθορισμένο όνομα
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέο αντικείμενο IconImage από περιεχόμενο, που αναπαρίσταται ως ροή byte, |
και με καθορισμένο όνομα
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει αν η καθορισμένη ροή είναι έγκυρη εικόνα ICON |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει αν το καθορισμένο αλφαριθμητικό κωδικοποιημένο σε base64 είναι έγκυρη εικόνα ICON |
|
|  | [getType()](#getType--) | Επιστρέφει ImageType.Icon |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Επιστρέφει τον αριθμό των εικόνων που υπάρχουν σε αυτό το αρχείο ICON |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Δημιουργεί νέο αντικείμενο IconImage από περιεχόμενο, που αναπαρίσταται ως
αλφαριθμητικό κωδικοποιημένο σε base64, και με το καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της εικόνας ICON. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως αλφαριθμητικό κωδικοποιημένο σε base64. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. Εάν δεν είναι περιεχόμενο ICON, θα εξαπολυθεί εξαίρεση. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Δημιουργεί νέο αντικείμενο IconImage από περιεχόμενο, που αναπαρίσταται ως ροή byte,
και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της εικόνας ICON. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμη και αναζητήσιμη. Εάν αυτή η παρουσία αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει αν η καθορισμένη ροή είναι έγκυρη εικόνα ICON


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, που προφανώς περιέχει μια εικόνα ICON |
|

**Returns:**
boolean - True αν η καθορισμένη ροή περιέχει έγκυρη εικόνα ICON, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει αν το καθορισμένο αλφαριθμητικό κωδικοποιημένο σε base64 είναι έγκυρη εικόνα ICON


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της προφανώς εικόνας ICON με τη μορφή αλφαριθμητικού κωδικοποιημένου σε base64 |
|

**Returns:**
boolean - True αν το καθορισμένο αλφαριθμητικό περιέχει έγκυρη εικόνα ICON, false διαφορετικά

### getType() {#getType--}
```
public ImageType getType()
```


Επιστρέφει ImageType.Icon


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


Επιστρέφει τον αριθμό των εικόνων που υπάρχουν σε αυτό το αρχείο ICON


**Returns:**
int
