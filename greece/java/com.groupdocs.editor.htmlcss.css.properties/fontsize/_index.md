---
title: "FontSize"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει ένα μέγεθος γραμματοσειράς ως ειδική μονάδα ή τιμή μήκους που καθορίζει το μέγεθος της γραμματοσειράς, ιστορικά το πλάτος του κεφαλαίου M."
type: docs
weight: 10
url: /el/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Αντιπροσωπεύει ένα μέγεθος γραμματοσειράς ως ειδική μονάδα ή τιμή μήκους, η οποία καθορίζει το μέγεθος της γραμματοσειράς (παραδοσιακά το πλάτος του κεφαλαίου "M").

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Medium](#Medium) | Μεσαίο μέγεθος. |
|
|  | [XxSmall](#XxSmall) | Το πολύ μικρό absolute-size |
|
|  | [XSmall](#XSmall) | Το μετρίως μικρό absolute-size |
|
|  | [Small](#Small) | Το κανονικά μικρό absolute-size |
|
|  | [Large](#Large) | Το κανονικά μεγάλο absolute-size |
|
|  | [XLarge](#XLarge) | Το μετρίως μεγάλο absolute-size |
|
|  | [XxLarge](#XxLarge) | Το πολύ μεγάλο absolute-size |
|
|  | [Larger](#Larger) | Μεγαλύτερο relative-size - η γραμματοσειρά θα είναι μεγαλύτερη σε σχέση με το font-size του γονικού στοιχείου, περίπου με τον λόγο που χρησιμοποιείται για διαχωρισμό των παραπάνω absolute-size keywords. |
|
|  | [Smaller](#Smaller) | Μικρότερο relative-size - η γραμματοσειρά θα είναι μικρότερη σε σχέση με το font-size του γονικού στοιχείου, περίπου με τον λόγο που χρησιμοποιείται για διαχωρισμό των παραπάνω absolute-size keywords. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isInitial()](#isInitial--) | Δείχνει αν αυτό το font-size έχει αρχική τιμή (Medium) |
|
|  | [getValue()](#getValue--) | Επιστρέφει μια τιμή αυτού του font size ως συμβολοσειρά |
|
|  | [isLengthDefined()](#isLengthDefined--) | Δείχνει εάν αυτό το font-size ορίζεται με μια τιμή [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |
|
|  | [getLength()](#getLength--) | Μια τιμή μήκους, εάν αυτό το font-size ορίστηκε με αυτήν, ή ρίχνει εξαίρεση διαφορετικά |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Δείχνει εάν αυτό το font-size ορίζεται με απόλυτο μέγεθος ως λέξη-κλειδί, βάσει του προεπιλεγμένου μεγέθους γραμματοσειράς του χρήστη (που είναι medium) |
|
|  | [isRelativeSize()](#isRelativeSize--) | Δείχνει εάν αυτό το font-size ορίζεται με σχετικό μέγεθος ως λέξη-κλειδί. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Καθορίζει εάν αυτή η παρουσία του font-size είναι ίση με την καθορισμένη |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία του font-size είναι ίση με την καθορισμένη μη μετατρεπόμενη |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Ελέγχει εάν δύο τιμές "FontSize" είναι ίσες |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Ελέγχει εάν δύο τιμές "FontSize" δεν είναι ίσες |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Δημιουργεί ένα font-size από το καθορισμένο μήκος |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Προσπαθεί να αναγνωρίσει μια καθορισμένη λέξη-κλειδί ως έγκυρη τιμή λέξης-κλειδί του 'font-size' και την επιστρέφει σε περίπτωση επιτυχίας ή NULL σε περίπτωση αποτυχίας. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Μέγεθος medium. Αρχική τιμή.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


Το πολύ μικρό absolute-size


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


Το μετρίως μικρό absolute-size


### Small {#Small}
```
public static final FontSize Small
```


Το κανονικά μικρό absolute-size


### Large {#Large}
```
public static final FontSize Large
```


Το κανονικά μεγάλο absolute-size


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


Το μετρίως μεγάλο absolute-size


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


Το πολύ μεγάλο absolute-size


### Larger {#Larger}
```
public static final FontSize Larger
```


Μεγαλύτερο relative-size - η γραμματοσειρά θα είναι μεγαλύτερη σε σχέση με το font-size του γονικού στοιχείου, περίπου με τον λόγο που χρησιμοποιείται για διαχωρισμό των παραπάνω absolute-size keywords.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Μικρότερο relative-size - η γραμματοσειρά θα είναι μικρότερη σε σχέση με το font-size του γονικού στοιχείου, περίπου με τον λόγο που χρησιμοποιείται για διαχωρισμό των παραπάνω absolute-size keywords.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Δείχνει αν αυτό το font-size έχει αρχική τιμή (Medium)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Επιστρέφει μια τιμή αυτού του font size ως συμβολοσειρά


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Δείχνει εάν αυτό το font-size ορίζεται με μια τιμή [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


Μια τιμή μήκους, εάν αυτό το font-size ορίστηκε με αυτήν, ή ρίχνει εξαίρεση διαφορετικά


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Δείχνει εάν αυτό το font-size ορίζεται με απόλυτο μέγεθος ως λέξη-κλειδί, βάσει του προεπιλεγμένου μεγέθους γραμματοσειράς του χρήστη (που είναι medium)


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Δείχνει εάν αυτό το font-size ορίζεται με σχετικό μέγεθος ως λέξη-κλειδί. Η γραμματοσειρά θα είναι μεγαλύτερη ή μικρότερη σε σχέση με το μέγεθος γραμματοσειράς του γονικού στοιχείου, περίπου με τον λόγο που χρησιμοποιείται για το διαχωρισμό των απόλυτων λέξεων-κλειδιών μεγέθους.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Καθορίζει εάν αυτή η παρουσία του font-size είναι ίση με την καθορισμένη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Άλλη παρουσία του font-size |
|

**Returns:**
boolean - true αν είναι ίσες, false διαφορετικά

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτή η παρουσία του font-size είναι ίση με την καθορισμένη μη μετατρεπόμενη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Άλλη μη μετατρεπόμενη παρουσία του font-size, μπορεί να είναι null |
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

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Ελέγχει εάν δύο τιμές "FontSize" είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Πρώτη τιμή για έλεγχο |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Δεύτερη τιμή για έλεγχο |
|

**Returns:**
boolean - true αν είναι ίσες, false διαφορετικά

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Ελέγχει εάν δύο τιμές "FontSize" δεν είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Πρώτη τιμή για έλεγχο |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Δεύτερη τιμή για έλεγχο |
|

**Returns:**
boolean - false αν είναι ίσες, true διαφορετικά

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Δημιουργεί ένα font-size από το καθορισμένο μήκος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Μια τιμή μήκους, δεν μπορεί να είναι χωρίς μονάδα ή αρνητική |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


Προσπαθεί να αναγνωρίσει μια καθορισμένη λέξη-κλειδί ως έγκυρη τιμή λέξης-κλειδί του 'font-size' και την επιστρέφει σε περίπτωση επιτυχίας ή NULL σε περίπτωση αποτυχίας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | keyword | java.lang.String | Μια λέξη-κλειδί για ανάλυση |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Αποτέλεσμα, η ανάλυση ήταν επιτυχής, ή #Medium.Medium διαφορετικά |
|

**Returns:**
boolean - true εάν η ανάλυση ήταν επιτυχής, false διαφορετικά

