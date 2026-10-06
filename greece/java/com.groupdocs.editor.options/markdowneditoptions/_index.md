---
title: "MarkdownEditOptions"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων σε μορφή Markdown."
type: docs
weight: 21
url: /el/java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Επιτρέπει τον καθορισμό προσαρμοσμένων επιλογών για την επεξεργασία εγγράφων σε μορφή Markdown.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | Δημιουργεί και επιστρέφει μια νέα παρουσία της κλάσης MarkdownEditOptions, |
όπου όλες οι επιλογές ορίζονται στις προεπιλεγμένες τιμές
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Επιτρέπει τον έλεγχο του τρόπου αποθήκευσης των εικόνων κατά τη μετατροπή του εγγράφου Markdown |
σε Html.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Επιτρέπει τον έλεγχο του τρόπου αποθήκευσης των εικόνων κατά τη μετατροπή του εγγράφου Markdown |
σε Html.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


Δημιουργεί και επιστρέφει μια νέα παρουσία της κλάσης MarkdownEditOptions,
όπου όλες οι επιλογές ορίζονται στις προεπιλεγμένες τιμές


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Επιτρέπει τον έλεγχο του τρόπου αποθήκευσης των εικόνων κατά τη μετατροπή του εγγράφου Markdown
σε Html.
Τιμή: Η κλήση επιστροφής αποθήκευσης εικόνας.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Επιτρέπει τον έλεγχο του τρόπου αποθήκευσης των εικόνων κατά τη μετατροπή του εγγράφου Markdown
σε Html.
Τιμή: Η κλήση επιστροφής αποθήκευσης εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

