---
title: "TextType"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει έναν υποστηριζόμενο τύπο κειμενικού πόρου"
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

Αντιπροσωπεύει έναν υποστηριζόμενο τύπο κειμενικού πόρου

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextType()](#TextType--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Ειδική τιμή, η οποία σηματοδοτεί ακαθόριστο, άγνωστο ή μη υποστηριζόμενο κείμενο |
πόρος
|
|  | [getCss()](#getCss--) | Τύπος CSS του κειμενικού πόρου |
|
|  | [getXml()](#getXml--) | Τύπος XML του κειμενικού πόρου |
|
|  | [getFormalName()](#getFormalName--) | Επιστρέφει ένα επίσημο όνομα αυτού του τύπου κειμενικού πόρου |
|
|  | [getFileExtension()](#getFileExtension--) | Επέκταση αρχείου (χωρίς τον αρχικό χαρακτήρα τελείας) ενός συγκεκριμένου κειμένου |
πόρος
|
|  | [getMimeCode()](#getMimeCode--) | Κωδικός MIME ενός συγκεκριμένου τύπου πόρου κειμένου |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο \"TextType\" |
αντίγραφο
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο, |
που προφανώς είναι μια άλλη παρουσία \"TextType\"
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Ορίζει εάν δύο συγκεκριμένα παραδείγματα \"TextType\" είναι ίσα |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Ορίζει εάν δύο συγκεκριμένα παραδείγματα \"TextType\" δεν είναι ίσα |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό hash, ο οποίος είναι ένας σταθερός αριθμός για αυτή τη συγκεκριμένη τιμή |
τύπος
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Επιστρέφει τιμή TextType, η οποία είναι ισοδύναμη με την επέκταση ονόματος αρχείου, η οποία εξάγεται από το καθορισμένο όνομα αρχείου με επέκταση ή καθαρή επέκταση |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


Ειδική τιμή, η οποία σηματοδοτεί ακαθόριστο, άγνωστο ή μη υποστηριζόμενο κείμενο
πόρος


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


Τύπος CSS του κειμενικού πόρου


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


Τύπος XML του κειμενικού πόρου


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Επιστρέφει ένα επίσημο όνομα αυτού του τύπου κειμενικού πόρου


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Επέκταση αρχείου (χωρίς τον αρχικό χαρακτήρα τελείας) ενός συγκεκριμένου κειμένου
πόρος


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Κωδικός MIME ενός συγκεκριμένου τύπου πόρου κειμένου


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο \"TextType\"
αντίγραφο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Άλλη παρουσία TextType, η οποία πρέπει να συγκριθεί με αυτήν για ισότητα |
|

**Returns:**
boolean - Επιστρέφει true εάν είναι ίσες ή false εάν δεν είναι ίσες

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο,
που προφανώς είναι μια άλλη παρουσία \"TextType\"


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Άλλη παρουσία TextType, η οποία είναι μετατρεπόμενη σε αντικείμενο |
|

**Returns:**
boolean - Επιστρέφει true εάν είναι ίσες ή false εάν δεν είναι ίσες

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


Ορίζει εάν δύο συγκεκριμένα παραδείγματα \"TextType\" είναι ίσα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Πρώτη παρουσία TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Δεύτερη παρουσία TextType |
|

**Returns:**
boolean - Επιστρέφει true εάν είναι ίσες ή false εάν δεν είναι ίσες

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


Ορίζει εάν δύο συγκεκριμένα παραδείγματα \"TextType\" δεν είναι ίσα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Πρώτη παρουσία TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Δεύτερη παρουσία TextType |
|

**Returns:**
boolean - Επιστρέφει true εάν δεν είναι ίσες ή false εάν είναι ίσες

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό hash, ο οποίος είναι ένας σταθερός αριθμός για αυτή τη συγκεκριμένη τιμή
τύπος


**Returns:**
int - Υπογεγραμμένος ακέραιος 4-μπάιτ. Επιστρέφει 0 εάν αυτή η παρουσία έχει προεπιλεγμένη τιμή.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


Επιστρέφει τιμή TextType, η οποία είναι ισοδύναμη με την επέκταση ονόματος αρχείου, η οποία εξάγεται από το καθορισμένο όνομα αρχείου με επέκταση ή καθαρή επέκταση


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα αρχείου | java.lang.String | Όνομα αρχείου με επέκταση, μπορεί να είναι σχετική ή απόλυτη διαδρομή, ή καθαρή επέκταση |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

