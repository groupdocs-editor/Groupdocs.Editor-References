---
title: "FontStyle"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Ορίζει πώς πρέπει να μορφοποιηθεί η γραμματοσειρά με κανονική, πλάγια ή λοξή μορφή από την οικογένεια γραμματοσειρών της."
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

Ορίζει πώς πρέπει να μορφοποιηθεί η γραμματοσειρά με: κανονική, πλάγια ή λοξή μορφή από την οικογένεια γραμματοσειρών της.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Normal](#Normal) | Επιλέγει μια γραμματοσειρά που ταξινομείται ως κανονική μέσα σε μια οικογένεια γραμματοσειρών. |
|
|  | [Italic](#Italic) | Επιλέγει μια γραμματοσειρά που ταξινομείται ως πλάγια. |
|
|  | [Oblique](#Oblique) | Επιλέγει μια γραμματοσειρά που ταξινομείται ως λοξή. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isInitial()](#isInitial--) | Δείχνει εάν αυτό το στυλ γραμματοσειράς έχει αρχική τιμή (Κανονική) |
|
|  | [getValue()](#getValue--) | Επιστρέφει μια τιμή αυτού του στυλ γραμματοσειράς ως συμβολοσειρά |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Καθορίζει εάν αυτή η παρουσία στυλ γραμματοσειράς είναι ίση με την καθορισμένη |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία στυλ γραμματοσειράς είναι ίση με την καθορισμένη χωρίς μετατροπή τύπου |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Ελέγχει εάν δύο τιμές "FontStyle" είναι ίσες |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Ελέγχει εάν δύο τιμές "FontStyle" δεν είναι ίσες |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | Προσπαθεί να αναγνωρίσει μια καθορισμένη λέξη-κλειδί ως έγκυρη τιμή λέξης-κλειδί του 'font-style' και την επιστρέφει σε περίπτωση επιτυχίας ή NULL σε περίπτωση αποτυχίας. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


Επιλέγει μια γραμματοσειρά που ταξινομείται ως κανονική μέσα σε μια οικογένεια γραμματοσειρών. Αρχική τιμή.


### Italic {#Italic}
```
public static final FontStyle Italic
```


Επιλέγει μια γραμματοσειρά που ταξινομείται ως πλάγια. Εάν δεν υπάρχει διαθέσιμη πλάγια έκδοση της γραμματοσειράς, χρησιμοποιείται μια που ταξινομείται ως λοξή. Εάν καμία δεν είναι διαθέσιμη, το στυλ προσομοιώνεται τεχνητά.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


Επιλέγει μια γραμματοσειρά που ταξινομείται ως λοξή. Εάν δεν υπάρχει διαθέσιμη λοξή έκδοση της γραμματοσειράς, χρησιμοποιείται μια που ταξινομείται ως πλάγια. Εάν καμία δεν είναι διαθέσιμη, το στυλ προσομοιώνεται τεχνητά.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Δείχνει εάν αυτό το στυλ γραμματοσειράς έχει αρχική τιμή (Κανονική)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Επιστρέφει μια τιμή αυτού του στυλ γραμματοσειράς ως συμβολοσειρά


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


Καθορίζει εάν αυτή η παρουσία στυλ γραμματοσειράς είναι ίση με την καθορισμένη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Άλλη παρουσία font-style |
|

**Returns:**
boolean - true αν είναι ίσες, false διαφορετικά

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτή η παρουσία στυλ γραμματοσειράς είναι ίση με την καθορισμένη χωρίς μετατροπή τύπου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Άλλη μη μετατρεπόμενη font-style instance, μπορεί να είναι null |
|

**Returns:**
boolean - true αν είναι ίσες, false αν δεν είναι ίσες, null ή άλλου τύπου

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία


**Returns:**
int - Hash-code ως υπογεγραμμένος ακέραιος

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


Ελέγχει εάν δύο τιμές "FontStyle" είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Πρώτη τιμή για έλεγχο |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Δεύτερη τιμή για έλεγχο |
|

**Returns:**
boolean - true αν είναι ίσες, false διαφορετικά

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


Ελέγχει εάν δύο τιμές "FontStyle" δεν είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Πρώτη τιμή για έλεγχο |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Δεύτερη τιμή για έλεγχο |
|

**Returns:**
boolean - false αν είναι ίσες, true διαφορετικά

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


Προσπαθεί να αναγνωρίσει μια καθορισμένη λέξη-κλειδί ως έγκυρη τιμή λέξης-κλειδί του 'font-style' και την επιστρέφει σε περίπτωση επιτυχίας ή NULL σε περίπτωση αποτυχίας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | keyword | java.lang.String | Μια λέξη-κλειδί για ανάλυση |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Αποτέλεσμα, εάν η ανάλυση ήταν επιτυχής, ή #Normal.Normal διαφορετικά |
|

**Returns:**
boolean - true εάν η ανάλυση ήταν επιτυχής, false διαφορετικά

