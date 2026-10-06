---
title: "MarkdownDocumentInfo"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Markdown"
type: docs
weight: 13
url: /el/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Markdown

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Επιστρέφει μορφή αυτού του εγγράφου Markdown \\u2014 πάντα είναι |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | Επιστρέφει αριθμό σελίδων. |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου Markdown |
|
|  | [isEncrypted()](#isEncrypted--) | Επειδή τα έγγραφα Markdown δεν μπορούν να κρυπτογραφηθούν με κωδικό, αυτό |
η ιδιότητα πάντα επιστρέφει 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη που καθορίζεται |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Επιστρέφει μορφή αυτού του εγγράφου Markdown \\u2014 πάντα είναι
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Επιστρέφει αριθμό σελίδων. Τα έγγραφα Markdown συνήθως δεν έχουν σταθερές σελίδες
και έτσι ο αριθμός σελίδων, έτσι ο αριθμός αυτός υπολογίζεται από το τυπικό μέγεθος σελίδας
ορίζεται σε A4 σε κατακόρυφη προσανατολισμό.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου Markdown


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Επειδή τα έγγραφα Markdown δεν μπορούν να κρυπτογραφηθούν με κωδικό, αυτό
η ιδιότητα πάντα επιστρέφει 'false'


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη που καθορίζεται
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Άλλη παρουσία [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) που πρέπει να ελεγχθεί για ισότητα με αυτήν |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

