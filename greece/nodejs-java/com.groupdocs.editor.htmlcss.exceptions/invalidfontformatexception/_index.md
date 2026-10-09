---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Η εξαίρεση που εκτοξεύεται όταν προσπαθείτε να ανοίξετε, φορτώσετε, αποθηκεύσετε ή επεξεργαστείτε με κάποιον τρόπο κάποιο περιεχόμενο που προφανώς είναι μια γραμματοσειρά υποστηριζόμενης γνωστής μορφής, αλλά στην πραγματικότητα είναι μια γραμματοσειρά μη υποστηριζόμενης ή απροσδόκητης μορφής ή καθόλου γραμματοσειρά."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

Η εξαίρεση που ρίχνεται όταν προσπαθείτε να ανοίξετε, φορτώσετε, αποθηκεύσετε ή επεξεργαστείτε με κάποιον τρόπο άλλο κάποιο περιεχόμενο, το οποίο υποτίθεται ότι είναι μια γραμματοσειρά υποστηριζόμενης (γνωστής) μορφής, αλλά στην πραγματικότητα είναι μια γραμματοσειρά μη υποστηριζόμενης ή απροσδόκητης μορφής ή καθόλου δεν είναι γραμματοσειρά.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Δημιουργεί νέο στιγμιότυπο του με το καθορισμένο μήνυμα σφάλματος |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Δημιουργεί νέο στιγμιότυπο του @see "InvalidFontFormatException" με το καθορισμένο μήνυμα σφάλματος και μια αναφορά στην εσωτερική εξαίρεση που είναι η αιτία αυτής της εξαίρεσης |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Δημιουργεί νέο στιγμιότυπο του με το καθορισμένο μήνυμα σφάλματος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Κειμενικό μήνυμα, που περιγράφει το σφάλμα, μπορεί να είναι null ή κενό |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Δημιουργεί νέο στιγμιότυπο του @see "InvalidFontFormatException" με το καθορισμένο μήνυμα σφάλματος και μια αναφορά στην εσωτερική εξαίρεση που είναι η αιτία αυτής της εξαίρεσης


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Κειμενικό μήνυμα, που περιγράφει το σφάλμα, μπορεί να είναι null ή κενό |
|
|  | innerException | java.lang.RuntimeException | Η εξαίρεση που είναι η αιτία της τρέχουσας εξαίρεσης, ή μια αναφορά null εάν δεν έχει καθοριστεί εσωτερική εξαίρεση. |
|

