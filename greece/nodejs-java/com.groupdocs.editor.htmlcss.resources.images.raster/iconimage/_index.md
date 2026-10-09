---
title: "IconImage"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αναπαριστά μία εικόνα σε μορφή ICON με τα μεταδεδομένα της και πρόσθετες μεθόδους"
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

Αναπαριστά μία εικόνα σε μορφή ICON με τα μεταδεδομένα της και πρόσθετες μεθόδους

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Δημιουργεί νέα παρουσία IconImage από περιεχόμενο, που αναπαρίσταται ως |
συμβολοσειρά κωδικοποιημένη σε base64, και με καθορισμένο όνομα
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέα παρουσία IconImage από περιεχόμενο, που αναπαρίσταται ως ροή byte, |
και με καθορισμένο όνομα
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει εάν η καθορισμένη ροή είναι μια έγκυρη εικόνα ICON |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι μια έγκυρη εικόνα ICON |
|
|  | [getType()](#getType--) | Επιστρέφει ImageType.Icon |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Επιστρέφει τον αριθμό των εικόνων που υπάρχουν σε αυτό το αρχείο ICON |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Δημιουργεί νέα παρουσία IconImage από περιεχόμενο, που αναπαρίσταται ως
συμβολοσειρά κωδικοποιημένη σε base64, και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας ICON. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη σε base64. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. Εάν δεν είναι περιεχόμενο ICON, θα ριχθεί εξαίρεση. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Δημιουργεί νέα παρουσία IconImage από περιεχόμενο, που αναπαρίσταται ως ροή byte,
και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας ICON. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. Εάν αυτό το αντικείμενο αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει εάν η καθορισμένη ροή είναι μια έγκυρη εικόνα ICON


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


Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι μια έγκυρη εικόνα ICON


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της προφανώς εικόνας ICON με μορφή συμβολοσειράς κωδικοποιημένης base64 |
|

**Returns:**
boolean - True αν η καθορισμένη συμβολοσειρά περιέχει έγκυρη εικόνα ICON, false διαφορετικά

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
