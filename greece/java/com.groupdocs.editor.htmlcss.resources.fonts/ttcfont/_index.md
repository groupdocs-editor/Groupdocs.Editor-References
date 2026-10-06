---
title: "TtcFont"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά μία γραμματοσειρά στη μορφή TTC TrueType Collection"
type: docs
weight: 14
url: /el/java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

Αντιπροσωπεύει μια γραμματοσειρά σε μορφή TTC (TrueType Collection).


Δείτε περισσότερα: https://docs.fileformat.com/font/ttc/

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | Δημιουργεί νέα κλάση TtcFont από περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64 |
συμβολοσειρά, και με καθορισμένο όνομα
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | Δημιουργεί νέα κλάση TtcFont από περιεχόμενο, που αναπαρίσταται ως ροή byte, και |
με καθορισμένο όνομα
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Μέγεθος κεφαλίδας TTC (σε bytes), το οποίο απαιτείται για την επικύρωσή του |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει εάν η καθορισμένη ροή είναι μια έγκυρη γραμματοσειρά TTC |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι μια έγκυρη γραμματοσειρά TTC |
|
|  | [getType()](#getType--) | Επιστρέφει FontType.Ttc |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | Έκδοση κεφαλίδας TTC, μπορεί να είναι "1" ή "2" |
|
|  | [getFontsNumber()](#getFontsNumber--) | Αριθμός γραμματοσειρών σε αυτό το TTC |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | Δείχνει εάν αυτό το TTC έχει πίνακα DSIG. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


Δημιουργεί νέα κλάση TtcFont από περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64
συμβολοσειρά, και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της γραμματοσειράς TTC. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη σε base64. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. Εάν δεν είναι περιεχόμενο TTC, θα προκληθεί εξαίρεση. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


Δημιουργεί νέα κλάση TtcFont από περιεχόμενο, που αναπαρίσταται ως ροή byte, και
με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της γραμματοσειράς TTC. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμη και αναζητήσιμη. Εάν αυτή η παρουσία αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Μέγεθος κεφαλίδας TTC (σε bytes), το οποίο απαιτείται για την επικύρωσή του


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει εάν η καθορισμένη ροή είναι μια έγκυρη γραμματοσειρά TTC


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, που προφανώς περιέχει έναν πόρο TTC |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει έγκυρη γραμματοσειρά TTC, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι μια έγκυρη γραμματοσειρά TTC


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της προφανώς γραμματοσειράς TTC σε μορφή συμβολοσειράς κωδικοποιημένης σε base64 |
|

**Returns:**
boolean - True εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη γραμματοσειρά TTC, false διαφορετικά

### getType() {#getType--}
```
public FontType getType()
```


Επιστρέφει FontType.Ttc


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


Έκδοση κεφαλίδας TTC, μπορεί να είναι "1" ή "2"


**Returns:**
byte
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


Αριθμός γραμματοσειρών σε αυτό το TTC


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


Δείχνει εάν αυτό το TTC έχει πίνακα DSIG. Ο πίνακας DSIG μπορεί να υπάρχει
μόνο εάν το TTC έχει έκδοση κεφαλίδας 2.0.


**Returns:**
boolean
