---
title: "TtfFont"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει μία γραμματοσειρά στη μορφή TTF TrueType Font"
type: docs
weight: 15
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

Αντιπροσωπεύει μια γραμματοσειρά σε μορφή TTF (TrueType Font).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | Δημιουργεί νέα κλάση TtfFont από το περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο σε base64 |
συμβολοσειρά, και με το καθορισμένο όνομα
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | Δημιουργεί νέα κλάση TtfFont από το περιεχόμενο, που αναπαρίσταται ως ροή byte, και |
με καθορισμένο όνομα
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Μέγεθος κεφαλίδας TTF (σε bytes), που απαιτείται για την επικύρωσή της |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει εάν η καθορισμένη ροή είναι έγκυρη γραμματοσειρά TTF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη γραμματοσειρά TTF |
|
|  | [getType()](#getType--) | Επιστρέφει FontType.Ttf |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


Δημιουργεί νέα κλάση TtfFont από το περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο σε base64
συμβολοσειρά, και με το καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της γραμματοσειράς TTF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη σε base64. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. Εάν δεν είναι περιεχόμενο TTF, θα προκληθεί εξαίρεση. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


Δημιουργεί νέα κλάση TtfFont από το περιεχόμενο, που αναπαρίσταται ως ροή byte, και
με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της γραμματοσειράς TTF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. Εάν αυτό το αντικείμενο αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Μέγεθος κεφαλίδας TTF (σε bytes), που απαιτείται για την επικύρωσή της


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει εάν η καθορισμένη ροή είναι έγκυρη γραμματοσειρά TTF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, που πιθανώς περιέχει έναν πόρο TTF |
|

**Returns:**
boolean - Αληθές εάν η καθορισμένη ροή περιέχει έγκυρη γραμματοσειρά TTF, ψευδές διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη γραμματοσειρά TTF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της πιθανής γραμματοσειράς TTF με μορφή συμβολοσειράς κωδικοποιημένης σε base64 |
|

**Returns:**
boolean - Αληθές εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη γραμματοσειρά TTF, ψευδές διαφορετικά

### getType() {#getType--}
```
public FontType getType()
```


Επιστρέφει FontType.Ttf


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
