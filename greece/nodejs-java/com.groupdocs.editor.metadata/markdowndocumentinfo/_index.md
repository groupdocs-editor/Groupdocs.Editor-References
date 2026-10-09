---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει τα μεταδεδομένα ενός εγγράφου Markdown"
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.editor.metadata/markdowndocumentinfo/
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
|  | [getFormat()](#getFormat--) | Επιστρέφει μια μορφή αυτού του εγγράφου Markdown \\u2014 είναι πάντα |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | Επιστρέφει τον αριθμό των σελίδων. |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος σε bytes αυτού του εγγράφου Markdown |
|
|  | [isEncrypted()](#isEncrypted--) | Επειδή τα έγγραφα Markdown δεν μπορούν να κρυπτογραφηθούν με κωδικό πρόσβασης, αυτό |
η ιδιότητα πάντα επιστρέφει 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την άλλη που καθορίζεται |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Επιστρέφει μια μορφή αυτού του εγγράφου Markdown \\u2014 είναι πάντα
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Επιστρέφει τον αριθμό των σελίδων. Τα έγγραφα Markdown συνήθως δεν έχουν σταθερές σελίδες
και έτσι τον αριθμό σελίδων, επομένως αυτός ο αριθμός υπολογίζεται από το τυπικό μέγεθος σελίδας
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


Επειδή τα έγγραφα Markdown δεν μπορούν να κρυπτογραφηθούν με κωδικό πρόσβασης, αυτό
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
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Άλλη παρουσία [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo), η οποία θα πρέπει να ελεγχθεί για ισότητα με αυτήν |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά

