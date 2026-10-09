---
title: "Μήκος"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει μια τιμή μήκους CSS σε οποιαδήποτε υποστηριζόμενη μονάδα, συμπεριλαμβανομένου του ποσοστού και του τύπου χωρίς μονάδα."
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

Αντιπροσωπεύει μια τιμή μήκους CSS σε οποιαδήποτε υποστηριζόμενη μονάδα, συμπεριλαμβανομένου του ποσοστού
και τύπου χωρίς μονάδα. Οι τιμές μπορεί να είναι ακέραιες ή δεκαδικές, αρνητικές, μηδέν και
θετικές. Αμετάβλητη δομή.

*** ** * ** ***


Αυτός ο τύπος καλύπτει τους επόμενους τύπους δεδομένων CSS:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Length()](#Length--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | Ακέραιος μηδέν χωρίς μονάδα - προεπιλεγμένη τιμή, το ίδιο με την προεπιλεγμένη χωρίς παραμέτρους |
κατασκευαστής
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | Δημιουργεί και επιστρέφει μια παρουσία του τύπου Length με τον καθορισμένο αριθμό κινητής υποδιαστολής |
και μονάδα
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | Δημιουργεί και επιστρέφει μια παρουσία του τύπου Length με τον καθορισμένο αριθμό διπλής ακρίβειας |
και μονάδα
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | Δημιουργεί και επιστρέφει μια παρουσία τύπου Length με συγκεκριμένο ακέραιο |
αριθμός και μονάδα
|
|  | [isUnitlessZero()](#isUnitlessZero--) | Καθορίζει εάν αυτή η παρουσία είναι μηδέν χωρίς μονάδα ή όχι. |
|
|  | [isDefault()](#isDefault--) | Δείχνει εάν αυτή η παρουσία Length έχει προεπιλεγμένη τιμή \\u2014 χωρίς μονάδα |
μηδέν.
|
|  | [getUnitType()](#getUnitType--) | Επιστρέφει έναν τύπο μονάδας αυτής της παρουσίασης Length. |
|
|  | [isInteger()](#isInteger--) | Δείχνει εάν η αριθμητική τιμή αυτής της παρουσίας Length ήταν |
αρχικά καθορισμένη και αποθηκευμένη ως ακέραιος (INT32) αριθμός
|
|  | [isFloat()](#isFloat--) | Δείχνει εάν η αριθμητική τιμή αυτής της παρουσίας Length ήταν |
αρχικά καθορισμένη και αποθηκευμένη ως δεκαδικός (FP32) αριθμός
|
|  | [getFloatValue()](#getFloatValue--) | Επιστρέφει μια δεκαδική αριθμητική τιμή της παρουσίας Length. |
|
|  | [getIntegerValue()](#getIntegerValue--) | Επιστρέφει μια ακέραια αριθμητική τιμή αυτής της παρουσίας Length, εάν είναι |
εσωτερικά αποθηκευμένη ως ακέραιος, ή ρίχνει εξαίρεση, εάν ήταν
αρχικά αποθηκευμένη ως δεκαδικός αριθμός.
|
|  | [isAbsolute()](#isAbsolute--) | Λαμβάνει εάν το μήκος δίνεται σε απόλυτες μονάδες. |
|
|  | [isRelative()](#isRelative--) | Λαμβάνει εάν το μήκος δίνεται σε σχετικές μονάδες. |
|
|  | [isZero()](#isZero--) | Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι μηδενικός αριθμός |
|
|  | [isNegative()](#isNegative--) | Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι αρνητικός αριθμός |
|
|  | [isPositive()](#isPositive--) | Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι θετικός αριθμός |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | Η τιμή έχει τύπο χωρίς μονάδα, αλλά δεν είναι μηδέν - θετική ή αρνητική |
number
|
|  | [toPixel()](#toPixel--) | Μετατρέπει το μήκος σε αριθμό εικονοστοιχείων, εάν είναι δυνατόν. |
|
|  | [to(int unit)](#to-int-) | Μετατρέπει το μήκος στη δοθείσα μονάδα, εάν είναι δυνατόν. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτού του μήκους στον καθορισμένο τύπο μονάδας. |
|
|  | [serializeDefault()](#serializeDefault--) | Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτού του μήκους στην αρχική του |
μορφή (όπως αποθηκεύεται), χωρίς να μετατρέπει την τιμή του μήκους σε κάποια άλλη
τύπο μονάδας
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Ορίζει εάν αυτή η τιμή είναι ίση με το άλλο καθορισμένο μήκος |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτό το μήκος είναι ίσο με το καθορισμένο αντικείμενο |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | Πολλαπλασιάζει το δοσμένο Length με τον δοσμένο παράγοντα |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Ελέγχει την ισότητα των δύο δοσμένων μηκών. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Ελέγχει την ανισότητα των δύο δοσμένων μηκών. |
|
|  | [hashCode()](#hashCode--) | Υπολογίζει και επιστρέφει έναν κωδικό κατακερματισμού (hash-code) αυτού του αντικειμένου Length συνδυάζοντας |
τους κωδικούς κατακερματισμού της τιμής και του τύπου μονάδας
|
|  | [deepClone()](#deepClone--) | Επιστρέφει ένα πλήρες αντίγραφο αυτού του αντικειμένου Length |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Προσπαθεί να αναλύσει το καθορισμένο όνομα μονάδας και να επιστρέψει την αντίστοιχη τιμή ενός |
Enum μονάδας.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | Προσπαθεί να αναλύσει μια καθορισμένη συμβολοσειρά ως τιμή Length, συμπεριλαμβανομένου του |
αριθμητικού τιμής και του ονόματος μονάδας
|
|  | [parse(String input)](#parse-java.lang.String-) | Αναλύει και επιστρέφει την καθορισμένη συμβολοσειρά ως τιμή Length, συμπεριλαμβανομένου του |
αριθμητικού τιμής και του ονόματος μονάδας, ή ρίχνει μια εξαίρεση σε περίπτωση αποτυχίας
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


Ακέραιος μηδέν χωρίς μονάδα - προεπιλεγμένη τιμή, το ίδιο με την προεπιλεγμένη χωρίς παραμέτρους
κατασκευαστής


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


Δημιουργεί και επιστρέφει μια παρουσία του τύπου Length με τον καθορισμένο αριθμό κινητής υποδιαστολής
και μονάδα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | float | \>Οποιοσδήποτε αριθμός float (FP32) |
|
|  | μονάδα | int | Οποιοσδήποτε έγκυρος τύπος μονάδας |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


Δημιουργεί και επιστρέφει μια παρουσία του τύπου Length με τον καθορισμένο αριθμό διπλής ακρίβειας
και μονάδα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | διπλός | Οποιοσδήποτε αριθμός double (FP64), που θα μετατραπεί σε float (FP32) |
|
|  | μονάδα | int | Οποιοσδήποτε έγκυρος τύπος μονάδας |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


Δημιουργεί και επιστρέφει μια παρουσία τύπου Length με συγκεκριμένο ακέραιο
αριθμός και μονάδα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Οποιοσδήποτε ακέραιος αριθμός |
|
|  | μονάδα | int | Οποιοσδήποτε έγκυρος τύπος μονάδας |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


Καθορίζει εάν αυτή η παρουσία είναι μηδενική χωρίς μονάδα ή όχι. Μηδενική χωρίς μονάδα
είναι η προεπιλεγμένη τιμή αυτού του τύπου. Το ίδιο με την ιδιότητα IsDefault.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Δείχνει εάν αυτή η παρουσία Length έχει προεπιλεγμένη τιμή \\u2014 χωρίς μονάδα
μηδέν. Το ίδιο με την ιδιότητα IsUnitlessZero.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


Επιστρέφει έναν τύπο μονάδας αυτής της παρουσίασης Length.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Δείχνει εάν η αριθμητική τιμή αυτής της παρουσίας Length ήταν
αρχικά καθορισμένη και αποθηκευμένη ως ακέραιος (INT32) αριθμός


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Δείχνει εάν η αριθμητική τιμή αυτής της παρουσίας Length ήταν
αρχικά καθορισμένη και αποθηκευμένη ως δεκαδικός (FP32) αριθμός


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Επιστρέφει μια αριθμητική τιμή float του αντικειμένου Length. Ποτέ δεν ρίχνει ένα
εξαίρεση - μετατρέπει την τιμή Integer σε Float εάν είναι απαραίτητο.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Επιστρέφει μια ακέραια αριθμητική τιμή αυτής της παρουσίας Length, εάν είναι
εσωτερικά αποθηκευμένη ως ακέραιος, ή ρίχνει εξαίρεση, εάν ήταν
αρχικά αποθηκευμένη ως δεκαδικός αριθμός.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Λαμβάνει εάν το μήκος δίνεται σε απόλυτες μονάδες. Ένα τέτοιο μήκος μπορεί να
μετατραπεί σε εικονοστοιχεία.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Λαμβάνει εάν το μήκος δίνεται σε σχετικές μονάδες. Ένα τέτοιο μήκος δεν μπορεί να
μετατραπεί σε εικονοστοιχεία.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι μηδενικός αριθμός


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι αρνητικός αριθμός


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


Καθορίζει εάν η αριθμητική τιμή αυτού του μήκους είναι θετικός αριθμός


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


Η τιμή έχει τύπο χωρίς μονάδα, αλλά δεν είναι μηδέν - θετική ή αρνητική
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


Μετατρέπει το μήκος σε αριθμό εικονοστοιχείων, εάν είναι δυνατόν. Εάν το τρέχον
μονάδα είναι σχετική, τότε θα ριχθεί εξαίρεση.


**Returns:**
float - Ο αριθμός των εικονοστοιχείων που αντιπροσωπεύει το τρέχον μήκος.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


Μετατρέπει το μήκος στη δεδομένη μονάδα, εάν είναι δυνατόν. Εάν το τρέχον ή
η δεδομένη μονάδα είναι σχετική, τότε θα ριχθεί εξαίρεση.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μονάδα | int | Η μονάδα στην οποία θα μετατραπεί. |
|

**Returns:**
float - Η τιμή στη δεδομένη μονάδα του τρέχοντος μήκους.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτού του μήκους στον καθορισμένο τύπο μονάδας.
Η αριθμητική τιμή θα μετατραπεί ανάλογα με την αλλαγή τύπου μονάδας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μονάδα | int | Καθορισμένη μονάδα, στην οποία αυτή η παρουσία πρέπει να μετατραπεί πριν από τη σειριοποίηση σε συμβολοσειρά. Πρέπει να είναι έγκυρη. Δεν μπορεί να είναι χωρίς μονάδα. |
|

**Returns:**
java.lang.String - Αναπαράσταση συμβολοσειράς

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτού του μήκους στην αρχική του
μορφή (όπως αποθηκεύεται), χωρίς να μετατρέπει την τιμή του μήκους σε κάποια άλλη
τύπο μονάδας


**Returns:**
java.lang.String - Παράδειγμα συμβολοσειράς

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


Ορίζει εάν αυτή η τιμή είναι ίση με το άλλο καθορισμένο μήκος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Άλλη παρουσία τύπου Length |
|

**Returns:**
boolean - Αληθές εάν είναι ίσο, διαφορετικά ψευδές

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτό το μήκος είναι ίσο με το καθορισμένο αντικείμενο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Άλλη παρουσία τύπου Length, η οποία είναι τοποθετημένη στο System.Object ή σε οποιοδήποτε άλλο αφηρημένο τύπο ή διεπαφή |
|

**Returns:**
boolean - Αληθές εάν είναι ίσο, διαφορετικά ψευδές

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


Πολλαπλασιάζει το δοσμένο Length με τον δοσμένο παράγοντα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - πολλαπλασιαστής |
|
|  | παράγοντας | int | Αυθαίρετος ακέραιος - παράγοντας |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


Ελέγχει την ισότητα των δύο δοσμένων μηκών.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Ο αριστερός τελεστής μήκους. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Ο δεξιός τελεστής μήκους. |
|

**Returns:**
boolean - Αληθές εάν και τα δύο μήκη είναι ίσα, διαφορετικά ψευδές.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


Ελέγχει την ανισότητα των δύο δοσμένων μηκών.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Ο αριστερός τελεστής μήκους. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Ο δεξιός τελεστής μήκους. |
|

**Returns:**
boolean - Αληθές εάν και τα δύο μήκη δεν είναι ίσα, διαφορετικά ψευδές.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Υπολογίζει και επιστρέφει έναν κωδικό κατακερματισμού (hash-code) αυτού του αντικειμένου Length συνδυάζοντας
τους κωδικούς κατακερματισμού της τιμής και του τύπου μονάδας


**Returns:**
int - Ακέραιος αριθμός

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


Επιστρέφει ένα πλήρες αντίγραφο αυτού του αντικειμένου Length


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


Προσπαθεί να αναλύσει το καθορισμένο όνομα μονάδας και να επιστρέψει την αντίστοιχη τιμή ενός
Απαρίθμηση Unit. Επιστρέφει LengthUnit.Unitless εάν δεν βρεθεί κατάλληλο LengthUnit.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | unitName | java.lang.String | String, που αντιπροσωπεύει ένα όνομα μονάδας |
|

**Returns:**
int - Τιμή της αρίθμησης Unit σε κάθε περίπτωση, LengthUnit.Unitless όταν δεν βρεθεί κατάλληλη μονάδα

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


Προσπαθεί να αναλύσει μια καθορισμένη συμβολοσειρά ως τιμή Length, συμπεριλαμβανομένου του
αριθμητικού τιμής και του ονόματος μονάδας


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | εισόδους | java.lang.String | Συμβολοσειρά εισόδου, που πρέπει να αναλυθεί |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Παράμετρος εξόδου, που περιέχει το αποτέλεσμα της ανάλυσης. Εάν η ανάλυση αποτύχει, περιέχει μια προεπιλεγμένη τιμή Length \u2014 ένα μη μονάδας μηδέν. |
|

**Returns:**
boolean - True εάν η ανάλυση είναι επιτυχής, false εάν αποτύχει

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


Αναλύει και επιστρέφει την καθορισμένη συμβολοσειρά ως τιμή Length, συμπεριλαμβανομένου του
αριθμητικού τιμής και του ονόματος μονάδας, ή ρίχνει μια εξαίρεση σε περίπτωση αποτυχίας


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | εισόδους | java.lang.String | Συμβολοσειρά εισόδου, που πρέπει να αναλυθεί |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

