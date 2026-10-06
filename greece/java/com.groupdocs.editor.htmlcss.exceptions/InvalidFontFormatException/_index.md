---
title: "InvalidFontFormatException"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Η εξαίρεση που ρίχνεται όταν προσπαθείτε να ανοίξετε, φορτώσετε, αποθηκεύσετε ή επεξεργαστείτε με κάποιον τρόπο κάποιο περιεχόμενο που υποτίθεται ότι είναι μια γραμματοσειρά υποστηριζόμενης γνωστής μορφής, αλλά στην πραγματικότητα είναι μια γραμματοσειρά μη υποστηριζόμενης ή απροσδόκητης μορφής ή καθόλου δεν είναι γραμματοσειρά."
type: docs
weight: 10
url: /el/java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

Η εξαίρεση που ρίχνεται όταν προσπαθείτε να ανοίξετε, φορτώσετε, αποθηκεύσετε ή επεξεργαστείτε με κάποιον τρόπο κάποιο περιεχόμενο, το οποίο υποτίθεται ότι είναι μια γραμματοσειρά υποστηριζόμενης (γνωστής) μορφής, αλλά στην πραγματικότητα είναι μια γραμματοσειρά μη υποστηριζόμενης ή απροσδόκητης μορφής ή καθόλου δεν είναι γραμματοσειρά.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Δημιουργεί νέα παρουσία με το καθορισμένο μήνυμα σφάλματος |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Δημιουργεί νέα παρουσία του @see \"InvalidFontFormatException\" με το καθορισμένο μήνυμα σφάλματος και μια αναφορά στην innerException που είναι η αιτία αυτής της εξαίρεσης |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Δημιουργεί νέα παρουσία με το καθορισμένο μήνυμα σφάλματος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Κειμενικό μήνυμα, που περιγράφει το σφάλμα, μπορεί να είναι null ή κενό |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Δημιουργεί νέα παρουσία του @see \"InvalidFontFormatException\" με το καθορισμένο μήνυμα σφάλματος και μια αναφορά στην innerException που είναι η αιτία αυτής της εξαίρεσης


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Κειμενικό μήνυμα, που περιγράφει το σφάλμα, μπορεί να είναι null ή κενό |
|
|  | innerException | java.lang.RuntimeException | Η εξαίρεση που είναι η αιτία της τρέχουσας εξαίρεσης, ή μια αναφορά null εάν δεν έχει οριστεί innerException. |
|

