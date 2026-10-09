---
title: "Αναλογία"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αναπαριστά έναν τύπο CSS αναλογίας που χρησιμοποιείται για την περιγραφή αναλογιών διαστάσεων σε ερωτήματα μέσων και για ραστερ εικόνες, δηλώνοντας την αναλογία μεταξύ δύο αδιάστατων τιμών που ονομάζονται αριθμητής και παρονομαστής."
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

Αναπαριστά έναν τύπο CSS "ratio", που χρησιμοποιείται για την περιγραφή της αναλογίας
αναλογιών σε ερωτήματα μέσων και για ραστερ εικόνες, δηλώνοντας την αναλογία
μεταξύ δύο αδιάστατων τιμών που ονομάζονται "numerator" και "denominator". Αμετάβλητο
struct.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Single](#Single) | Μοναδική προεπιλεγμένη αναλογία 1/1 |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | Επιστρέφει έναν αριθμητή αυτής της αναλογίας |
|
|  | [getDenominator()](#getDenominator--) | Επιστρέφει έναν παρονομαστή αυτής της αναλογίας |
|
|  | [calculate()](#calculate--) | Υπολογίζει και επιστρέφει αυτή την αναλογία ως έναν μοναδικό αριθμό κινητής υποδιαστολής |
|
|  | [getInverseRatio()](#getInverseRatio--) | Δημιουργεί και επιστρέφει μια αντίστροφη (αντίστροφη) αναλογία για αυτή την αναλογία |
|
|  | [serializeDefault()](#serializeDefault--) | Σειριοποιεί αυτή την αναλογία σε συμβολοσειρά και την επιστρέφει |
|
|  | [toString()](#toString--) | Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτής της αναλογίας· το ίδιο με |
"SerializeDefault()"
|
|  | [isDefault()](#isDefault--) | Καθορίζει αν αυτή η αναλογία έχει προεπιλεγμένη τιμή ή είναι "1/1" (Μοναδική) |
|
|  | [deepClone()](#deepClone--) | Επιστρέφει ένα πλήρες αντίγραφο αυτού του λόγου |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το καθορισμένο αντικείμενο "Ratio" |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο, |
το οποίο προφανώς είναι ένα άλλο αντικείμενο "Ratio"
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Συγκρίνει δύο λόγους και επιστρέφει μια boolean τιμή που υποδεικνύει εάν οι δύο ταιριάζουν. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Συγκρίνει δύο λόγους και επιστρέφει μια boolean τιμή που υποδεικνύει εάν οι δύο δεν |
ταιριάζουν.
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το αντικείμενο, ο οποίος δεν μπορεί να αλλάξει κατά τη διάρκεια του |
διάρκειας ζωής
|
|  | [create(int numerator, int denominator)](#create-int-int-) | Δημιουργεί και επιστρέφει ένα αντικείμενο Ratio από τον καθορισμένο αριθμητή και |
παρονομαστή
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


Μοναδική προεπιλεγμένη αναλογία 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Επιστρέφει έναν αριθμητή αυτής της αναλογίας


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Επιστρέφει έναν παρονομαστή αυτής της αναλογίας


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


Υπολογίζει και επιστρέφει αυτή την αναλογία ως έναν μοναδικό αριθμό κινητής υποδιαστολής


**Returns:**
double - Αριθμός κινητής υποδιαστολής με διπλή ακρίβεια

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Δημιουργεί και επιστρέφει μια αντίστροφη (αντίστροφη) αναλογία για αυτή την αναλογία


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Σειριοποιεί αυτή την αναλογία σε συμβολοσειρά και την επιστρέφει


**Returns:**
java.lang.String - Συμβολοσειρά σε μορφή "numerator/denominator"

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτής της αναλογίας· το ίδιο με
"SerializeDefault()"


**Returns:**
java.lang.String - Συμβολοσειρά σε μορφή "numerator/denominator"

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Καθορίζει αν αυτή η αναλογία έχει προεπιλεγμένη τιμή ή είναι "1/1" (Μοναδική)


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Επιστρέφει ένα πλήρες αντίγραφο αυτού του λόγου


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το καθορισμένο αντικείμενο "Ratio"


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Άλλο αντικείμενο Ratio για έλεγχο ισότητας με αυτό |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο,
το οποίο προφανώς είναι ένα άλλο αντικείμενο "Ratio"


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | άλλο | java.lang.Object | Άλλο αντικείμενο System.Object, το οποίο προφανώς είναι τύπου Ratio, για έλεγχο ισότητας με αυτό |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


Συγκρίνει δύο λόγους και επιστρέφει μια boolean τιμή που υποδεικνύει εάν οι δύο ταιριάζουν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Ο πρώτος λόγος που θα χρησιμοποιηθεί. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Ο δεύτερος λόγος που θα χρησιμοποιηθεί. |
|

**Returns:**
boolean - Αληθές εάν και οι δύο λόγοι είναι ίσοι, διαφορετικά ψευδές.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


Συγκρίνει δύο λόγους και επιστρέφει μια boolean τιμή που υποδεικνύει εάν οι δύο δεν
ταιριάζουν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Ο πρώτος λόγος που θα χρησιμοποιηθεί. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Ο δεύτερος λόγος που θα χρησιμοποιηθεί. |
|

**Returns:**
boolean - Αληθές εάν και οι δύο λόγοι δεν είναι ίσοι, διαφορετικά ψευδές.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το αντικείμενο, ο οποίος δεν μπορεί να αλλάξει κατά τη διάρκεια του
διάρκειας ζωής


**Returns:**
int - Υπογεγραμμένος ακέραιος 4-μπάιτ, ο οποίος είναι αμετάβλητος για αυτό το αντικείμενο

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Δημιουργεί και επιστρέφει ένα αντικείμενο Ratio από τον καθορισμένο αριθμητή και
παρονομαστή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αριθμητής | int | Αριθμητής για τον λόγο. Θα πρέπει να είναι αυστηρά θετικός ακέραιος αριθμός. |
|
|  | παρονομαστή | int | Παρονομαστής για τον λόγο. Θα πρέπει να είναι αυστηρά θετικός ακέραιος αριθμός. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

