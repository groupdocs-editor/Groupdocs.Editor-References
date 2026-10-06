---
title: "InvalidFormatException"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Η εξαίρεση που ρίχνεται όταν ο χρήστης προσπαθεί να ανοίξει κάποιο έγγραφο με επιλογές ειδικές για μορφή που είναι ασύμβατες με την αρχική μορφή του εγγράφου."
type: docs
weight: 15
url: /el/java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

Η εξαίρεση που ρίχνεται όταν ο χρήστης προσπαθεί να ανοίξει κάποιο έγγραφο με
επιλογές ειδικές για μορφή που είναι ασύμβατες με την αρχική μορφή του εγγράφου.


*** ** * ** ***

Για παράδειγμα, αυτή η εξαίρεση θα ριχτεί, εάν προσπαθήσετε να ανοίξετε έγγραφο Spreadsheet με επιλογές εγγράφου WordProcessing.

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [InvalidFormatException()](#InvalidFormatException--) |  |
| [InvalidFormatException(String message)](#InvalidFormatException-java.lang.String-) |  |
| [InvalidFormatException(String message, RuntimeException inner)](#InvalidFormatException-java.lang.String-java.lang.RuntimeException-) |  |
### InvalidFormatException() {#InvalidFormatException--}
```
public InvalidFormatException()
```


### InvalidFormatException(String message) {#InvalidFormatException-java.lang.String-}
```
public InvalidFormatException(String message)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String |  |
| εσωτερικό | java.lang.RuntimeException |  |

