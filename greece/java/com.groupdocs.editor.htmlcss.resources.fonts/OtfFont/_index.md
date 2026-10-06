---
title: "OtfFont"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά μία γραμματοσειρά στο φορμά OTF Open Type Format"
type: docs
weight: 13
url: /el/java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

Αντιπροσωπεύει μια γραμματοσειρά σε μορφή OTF (Open Type Format).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | Δημιουργεί νέα κλάση OtfFont από περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64 |
συμβολοσειρά, και με καθορισμένο όνομα
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | Δημιουργεί νέα κλάση OtfFont από περιεχόμενο, που αναπαρίσταται ως ροή byte, και |
με καθορισμένο όνομα
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Μέγεθος κεφαλίδας OTF (σε bytes), που απαιτείται για την επικύρωσή του |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει αν η καθορισμένη ροή είναι έγκυρη γραμματοσειρά OTF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει αν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι έγκυρη γραμματοσειρά OTF |
|
|  | [getType()](#getType--) | Επιστρέφει |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


Δημιουργεί νέα κλάση OtfFont από περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο base64
συμβολοσειρά, και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της γραμματοσειράς OTF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη base64. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. Εάν δεν είναι περιεχόμενο OTF, θα προκληθεί εξαίρεση. |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


Δημιουργεί νέα κλάση OtfFont από περιεχόμενο, που αναπαρίσταται ως ροή byte, και
με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Όνομα της γραμματοσειράς OTF. Δεν μπορεί να είναι null, κενό ή λευκοί χαρακτήρες. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμη και αναζητήσιμη. Εάν αυτή η παρουσία αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Μέγεθος κεφαλίδας OTF (σε bytes), που απαιτείται για την επικύρωσή του


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει αν η καθορισμένη ροή είναι έγκυρη γραμματοσειρά OTF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Ροή byte, που προφανώς περιέχει έναν πόρο OTF |
|

**Returns:**
boolean - True εάν η καθορισμένη ροή περιέχει έγκυρη γραμματοσειρά OTF, false διαφορετικά

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Ελέγχει αν η καθορισμένη συμβολοσειρά κωδικοποιημένη base64 είναι έγκυρη γραμματοσειρά OTF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της προφανώς γραμματοσειράς OTF σε μορφή συμβολοσειράς κωδικοποιημένης base64 |
|

**Returns:**
boolean - True εάν η καθορισμένη συμβολοσειρά περιέχει έγκυρη γραμματοσειρά OTF, false διαφορετικά

### getType() {#getType--}
```
public FontType getType()
```


Επιστρέφει
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
