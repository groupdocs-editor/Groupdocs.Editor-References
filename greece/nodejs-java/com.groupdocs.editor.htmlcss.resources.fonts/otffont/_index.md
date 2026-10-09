---
title: "OtfFont"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει μία γραμματοσειρά στη μορφή OTF Open Type Format"
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
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
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | Δημιουργεί νέα κλάση OtfFont από περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο σε base64 |
συμβολοσειρά, και με το καθορισμένο όνομα
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | Δημιουργεί νέα κλάση OtfFont από περιεχόμενο, που αναπαρίσταται ως ροή byte, και |
με καθορισμένο όνομα
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | Μέγεθος κεφαλίδας OTF (σε bytes), που απαιτείται για την επικύρωσή της |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Ελέγχει εάν η καθορισμένη ροή είναι έγκυρη γραμματοσειρά OTF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη γραμματοσειρά OTF |
|
|  | [getType()](#getType--) | Επιστρέφει |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


Δημιουργεί νέα κλάση OtfFont από περιεχόμενο, που αναπαρίσταται ως κωδικοποιημένο σε base64
συμβολοσειρά, και με το καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της γραμματοσειράς OTF. Δεν μπορεί να είναι null, κενό ή κενά. |
|
|  | contentInBase64 | java.lang.String | Περιεχόμενο ως συμβολοσειρά κωδικοποιημένη σε base64. Δεν μπορεί να είναι null, κενό ή κενά. Εάν δεν είναι περιεχόμενο OTF, θα προκληθεί εξαίρεση. |
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
|  | name | java.lang.String | Όνομα της γραμματοσειράς OTF. Δεν μπορεί να είναι null, κενό ή κενά. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. Εάν αυτό το αντικείμενο αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


Μέγεθος κεφαλίδας OTF (σε bytes), που απαιτείται για την επικύρωσή της


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Ελέγχει εάν η καθορισμένη ροή είναι έγκυρη γραμματοσειρά OTF


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


Ελέγχει εάν η καθορισμένη συμβολοσειρά κωδικοποιημένη σε base64 είναι έγκυρη γραμματοσειρά OTF


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Περιεχόμενο της προφανώς γραμματοσειράς OTF με μορφή συμβολοσειράς κωδικοποιημένης σε base64 |
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
