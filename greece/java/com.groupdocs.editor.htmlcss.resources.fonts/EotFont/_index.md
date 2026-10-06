---
title: "EotFont"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει μία γραμματοσειρά στη μορφή EOT Embedded OpenType"
type: docs
weight: 10
url: /el/java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

Αντιπροσωπεύει μια γραμματοσειρά σε μορφή EOT (Embedded OpenType).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | Δημιουργεί νέα κλάση EotFont από περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64 |
συμβολοσειρά, και με καθορισμένο όνομα
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | Δημιουργεί νέα κλάση EotFont από περιεχόμενο, που αναπαρίσταται ως ροή byte, και |
με καθορισμένο όνομα
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Μέγεθος κεφαλίδας EOT (σε bytes), που απαιτείται για την επικύρωσή της |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει εάν η καθορισμένη ροή είναι έγκυρη γραμματοσειρά EOT |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι έγκυρη γραμματοσειρά EOT |
|
|  | [getType()](#getType--) | Επιστρέφει FontType.Eot |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


Δημιουργεί νέα κλάση EotFont από περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64
συμβολοσειρά, και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της γραμματοσειράς EOT. Δεν μπορεί να είναι null, κενό ή λευκά διαστήματα. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη σε base64. Δεν μπορεί να είναι null, κενό ή λευκά διαστήματα. Εάν δεν είναι περιεχόμενο EOT, θα ριχθεί εξαίρεση. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


Δημιουργεί νέα κλάση EotFont από περιεχόμενο, που αναπαρίσταται ως ροή byte, και
με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της γραμματοσειράς EOT. Δεν μπορεί να είναι null, κενό ή λευκά διαστήματα. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμη και αναζητήσιμη. Εάν αυτή η παρουσία αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Μέγεθος κεφαλίδας EOT (σε bytes), που απαιτείται για την επικύρωσή της


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει εάν η καθορισμένη ροή είναι έγκυρη γραμματοσειρά EOT


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, που προφανώς περιέχει έναν πόρο EOT |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει έγκυρη γραμματοσειρά EOT, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι έγκυρη γραμματοσειρά EOT


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της προφανώς γραμματοσειράς EOT με μορφή συμβολοσειράς κωδικοποιημένης σε base64 |
|

**Returns:**
boolean - True εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη γραμματοσειρά EOT, false διαφορετικά

### getType() {#getType--}
```
public FontType getType()
```


Επιστρέφει FontType.Eot


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
