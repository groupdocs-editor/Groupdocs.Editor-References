---
title: "ResourceTypeDetector"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Βοηθητικές στατικές μεθόδους για την ανίχνευση τύπων/μορφών πόρων"
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

Στατικές βοηθητικές μεθόδους για την ανίχνευση τύπων πόρων (μορφές).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | Ανιχνεύει έναν τύπο από το καθορισμένο όνομα αρχείου και επιστρέφει ένα αντικείμενο του |
αντίστοιχου IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | Προσπαθεί να αναλύσει μια ροή εισόδου και δημιουργεί ένα από τα υποστηριζόμενα HTML |
πόρους από αυτό, λαμβάνοντας υπόψη έναν καθορισμένο υποθετικό τύπο, εάν
δεν είναι null
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


Ανιχνεύει έναν τύπο από το καθορισμένο όνομα αρχείου και επιστρέφει ένα αντικείμενο του
αντίστοιχου IResourceType


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα αρχείου | java.lang.String | Όνομα αρχείου εισόδου, από το οποίο αυτή η μέθοδος θα προσπαθήσει να εξάγει την προκύπτουσα υλοποίηση IResourceType |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


Προσπαθεί να αναλύσει μια ροή εισόδου και δημιουργεί ένα από τα υποστηριζόμενα HTML
πόρους από αυτό, λαμβάνοντας υπόψη έναν καθορισμένο υποθετικό τύπο, εάν
δεν είναι null


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | Ροή εισόδου, η οποία προφανώς περιέχει έναν πόρο HTML. Εάν είναι μη έγκυρη, θα ριχτεί μια εξαίρεση. |
|
|  | name | java.lang.String | Όνομα πόρου, το οποίο θα χρησιμοποιηθεί για το δημιουργημένο και επιστρεφόμενο πόρο σε περίπτωση επιτυχίας. Δεν μπορεί να είναι NULL, κενό ή κενό διάστημα |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | Υποτιθέμενη μορφή του εισερχόμενου πόρου HTML, η οποία είναι χρήσιμη για την επίτευξη της καλύτερης απόδοσης. Εάν είναι εντελώς άγνωστη, χρησιμοποιήστε την τιμή NULL. Μπορεί να είναι λανθασμένη, κάτι που θα μειώσει μόνο την απόδοση. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

