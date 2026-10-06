---
title: "Αναλογία"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει έναν τύπο δεδομένων CSS ratio που χρησιμοποιείται για την περιγραφή αναλογιών διαστάσεων σε ερωτήματα μέσων και για ραστερ εικόνες, δηλώνοντας την αναλογία μεταξύ δύο αδιάστατων τιμών που ονομάζονται αριθμητής και παρονομαστής."
type: docs
weight: 14
url: /el/java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

Αντιπροσωπεύει έναν τύπο δεδομένων CSS "ratio", ο οποίος χρησιμοποιείται για την περιγραφή της αναλογίας
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
|  | [calculate()](#calculate--) | Υπολογίζει και επιστρέφει αυτήν την αναλογία ως έναν μοναδικό αριθμό κινητής υποδιαστολής |
|
|  | [getInverseRatio()](#getInverseRatio--) | Δημιουργεί και επιστρέφει μια αντίστροφη (αντίστροφη) αναλογία για αυτήν την αναλογία |
|
|  | [serializeDefault()](#serializeDefault--) | Σειριοποιεί αυτήν την αναλογία σε συμβολοσειρά και την επιστρέφει |
|
|  | [toString()](#toString--) | Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτής της αναλογίας· ίδιο με |
"SerializeDefault()"
|
|  | [isDefault()](#isDefault--) | Καθορίζει εάν αυτή η αναλογία έχει προεπιλεγμένη τιμή ή είναι "1/1" (Μοναδική) |
|
|  | [deepClone()](#deepClone--) | Επιστρέφει ένα πλήρες αντίγραφο αυτής της αναλογίας |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το καθορισμένο "Ratio" αντικείμενο |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Καθορίζει αν αυτή η περίπτωση είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο, |
που προφανώς είναι ένα άλλο "Ratio" αντικείμενο
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Συγκρίνει δύο αναλογίες και επιστρέφει μια boolean τιμή που υποδεικνύει αν οι δύο ταιριάζουν. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Συγκρίνει δύο αναλογίες και επιστρέφει μια boolean τιμή που υποδεικνύει αν οι δύο δεν |
ταιριάζουν.
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν hashcode για αυτήν την παρουσία, ο οποίος δεν μπορεί να αλλάξει κατά τη διάρκεια του |
διάρκειας
|
|  | [create(int numerator, int denominator)](#create-int-int-) | Δημιουργεί και επιστρέφει ένα αντικείμενο Ratio από το καθορισμένο αριθμητή και |
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


Υπολογίζει και επιστρέφει αυτήν την αναλογία ως έναν μοναδικό αριθμό κινητής υποδιαστολής


**Returns:**
double - Αριθμός κινητής υποδιαστολής με διπλή ακρίβεια

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Δημιουργεί και επιστρέφει μια αντίστροφη (αντίστροφη) αναλογία για αυτήν την αναλογία


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Σειριοποιεί αυτήν την αναλογία σε συμβολοσειρά και την επιστρέφει


**Returns:**
java.lang.String - Συμβολοσειρά σε μορφή "numerator/denominator"

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτής της αναλογίας· ίδιο με
"SerializeDefault()"


**Returns:**
java.lang.String - Συμβολοσειρά σε μορφή "numerator/denominator"

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Καθορίζει εάν αυτή η αναλογία έχει προεπιλεγμένη τιμή ή είναι "1/1" (Μοναδική)


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Επιστρέφει ένα πλήρες αντίγραφο αυτής της αναλογίας


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το καθορισμένο "Ratio" αντικείμενο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Άλλη παρουσία Ratio για έλεγχο ισότητας με αυτήν |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Καθορίζει αν αυτή η περίπτωση είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο,
που προφανώς είναι ένα άλλο "Ratio" αντικείμενο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | άλλο | java.lang.Object | Άλλη παρουσία System.Object, η οποία προφανώς είναι τύπου Ratio, για έλεγχο ισότητας με αυτήν |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


Συγκρίνει δύο αναλογίες και επιστρέφει μια boolean τιμή που υποδεικνύει αν οι δύο ταιριάζουν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Η πρώτη αναλογία προς χρήση. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Η δεύτερη αναλογία προς χρήση. |
|

**Returns:**
boolean - Αληθές αν και οι δύο αναλογίες είναι ίσες, διαφορετικά ψευδές.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


Συγκρίνει δύο αναλογίες και επιστρέφει μια boolean τιμή που υποδεικνύει αν οι δύο δεν
ταιριάζουν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Η πρώτη αναλογία προς χρήση. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Η δεύτερη αναλογία προς χρήση. |
|

**Returns:**
boolean - Αληθές αν και οι δύο αναλογίες δεν είναι ίσες, διαφορετικά ψευδές.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν hashcode για αυτήν την παρουσία, ο οποίος δεν μπορεί να αλλάξει κατά τη διάρκεια του
διάρκειας


**Returns:**
int - Υπογεγραμμένος ακέραιος 4-μπάιτ, ο οποίος είναι αμετάβλητος για αυτήν την παρουσία

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Δημιουργεί και επιστρέφει ένα αντικείμενο Ratio από το καθορισμένο αριθμητή και
παρονομαστή


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | αριθμητής | int | Αριθμητής για την αναλογία. Θα πρέπει να είναι αυστηρά θετικός ακέραιος αριθμός. |
|
|  | παρονομαστή | int | Παρονομαστής για την αναλογία. Θα πρέπει να είναι αυστηρά θετικός ακέραιος αριθμός. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

