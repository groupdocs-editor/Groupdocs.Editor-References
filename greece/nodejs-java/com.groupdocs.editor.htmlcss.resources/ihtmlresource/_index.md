---
title: "IHtmlResource"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει ένα αντικείμενο του άγνωστου πόρου HTML raster ή vector εικόνας, stylesheet, γραμματοσειράς, κειμένου, πόρου CSS, XML κ.λπ."
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

Αντιπροσωπεύει ένα αντικείμενο του άγνωστου πόρου HTML (raster ή vector εικόνα,
stylesheet, γραμματοσειρά, κειμενικό πόρο (CSS, XML) κ.)

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getName()](#getName--) | Όνομα του πόρου HTML |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Σωστό όνομα αρχείου του καθορισμένου πόρου με το κατάλληλο αρχείο |
επέκταση
|
|  | [getType()](#getType--) | Τύπος του πόρου HTML |
|
|  | [getByteContent()](#getByteContent--) | Περιεχόμενο του πόρου HTML με τη μορφή ροής byte |
|
|  | [getTextContent()](#getTextContent--) | Περιεχόμενο του πόρου HTML με τη μορφή κειμενικής συμβολοσειράς κωδικοποιημένης σε base64 |
για δυαδικούς πόρους ή απλό κείμενο για κειμενικούς πόρους
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Αποθηκεύει τον τρέχοντα πόρο στο καθορισμένο αρχείο |
|
### getName() {#getName--}
```
public abstract String getName()
```


Όνομα του πόρου HTML


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


Σωστό όνομα αρχείου του καθορισμένου πόρου με το κατάλληλο αρχείο
επέκταση


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


Τύπος του πόρου HTML


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


Περιεχόμενο του πόρου HTML με τη μορφή ροής byte


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Περιεχόμενο του πόρου HTML με τη μορφή κειμενικής συμβολοσειράς κωδικοποιημένης σε base64
για δυαδικούς πόρους ή απλό κείμενο για κειμενικούς πόρους


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Αποθηκεύει τον τρέχοντα πόρο στο καθορισμένο αρχείο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Πλήρης διαδρομή προς το αρχείο, το οποίο θα δημιουργηθεί ή θα ξαναγραφεί με το περιεχόμενο του τρέχοντος πόρου |
|

