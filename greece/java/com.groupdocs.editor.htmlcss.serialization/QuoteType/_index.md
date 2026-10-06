---
title: "QuoteType"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά χαρακτήρες εισαγωγικών - μονό εισαγωγικό και διπλό εισαγωγικό"
type: docs
weight: 10
url: /el/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

Αντιπροσωπεύει χαρακτήρες εισαγωγικών - μονό εισαγωγικό (') και διπλό εισαγωγικό (\")

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | Μονό εισαγωγικό (χαρακτήρας U+0027 APOSTROPHE) |
|
|  | [DoubleQuote](#DoubleQuote) | Διπλό εισαγωγικό (χαρακτήρας U+0022 QUOTATION MARK) |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCode()](#getCode--) | Σημείο κώδικα του τρέχοντος χαρακτήρα (U+0027 ή U+0022) |
|
|  | [getCharacter()](#getCharacter--) | Χαρακτήρας προς εισαγωγισμό |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | Χαρακτήρας κωδικοποιημένος σε HTML |
|
|  | [toString()](#toString--) | Επιστρέφει μια συμβολοσειρά "SingleQuote" ή "DoubleQuote" ανάλογα με την τρέχουσα τιμή |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Δείχνει αν αυτή η παρουσία του τύπου εισαγωγικών είναι ίση με την καθορισμένη |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Δείχνει αν αυτή η παρουσία του τύπου εισαγωγικών είναι ίση με την καθορισμένη χωρίς μετατροπή τύπου |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτόν τον χαρακτήρα |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Ελέγχει αν δύο τιμές "QuoteType" είναι ίσες |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Ελέγχει αν δύο τιμές "QuoteType" δεν είναι ίσες |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Μετατρέπει το καθορισμένο παράδειγμα [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) σε χαρακτήρα |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | Μετατρέπει συγκεκριμένο χαρακτήρα στον αντίστοιχο [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), ρίχνει εξαίρεση εάν η μετατροπή είναι άκυρη |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


Μονό εισαγωγικό (χαρακτήρας U+0027 APOSTROPHE)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


Διπλό εισαγωγικό (χαρακτήρας U+0022 QUOTATION MARK)


### getCode() {#getCode--}
```
public final int getCode()
```


Σημείο κώδικα του τρέχοντος χαρακτήρα (U+0027 ή U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Χαρακτήρας προς εισαγωγισμό


**Returns:**
χαρακτήρας
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


Χαρακτήρας κωδικοποιημένος σε HTML


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια συμβολοσειρά "SingleQuote" ή "DoubleQuote" ανάλογα με την τρέχουσα τιμή


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


Δείχνει αν αυτή η παρουσία του τύπου εισαγωγικών είναι ίση με την καθορισμένη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Άλλο παράδειγμα του QuoteType για έλεγχο |
|

**Returns:**
boolean - true εάν είναι ίσες, false εάν δεν είναι ίσες

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Δείχνει αν αυτή η παρουσία του τύπου εισαγωγικών είναι ίση με την καθορισμένη χωρίς μετατροπή τύπου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Ανέμετο αντικείμενο, αναμένεται να είναι τύπου [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |
|

**Returns:**
boolean - true εάν είναι ίσες, false εάν δεν είναι ίσες

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτόν τον χαρακτήρα


**Returns:**
int - Hash-code ως υπογεγραμμένος ακέραιος

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


Ελέγχει αν δύο τιμές "QuoteType" είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Πρώτη τιμή για έλεγχο |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Δεύτερη τιμή για έλεγχο |
|

**Returns:**
boolean - true αν είναι ίσες, false διαφορετικά

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


Ελέγχει αν δύο τιμές "QuoteType" δεν είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Πρώτη τιμή για έλεγχο |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Δεύτερη τιμή για έλεγχο |
|

**Returns:**
boolean - false αν είναι ίσες, true διαφορετικά

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Μετατρέπει το καθορισμένο παράδειγμα [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) σε χαρακτήρα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Παράδειγμα τύπου Quote για μετατροπή |
|

**Returns:**
χαρακτήρας
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


Μετατρέπει συγκεκριμένο χαρακτήρα στον αντίστοιχο [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), ρίχνει εξαίρεση εάν η μετατροπή είναι άκυρη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | χαρακτήρας | χαρακτήρας | Ένας μονός εισαγωγικός (U+0027 ΑΠΟΣΤΡΟΦΟ) ή διπλός εισαγωγικός (U+0022 ΣΥΜΒΟΛΟ ΠΑΡΑΤΥΠΩΣΗΣ) χαρακτήρας. Θα ριχθεί εξαίρεση εάν καθοριστεί οποιοσδήποτε άλλος χαρακτήρας. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
