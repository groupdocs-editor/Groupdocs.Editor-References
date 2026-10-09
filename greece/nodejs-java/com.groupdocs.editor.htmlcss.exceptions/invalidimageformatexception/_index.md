---
title: "InvalidImageFormatException"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Η εξαίρεση που εκτοξεύεται όταν προσπαθείτε να ανοίξετε, φορτώσετε, αποθηκεύσετε ή επεξεργαστείτε με κάποιον τρόπο κάποιο περιεχόμενο που προφανώς είναι μια εικόνα raster ή vector, αλλά στην πραγματικότητα είναι μια εικόνα απροσδόκητου τύπου ή καθόλου εικόνα."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

Η εξαίρεση που εκτοξεύεται όταν προσπαθείτε να ανοίξετε, φορτώσετε, αποθηκεύσετε ή επεξεργαστείτε
με κάποιον άλλο τρόπο κάποιο περιεχόμενο, που προφανώς είναι μια εικόνα (raster ή vector),
αλλά στην πραγματικότητα είναι μια εικόνα απροσδόκητου τύπου ή καθόλου εικόνα.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Δημιουργεί νέο στιγμιότυπο του InvalidImageFormatException με το καθορισμένο μήνυμα σφάλματος |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Δημιουργεί νέο στιγμιότυπο του InvalidImageFormatException με το καθορισμένο μήνυμα σφάλματος και μια αναφορά στην εσωτερική εξαίρεση που είναι η αιτία αυτής της εξαίρεσης |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Δημιουργεί νέο στιγμιότυπο του InvalidImageFormatException με το καθορισμένο μήνυμα σφάλματος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Κειμενικό μήνυμα, που περιγράφει το σφάλμα, μπορεί να είναι null ή κενό |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Δημιουργεί νέο στιγμιότυπο του InvalidImageFormatException με το καθορισμένο μήνυμα σφάλματος και μια αναφορά στην εσωτερική εξαίρεση που είναι η αιτία αυτής της εξαίρεσης


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Κειμενικό μήνυμα, που περιγράφει το σφάλμα, μπορεί να είναι null ή κενό |
|
|  | innerException | java.lang.RuntimeException | Η εξαίρεση που είναι η αιτία της τρέχουσας εξαίρεσης, ή μια αναφορά null εάν δεν έχει καθοριστεί εσωτερική εξαίρεση. |
|

