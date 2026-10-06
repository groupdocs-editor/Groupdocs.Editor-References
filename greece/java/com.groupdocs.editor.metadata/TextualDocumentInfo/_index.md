---
title: "TextualDocumentInfo"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά μεταδεδομένα ενός κειμενικού εγγράφου όπως XML HTML ή απλό κείμενο TXT"
type: docs
weight: 16
url: /el/java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

Αναπαριστά μεταδεδομένα ενός κειμενικού εγγράφου όπως XML, HTML ή απλό κείμενο
(TXT)

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Επιστρέφει μια μορφή αυτού του κειμενικού εγγράφου. |
|
|  | [getPageCount()](#getPageCount--) | Πάντα επιστρέφει 1 |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε bytes (όχι τον αριθμό των χαρακτήρων) αυτού του κειμενικού |
έγγραφο
|
|  | [isEncrypted()](#isEncrypted--) | Πάντα επιστρέφει 'false', καθώς τα κειμενικά έγγραφα δεν μπορούν να κρυπτογραφηθούν. |
|
|  | [getEncoding()](#getEncoding--) | Επιστρέφει την ανιχνευμένη πιθανή κωδικοποίηση του κειμενικού εγγράφου |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Επιστρέφει μια μορφή αυτού του κειμενικού εγγράφου. Μπορεί να μην είναι 100% σωστή σε
μερικές περιπτώσεις.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Πάντα επιστρέφει 1


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Επιστρέφει το μέγεθος σε bytes (όχι τον αριθμό των χαρακτήρων) αυτού του κειμενικού
έγγραφο


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Πάντα επιστρέφει 'false', καθώς τα κειμενικά έγγραφα δεν μπορούν να κρυπτογραφηθούν.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Επιστρέφει την ανιχνευμένη πιθανή κωδικοποίηση του κειμενικού εγγράφου


**Returns:**
java.nio.charset.Charset
