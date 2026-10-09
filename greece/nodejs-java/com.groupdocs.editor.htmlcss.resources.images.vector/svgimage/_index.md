---
title: "SvgImage"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει μία διανυσματική εικόνα σε μορφή SVG (Scalable Vector Graphics) με τα μεταδεδομένα της και πρόσθετες μεθόδους"
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

Αντιπροσωπεύει μία διανυσματική εικόνα σε μορφή SVG (Scalable Vector Graphics) με τα
μεταδεδομένα και πρόσθετες μεθόδους

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | Δημιουργεί νέο αντικείμενο SvgImage από το περιεχόμενο, που αναπαρίσταται ως συνηθισμένη συμβολοσειρά, |
και με καθορισμένο όνομα
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | Δημιουργεί νέο αντικείμενο SvgImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte, |
και με καθορισμένο όνομα
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | Πραγματοποιεί έλεγχο επιφάνειας εάν το καθορισμένο κειμενικό περιεχόμενο συμβατό με XML |
αντιπροσωπεύει μια εικόνα SVG
|
|  | [getType()](#getType--) | Επιστρέφει ImageType.Svg |
|
|  | [getByteContent()](#getByteContent--) | Επιστρέφει το περιεχόμενο αυτής της εικόνας SVG ως δυαδική ροή |
|
|  | [getTextContent()](#getTextContent--) | Επιστρέφει το περιεχόμενο αυτής της εικόνας SVG ως απλό κείμενο (σε μορφή XML) |
|
|  | [getXmlContent()](#getXmlContent--) | Επιστρέφει το περιεχόμενο αυτής της εικόνας SVG στην αρχική της μορφή συμβατή με XML |
κείμενη μορφή
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Αποθηκεύει αυτήν την εικόνα SVG στο αρχείο |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Αποθηκεύει αυτήν την διανυσματική εικόνα SVG σε ραστερ εικόνα PNG |
|
|  | [dispose()](#dispose--) | Αποδεσμεύει αυτή τη raster εικόνα, απελευθερώνοντας το περιεχόμενό της και καθιστώντας τις περισσότερες μεθόδους |
και τις ιδιότητες μη λειτουργικές
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


Δημιουργεί νέο αντικείμενο SvgImage από το περιεχόμενο, που αναπαρίσταται ως συνηθισμένη συμβολοσειρά,
και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας SVG. Δεν μπορεί να είναι null, κενό ή να περιέχει μόνο κενά. |
|
|  | περιεχόμενο | java.lang.String | Περιεχόμενο ως συνηθισμένη συμβολοσειρά, η οποία περιέχει έγκυρο περιεχόμενο συμβατό με XML για εικόνα SVG. Δεν μπορεί να είναι null, κενό ή να περιέχει μόνο κενά. Εάν δεν είναι περιεχόμενο SVG, θα προκληθεί εξαίρεση. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


Δημιουργεί νέο αντικείμενο SvgImage από το περιεχόμενο, που αναπαρίσταται ως ροή byte,
και με καθορισμένο όνομα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα της εικόνας SVG. Δεν μπορεί να είναι null, κενό ή να περιέχει μόνο κενά. |
|
|  | binaryContent | java.io.InputStream | Περιεχόμενο ως ροή byte. Η ανάγνωση ξεκινά από την αρχική θέση. Δεν μπορεί να είναι null. Πρέπει να είναι αναγνώσιμο και δυνατό για αναζήτηση. Εάν αυτό το αντικείμενο αποδεσμευτεί, αυτή η ροή θα αποδεσμευθεί επίσης. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


Πραγματοποιεί έλεγχο επιφάνειας εάν το καθορισμένο κειμενικό περιεχόμενο συμβατό με XML
αντιπροσωπεύει μια εικόνα SVG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | περιεχόμενο | java.lang.String | Περιεχόμενο XML μιας εικόνας SVG ως απλό κείμενο, όχι κωδικοποιημένο σε base64 |
|

**Returns:**
boolean - True εάν η καθορισμένη συμβολοσειρά μπορεί να θεωρηθεί έγκυρη SVG με την πρώτη ματιά, false εάν σίγουρα δεν είναι SVG

### getType() {#getType--}
```
public ImageType getType()
```


Επιστρέφει ImageType.Svg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Επιστρέφει το περιεχόμενο αυτής της εικόνας SVG ως δυαδική ροή


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Επιστρέφει το περιεχόμενο αυτής της εικόνας SVG ως απλό κείμενο (σε μορφή XML)


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


Επιστρέφει το περιεχόμενο αυτής της εικόνας SVG στην αρχική της μορφή συμβατή με XML
κείμενη μορφή


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Αποθηκεύει αυτήν την εικόνα SVG στο αρχείο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Πλήρης διαδρομή προς το αρχείο, το οποίο θα δημιουργηθεί (αν δεν υπάρχει) ή θα αντικατασταθεί (αν υπάρχει) με το περιεχόμενο αυτής της εικόνας SVG |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Αποθηκεύει αυτήν την διανυσματική εικόνα SVG σε ραστερ εικόνα PNG


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Ροή εξόδου, στην οποία θα γραφτεί το περιεχόμενο της εικόνας PNG. Δεν μπορεί να είναι NULL και πρέπει να είναι εγγράψιμη. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Αποδεσμεύει αυτή τη raster εικόνα, απελευθερώνοντας το περιεχόμενό της και καθιστώντας τις περισσότερες μεθόδους
και τις ιδιότητες μη λειτουργικές


