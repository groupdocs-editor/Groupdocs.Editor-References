---
title: "TextDecorationLineType"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά τύπους της γραμμής διακόσμησης κειμένου underline underscore overline και line-through strikethrough"
type: docs
weight: 13
url: /el/java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Αντιπροσωπεύει τύπους της γραμμής διακόσμησης κειμένου: υπογράμμιση (underscore), υπεργράμμιση και διαγραφή (strikethrough).

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
|  | [None](#None) | Παράγει καμία διακόσμηση κειμένου. |
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
|  | [isInitial()](#isInitial--) | Δείχνει εάν αυτή η παρουσία έχει αρχική τιμή \\u2014 None |
|
|  | [isUnderline()](#isUnderline--) | Δείχνει εάν η υπογράμμιση (underscore) είναι ενεργοποιημένη |
|
|  | [isOverline()](#isOverline--) | Δείχνει εάν η υπεργράμμιση είναι ενεργοποιημένη |
|
|  | [isLineThrough()](#isLineThrough--) | Δείχνει εάν η διαγράμμιση (strikethrough) είναι ενεργοποιημένη |
|
|  | [getValue()](#getValue--) | Επιστρέφει μια τιμή όλων των σημαιών σε αυτήν την παρουσία ως κείμενο |
|
|  | [toString()](#toString--) | Επιστρέφει μια τιμή όλων των σημαιών σε αυτήν την παρουσία ως κείμενο |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Δείχνει εάν αυτή η [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) παρουσία είναι ίση με την καθορισμένη |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Δείχνει εάν αυτή η [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) παρουσία είναι ίση με την καθορισμένη χωρίς μετατροπή |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού (hash-code) αυτής της παρουσίας |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Ελέγχει εάν δύο τιμές "TextDecorationLineType" είναι ίσες |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Ελέγχει εάν δύο τιμές "TextDecorationLineType" δεν είναι ίσες |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Δημιουργεί και επιστρέφει μια [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) παρουσία με σημαίες, ορισμένες από τις καθορισμένες παραμέτρους |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Προσπαθεί να αναλύσει μια καθορισμένη συμβολοσειρά και να επιστρέψει μια έγκυρη [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) παρουσία |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Συνδυάζει (συγχωνεύει) δύο καθορισμένους τύπους γραμμής και παράγει νέο τελικό τύπο γραμμής, όπου οι σημαίες συγχωνεύονται (ένωση) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Αφαιρεί τον δεύτερο καθορισμένο τύπο γραμμής από τον πρώτο καθορισμένο τύπο γραμμής και παράγει νέο τελικό τύπο γραμμής, όπου υπάρχουν μόνο εκείνες οι σημαίες από το πρώτο τελεστή, που δεν βρίσκονται στον δεύτερο τελεστή (διαφορά) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Επιστρέφει μια τομή μεταξύ του πρώτου και του δεύτερου τύπου γραμμής, όπου ενεργοποιούνται μόνο εκείνες οι σημαίες που είναι ενεργοποιημένες ταυτόχρονα και στα δύο τελεστές. |
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


Παράγει καμία διακόσμηση κειμένου. Αρχική τιμή.


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


Δείχνει εάν αυτή η παρουσία έχει αρχική τιμή \\u2014 None


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Δείχνει εάν η υπογράμμιση (underscore) είναι ενεργοποιημένη


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Δείχνει εάν η υπεργράμμιση είναι ενεργοποιημένη


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Δείχνει εάν η διαγράμμιση (strikethrough) είναι ενεργοποιημένη


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Επιστρέφει μια τιμή όλων των σημαιών σε αυτήν την παρουσία ως κείμενο


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια τιμή όλων των σημαιών σε αυτήν την παρουσία ως κείμενο


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Δείχνει εάν αυτή η [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) παρουσία είναι ίση με την καθορισμένη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Άλλη [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) παρουσία |
|

**Returns:**
boolean -  true  εάν είναι ίσες,  false  διαφορετικά

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Δείχνει εάν αυτή η [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) παρουσία είναι ίση με την καθορισμένη χωρίς μετατροπή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | java.lang.Object | Άλλη [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) παρουσία, μετατρεπόμενη σε αντικείμενο |
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


Ελέγχει εάν δύο τιμές "TextDecorationLineType" είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Πρώτος τελεστής για έλεγχο |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Δεύτερο τελεστή για έλεγχο |
|

**Returns:**
boolean -  true  εάν είναι ίσες,  false  διαφορετικά

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Ελέγχει εάν δύο τιμές "TextDecorationLineType" δεν είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Πρώτος τελεστής για έλεγχο |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Δεύτερο τελεστή για έλεγχο |
|

**Returns:**
boolean -  true  αν είναι άνισοι,  false  διαφορετικά

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Δημιουργεί και επιστρέφει μια [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) παρουσία με σημαίες, ορισμένες από τις καθορισμένες παραμέτρους


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | isUnderline | boolean | Καθορίζει εάν η σημαία υπογράμμισης είναι ενεργοποιημένη ή όχι |
|
|  | isOverline | boolean | Καθορίζει εάν η σημαία υπεργράμμισης είναι ενεργοποιημένη ή όχι |
|
|  | isLineThrough | boolean | Καθορίζει εάν η σημαία διαγράμμισης είναι ενεργοποιημένη ή όχι |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Προσπαθεί να αναλύσει μια καθορισμένη συμβολοσειρά και να επιστρέψει μια έγκυρη [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) παρουσία


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | είσοδος | java.lang.String | Συμβολοσειρά εισόδου |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Αποτέλεσμα. Εάν η ανάλυση είναι άκυρη, είναι μια τιμή #None.None |
|

**Returns:**
boolean -  true  εάν η ανάλυση ήταν επιτυχής,  false  σε περίπτωση αποτυχίας

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Συνδυάζει (συγχωνεύει) δύο καθορισμένους τύπους γραμμής και παράγει νέο τελικό τύπο γραμμής, όπου οι σημαίες συγχωνεύονται (ένωση)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Τελεστής τύπου πρώτης γραμμής |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Τελεστής τύπου δεύτερης γραμμής |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


Αφαιρεί τον δεύτερο καθορισμένο τύπο γραμμής από τον πρώτο καθορισμένο τύπο γραμμής και παράγει νέο τελικό τύπο γραμμής, όπου υπάρχουν μόνο εκείνες οι σημαίες από το πρώτο τελεστή, που δεν βρίσκονται στον δεύτερο τελεστή (διαφορά)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Τελεστής τύπου πρώτης γραμμής |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Τελεστής τύπου δεύτερης γραμμής |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


Επιστρέφει μια τομή μεταξύ των τύπων πρώτης και δεύτερης γραμμής, όπου ενεργοποιούνται μόνο εκείνες οι σημαίες που είναι ενεργοποιημένες ταυτόχρονα και στα δύο τελεστές. Έχει την υψηλότερη προτεραιότητα μεταξύ όλων των τελεστών (υψηλότερη από την ένωση και τη διαφορά)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Τελεστής τύπου πρώτης γραμμής |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Τελεστής τύπου δεύτερης γραμμής |
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
|  | οκτάδα | byte | Μια 8-bit οκτάδα (bitfield), όπου τα 5 πρώτα bits είναι μηδενικά, ενώ τα τελευταία 3 υποδεικνύουν σημαίες |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
