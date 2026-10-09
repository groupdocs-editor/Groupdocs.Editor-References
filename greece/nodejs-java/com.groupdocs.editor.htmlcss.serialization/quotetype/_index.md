---
title: "QuoteType"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αναπαριστά χαρακτήρες εισαγωγικών - μονό εισαγωγικό και διπλό εισαγωγικό"
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.serialization/quotetype/
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
|  | [getCharacter()](#getCharacter--) | Χαρακτήρας προς εισαγωγικό |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | Χαρακτήρας κωδικοποιημένος σε HTML |
|
|  | [toString()](#toString--) | Επιστρέφει μια συμβολοσειρά "SingleQuote" ή "DoubleQuote" ανάλογα με την τρέχουσα τιμή |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Υποδεικνύει εάν αυτή η παρουσία του τύπου εισαγωγικών είναι ίση με την καθορισμένη |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Υποδεικνύει εάν αυτή η παρουσία του τύπου εισαγωγικών είναι ίση με την καθορισμένη μη μετατρεπόμενη |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτόν τον χαρακτήρα |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Ελέγχει εάν δύο τιμές "QuoteType" είναι ίσες |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Ελέγχει εάν δύο τιμές "QuoteType" δεν είναι ίσες |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Μετατρέπει την καθορισμένη παρουσία [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) σε χαρακτήρα |
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


Χαρακτήρας προς εισαγωγικό


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


Υποδεικνύει εάν αυτή η παρουσία του τύπου εισαγωγικών είναι ίση με την καθορισμένη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Άλλη παρουσία του QuoteType για έλεγχο |
|

**Returns:**
boolean - true εάν είναι ίσες, false εάν είναι διαφορετικές

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Υποδεικνύει εάν αυτή η παρουσία του τύπου εισαγωγικών είναι ίση με την καθορισμένη μη μετατρεπόμενη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Μη μετατρεπόμενο αντικείμενο, αναμένεται να είναι τύπου [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |
|

**Returns:**
boolean - true εάν είναι ίσες, false εάν είναι διαφορετικές

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


Ελέγχει εάν δύο τιμές "QuoteType" είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Πρώτη τιμή για έλεγχο |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Δεύτερη τιμή για έλεγχο |
|

**Returns:**
boolean - true εάν είναι ίσα, false διαφορετικά

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


Ελέγχει εάν δύο τιμές "QuoteType" δεν είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Πρώτη τιμή για έλεγχο |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Δεύτερη τιμή για έλεγχο |
|

**Returns:**
boolean - false εάν είναι ίσα, true διαφορετικά

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Μετατρέπει την καθορισμένη παρουσία [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) σε χαρακτήρα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Παρουσία τύπου εισαγωγικών για μετατροπή |
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
|  | χαρακτήρας | χαρακτήρας | Ένα μονό εισαγωγικό (U+0027 APOSTROPHE) ή διπλό εισαγωγικό (U+0022 QUOTATION MARK) χαρακτήρας. Θα ριχθεί εξαίρεση εάν καθοριστεί οποιοσδήποτε άλλος χαρακτήρας. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
