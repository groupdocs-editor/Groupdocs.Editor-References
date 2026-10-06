---
title: "MarkdownImageLoadArgs"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Παρέχει δεδομένα για το συμβάν MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs."
type: docs
weight: 22
url: /el/java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Παρέχει δεδομένα για το

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

συμβάν.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Λαμβάνει ή ορίζει το όνομα αρχείου (όπως εμφανίζεται στο έγγραφο Markdown) που θα είναι |
επεξεργασία.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα αρχείου (όπως εμφανίζεται στο έγγραφο Markdown) που θα είναι |
επεξεργασία.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Λάβετε μια τιμή που υποδεικνύει εάν αυτή η εικόνα έχει απόλυτο σύνδεσμο URI. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Λάβετε μια τιμή που υποδεικνύει εάν αυτή η εικόνα έχει απόλυτο σύνδεσμο URI. |
|
|  | [setData(byte[] data)](#setData-byte---) | Ορίζει τα δεδομένα που παρέχονται από τον χρήστη για τον πόρο που χρησιμοποιείται εάν |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


Λαμβάνει ή ορίζει το όνομα αρχείου (όπως εμφανίζεται στο έγγραφο Markdown) που θα είναι
επεξεργασία.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Λαμβάνει ή ορίζει το όνομα αρχείου (όπως εμφανίζεται στο έγγραφο Markdown) που θα είναι
επεξεργασία.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Λάβετε μια τιμή που υποδεικνύει εάν αυτή η εικόνα έχει απόλυτο σύνδεσμο URI.
Τιμή:  true  εάν αυτή η εικόνα έχει απόλυτο σύνδεσμο URI· διαφορετικά,  false .


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Λάβετε μια τιμή που υποδεικνύει εάν αυτή η εικόνα έχει απόλυτο σύνδεσμο URI.
Τιμή:  true  εάν αυτή η εικόνα έχει απόλυτο σύνδεσμο URI· διαφορετικά,  false .


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Ορίζει τα δεδομένα που παρέχονται από τον χρήστη για τον πόρο που χρησιμοποιείται εάν

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | byte[] |  |

