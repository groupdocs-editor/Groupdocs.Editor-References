---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει τύπους της γραμμής διακόσμησης κειμένου υπογράμμιση, κάτω παύλα, πάνω γραμμή και διαγώνια γραμμή"
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Αντιπροσωπεύει τύπους της γραμμής διακόσμησης κειμένου: υπογράμμιση (underscore), επάνω γραμμή και διαγράμμιση (strikethrough).

<br />

*** ** * ** ***

Αμετάβλητη δομή. Παρόμοια με το https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [None](#None) | Δεν παράγει διακόσμηση κειμένου. |
|
|  | [Underline](#Underline) | Κάθε γραμμή κειμένου είναι υπογραμμισμένη. |
|
|  | [Overline](#Overline) | Κάθε γραμμή κειμένου έχει μια γραμμή πάνω της. |
|
|  | [LineThrough](#LineThrough) | Κάθε γραμμή κειμένου έχει μια γραμμή στη μέση. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isInitial()](#isInitial--) | Δείχνει εάν αυτή η παρουσία έχει αρχική τιμή \\u2014 Καμία |
|
|  | [isUnderline()](#isUnderline--) | Δείχνει εάν η υπογράμμιση (κάτω παύλα) είναι ενεργοποιημένη |
|
|  | [isOverline()](#isOverline--) | Δείχνει εάν η υπέργραμμιση είναι ενεργοποιημένη |
|
|  | [isLineThrough()](#isLineThrough--) | Δείχνει εάν η διαγραφή (strikethrough) είναι ενεργοποιημένη |
|
|  | [getValue()](#getValue--) | Επιστρέφει μια τιμή όλων των σημαιών σε αυτήν την παρουσία ως κείμενο. |
|
|  | [toString()](#toString--) | Επιστρέφει μια τιμή όλων των σημαιών σε αυτήν την παρουσία ως κείμενο. |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Δείχνει εάν αυτή η παρουσία [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) είναι ίση με την καθορισμένη |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Δείχνει εάν αυτή η παρουσία [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) είναι ίση με την καθορισμένη χωρίς μετατροπή |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού (hash-code) αυτής της παρουσίας |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Ελέγχει εάν δύο "TextDecorationLineType" τιμές είναι ίσες |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Ελέγχει εάν δύο "TextDecorationLineType" τιμές δεν είναι ίσες |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Δημιουργεί και επιστρέφει μια παρουσία [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) με σημαιές, ορισμένες από τις καθορισμένες παραμέτρους |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Προσπαθεί να αναλύσει μια καθορισμένη συμβολοσειρά και να επιστρέψει μια έγκυρη παρουσία [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Συνδυάζει (συγχωνεύει) δύο καθορισμένους τύπους γραμμής και παράγει νέο τελικό τύπο γραμμής, όπου οι σημαιές συγχωνεύονται (ένωση) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Αφαιρεί τον δεύτερο καθορισμένο τύπο γραμμής από τον πρώτο καθορισμένο τύπο γραμμής και παράγει νέο τελικό τύπο γραμμής, όπου υπάρχουν μόνο εκείνες οι σημαιές από το πρώτο τελεστή, που δεν βρίσκονται στο δεύτερο τελεστή (διαφορά) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Επιστρέφει μια τομή μεταξύ του πρώτου και του δεύτερου τύπου γραμμής, όπου ενεργοποιούνται μόνο εκείνες οι σημαιές που είναι ενεργοποιημένες ταυτόχρονα και στα δύο τελεστές. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Μετατρέπει συγκεκριμένο byte (8-bit octet) στον αντίστοιχο [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), ρίχνει εξαίρεση εάν η μετατροπή είναι άκυρη |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


Δεν παράγει διακόσμηση κειμένου. Αρχική τιμή.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


Κάθε γραμμή κειμένου είναι υπογραμμισμένη.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


Κάθε γραμμή κειμένου έχει μια γραμμή πάνω της.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


Κάθε γραμμή κειμένου έχει μια γραμμή στη μέση.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Δείχνει εάν αυτή η παρουσία έχει αρχική τιμή \\u2014 Καμία


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Δείχνει εάν η υπογράμμιση (κάτω παύλα) είναι ενεργοποιημένη


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Δείχνει εάν η υπέργραμμιση είναι ενεργοποιημένη


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Δείχνει εάν η διαγραφή (strikethrough) είναι ενεργοποιημένη


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Επιστρέφει μια τιμή όλων των σημαιών σε αυτήν την παρουσία ως κείμενο.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια τιμή όλων των σημαιών σε αυτήν την παρουσία ως κείμενο.


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Δείχνει εάν αυτή η παρουσία [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) είναι ίση με την καθορισμένη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Άλλη παρουσία [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|

**Returns:**
boolean -  true  εάν είναι ίσες,  false  διαφορετικά

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Δείχνει εάν αυτή η παρουσία [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) είναι ίση με την καθορισμένη χωρίς μετατροπή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | java.lang.Object | Άλλη παρουσία [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) μετατρεπόμενη σε αντικείμενο |
|

**Returns:**
boolean -  true  εάν είναι ίσες,  false  διαφορετικά

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού (hash-code) αυτής της παρουσίας


**Returns:**
int - Υπογεγραμμένος ακέραιος κωδικός κατακερματισμού

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


Ελέγχει εάν δύο "TextDecorationLineType" τιμές είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Πρώτος τελεστής για έλεγχο |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Δεύτερος τελεστής για έλεγχο |
|

**Returns:**
boolean -  true  εάν είναι ίσες,  false  διαφορετικά

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Ελέγχει εάν δύο "TextDecorationLineType" τιμές δεν είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Πρώτος τελεστής για έλεγχο |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Δεύτερος τελεστής για έλεγχο |
|

**Returns:**
boolean -  true  αν είναι άνισοι,  false  διαφορετικά

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Δημιουργεί και επιστρέφει μια παρουσία [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) με σημαιές, ορισμένες από τις καθορισμένες παραμέτρους


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | isUnderline | boolean | Καθορίζει αν η σημαία υπογράμμισης είναι ενεργοποιημένη ή όχι |
|
|  | isOverline | boolean | Καθορίζει αν η σημαία υπεργράμμισης είναι ενεργοποιημένη ή όχι |
|
|  | isLineThrough | boolean | Καθορίζει αν η σημαία διαγράμμισης είναι ενεργοποιημένη ή όχι |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Προσπαθεί να αναλύσει μια καθορισμένη συμβολοσειρά και να επιστρέψει μια έγκυρη παρουσία [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | εισόδους | java.lang.String | Συμβολοσειρά εισόδου |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Αποτέλεσμα. Εάν η ανάλυση είναι μη έγκυρη, είναι μια τιμή #None.None |
|

**Returns:**
boolean -  true  αν η ανάλυση ήταν επιτυχής,  false  σε περίπτωση αποτυχίας

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Συνδυάζει (συγχωνεύει) δύο καθορισμένους τύπους γραμμής και παράγει νέο τελικό τύπο γραμμής, όπου οι σημαιές συγχωνεύονται (ένωση)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Πρώτος τελεστής τύπου γραμμής |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Δεύτερος τελεστής τύπου γραμμής |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


Αφαιρεί τον δεύτερο καθορισμένο τύπο γραμμής από τον πρώτο καθορισμένο τύπο γραμμής και παράγει νέο τελικό τύπο γραμμής, όπου υπάρχουν μόνο εκείνες οι σημαιές από το πρώτο τελεστή, που δεν βρίσκονται στο δεύτερο τελεστή (διαφορά)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Πρώτος τελεστής τύπου γραμμής |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Δεύτερος τελεστής τύπου γραμμής |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


Επιστρέφει μια τομή μεταξύ των τύπων πρώτης και δεύτερης γραμμής, όπου ενεργοποιούνται μόνο εκείνες οι σημαίες που είναι ενεργοποιημένες ταυτόχρονα και στα δύο τελεστές. Έχει την υψηλότερη προτεραιότητα μεταξύ όλων των τελεστών (υψηλότερη από την union και τη difference)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Πρώτος τελεστής τύπου γραμμής |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Δεύτερος τελεστής τύπου γραμμής |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


Μετατρέπει συγκεκριμένο byte (8-bit octet) στον αντίστοιχο [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), ρίχνει εξαίρεση εάν η μετατροπή είναι άκυρη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | οκτέτο | byte | Ένα 8-bit οκτέτο (bitfield), όπου τα 5 πρώτα bits είναι μηδενικά, ενώ τα τελευταία 3 υποδεικνύουν σημαίες |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
