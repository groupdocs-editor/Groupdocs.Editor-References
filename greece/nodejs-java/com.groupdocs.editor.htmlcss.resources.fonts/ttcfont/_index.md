---
title: "TtcFont"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αναπαριστά μία γραμματοσειρά στη μορφή TTC TrueType Collection"
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
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
συμβολοσειρά, και με το καθορισμένο όνομα
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | Δημιουργεί νέα κλάση TtcFont από περιεχόμενο, που αναπαρίσταται ως ροή byte, και |
με καθορισμένο όνομα
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Μέγεθος κεφαλίδας TTC (σε bytes), που απαιτείται για την επικύρωσή του |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει αν η καθορισμένη ροή είναι έγκυρη γραμματοσειρά TTC |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει αν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη γραμματοσειρά TTC |
|
|  | [getType()](#getType--) | Επιστρέφει FontType.Ttc |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | Έκδοση κεφαλίδας TTC, μπορεί να είναι "1" ή "2" |
|
|  | [getFontsNumber()](#getFontsNumber--) | Αριθμός γραμματοσειρών σε αυτό το TTC |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | Δείχνει αν αυτό το TTC έχει πίνακα DSIG. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


Δημιουργεί νέα κλάση TtcFont από περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64
συμβολοσειρά, και με το καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της γραμματοσειράς TTC. Δεν μπορεί να είναι null, κενό ή κενά διαστήματα. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη σε base64. Δεν μπορεί να είναι null, κενό ή κενά διαστήματα. Εάν δεν είναι περιεχόμενο TTC, θα προκληθεί εξαίρεση. |
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
|  | name | java.lang.String | Όνομα της γραμματοσειράς TTC. Δεν μπορεί να είναι null, κενό ή κενά διαστήματα. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. Εάν αυτό το αντικείμενο αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Μέγεθος κεφαλίδας TTC (σε bytes), που απαιτείται για την επικύρωσή του


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει αν η καθορισμένη ροή είναι έγκυρη γραμματοσειρά TTC


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, η οποία πιθανώς περιέχει έναν πόρο TTC |
|

**Returns:**
boolean - Αληθές εάν η καθορισμένη ροή περιέχει έγκυρη γραμματοσειρά TTC, ψευδές διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει αν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη γραμματοσειρά TTC


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της πιθανής γραμματοσειράς TTC με μορφή συμβολοσειράς κωδικοποιημένης σε base64 |
|

**Returns:**
boolean - Αληθές εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη γραμματοσειρά TTC, ψευδές διαφορετικά

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


Δείχνει εάν αυτή η TTC έχει πίνακα DSIG. Ο πίνακας DSIG μπορεί να είναι παρών
μόνο εάν η TTC έχει κεφαλίδα έκδοσης 2.0.


**Returns:**
boolean
