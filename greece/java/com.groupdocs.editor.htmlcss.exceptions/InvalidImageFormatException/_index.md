---
title: "InvalidImageFormatException"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Η εξαίρεση που ρίχνεται όταν προσπαθείτε να ανοίξετε, φορτώσετε, αποθηκεύσετε ή επεξεργαστείτε με κάποιον τρόπο κάποιο περιεχόμενο που υποτίθεται ότι είναι μια εικόνα (raster ή vector), αλλά στην πραγματικότητα είναι μια εικόνα απροσδόκητου τύπου ή καθόλου δεν είναι εικόνα."
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

Η εξαίρεση που ρίχνεται όταν προσπαθείτε να ανοίξετε, φορτώσετε, αποθηκεύσετε ή επεξεργαστείτε
κάποιο άλλο περιεχόμενο, που υποτίθεται ότι είναι μια εικόνα (raster ή vector),
αλλά στην πραγματικότητα είναι μια εικόνα απροσδόκητου τύπου ή καθόλου δεν είναι εικόνα.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Δημιουργεί νέα παρουσία της InvalidImageFormatException με το καθορισμένο μήνυμα σφάλματος |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Δημιουργεί νέα παρουσία της InvalidImageFormatException με το καθορισμένο μήνυμα σφάλματος και μια αναφορά στην innerException που είναι η αιτία αυτής της εξαίρεσης |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Δημιουργεί νέα παρουσία της InvalidImageFormatException με το καθορισμένο μήνυμα σφάλματος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Κειμενικό μήνυμα, που περιγράφει το σφάλμα, μπορεί να είναι null ή κενό |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Δημιουργεί νέα παρουσία της InvalidImageFormatException με το καθορισμένο μήνυμα σφάλματος και μια αναφορά στην innerException που είναι η αιτία αυτής της εξαίρεσης


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Κειμενικό μήνυμα, που περιγράφει το σφάλμα, μπορεί να είναι null ή κενό |
|
|  | innerException | java.lang.RuntimeException | Η εξαίρεση που είναι η αιτία της τρέχουσας εξαίρεσης, ή μια αναφορά null εάν δεν έχει οριστεί innerException. |
|

