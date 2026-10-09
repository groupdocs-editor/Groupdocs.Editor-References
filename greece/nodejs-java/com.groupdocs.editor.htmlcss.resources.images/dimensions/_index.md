---
title: "Διαστάσεις"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει τις γραμμικές διαστάσεις πλάτος και ύψος μιας ραστερικής ορθογώνιας εικόνας σε αυθαίρετη μονάδα."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

Αντιπροσωπεύει τις γραμμικές διαστάσεις (πλάτος και ύψος) μιας ραστερικής ορθογώνιας
εικόνα σε αυθαίρετη μονάδα. Αμετάβλητη δομή.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | Δημιουργεί μια νέα παρουσία από το καθορισμένο πλάτος και ύψος |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWidth()](#getWidth--) | Επιστρέφει το πλάτος της εικόνας |
|
|  | [getHeight()](#getHeight--) | Επιστρέφει το ύψος της εικόνας |
|
|  | [isSquare()](#isSquare--) | Καθορίζει αν οι καθορισμένες 'Dimensions' αντιπροσωπεύουν τετράγωνο, δηλαδή. |
|
|  | [getArea()](#getArea--) | Επιστρέφει μια περιοχή (Πλάτος x Ύψος) |
|
|  | [isEmpty()](#isEmpty--) | Καθορίζει αν αυτή η "Dimensions" παρουσία είναι κενή και προεπιλεγμένη, δηλαδή. |
|
|  | [getAspectRatio()](#getAspectRatio--) | Αναλογία διαστάσεων ως πλάτος/ύψος |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | Δημιουργεί και επιστρέφει μια νέα "Dimensions" παρουσία, η οποία είναι αναλογικά |
αλλαγή μεγέθους από την τρέχουσα, βάσει του καθορισμένου πλάτους
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | Δημιουργεί και επιστρέφει μια νέα "Dimensions" παρουσία, η οποία είναι αναλογικά |
αλλαγή μεγέθους από την τρέχουσα, βάσει του καθορισμένου ύψους
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Καθορίζει αν αυτή η παρουσία είναι ίση με τις καθορισμένες "Dimensions" |
αντίγραφο
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο, |
που προφανώς είναι μια άλλη "Dimensions" παρουσία
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το αντικείμενο, ο οποίος δεν μπορεί να αλλάξει κατά τη διάρκεια του |
διάρκειας ζωής
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Ελέγχει αν δύο τιμές "Dimensions" είναι ίσες, δηλαδή. |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | Ελέγχει εάν δύο τιμές "Dimensions" δεν είναι ίσες, δηλαδή. |
|
|  | [toString()](#toString--) | Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτού του "Dimensions" |
|
|  | [deepClone()](#deepClone--) | Επιστρέφει ένα πλήρες αντίγραφο αυτού του αντικειμένου |
|
|  | [getEmpty()](#getEmpty--) | Επιστρέφει μια κενή παρουσία Dimensions |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


Δημιουργεί μια νέα παρουσία από το καθορισμένο πλάτος και ύψος


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | πλάτος | int | Πλάτος εικόνας |
|
|  | ύψος | int | Ύψος εικόνας |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Επιστρέφει το πλάτος της εικόνας


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Επιστρέφει το ύψος της εικόνας


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


Καθορίζει εάν το συγκεκριμένο 'Dimensions' αντιπροσωπεύει τετράγωνο, δηλαδή αν
το πλάτος είναι ίσο με το ύψος


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


Επιστρέφει μια περιοχή (Πλάτος x Ύψος)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Καθορίζει αν αυτή η "Dimensions" παρουσία είναι κενή και προεπιλεγμένη, δηλαδή.
δεν αποθηκεύει σωστά το πλάτος και το ύψος


**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Αναλογία διαστάσεων ως πλάτος/ύψος


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


Δημιουργεί και επιστρέφει μια νέα "Dimensions" παρουσία, η οποία είναι αναλογικά
αλλαγή μεγέθους από την τρέχουσα, βάσει του καθορισμένου πλάτους


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | targetWidth | int | Νέο πλάτος στόχου, που θα υπάρχει στην τελική Dimension |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


Δημιουργεί και επιστρέφει μια νέα "Dimensions" παρουσία, η οποία είναι αναλογικά
αλλαγή μεγέθους από την τρέχουσα, βάσει του καθορισμένου ύψους


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | targetHeight | int | Νέο ύψος στόχου, που θα υπάρχει στην τελική Dimension |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


Καθορίζει αν αυτή η παρουσία είναι ίση με τις καθορισμένες "Dimensions"
αντίγραφο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Άλλη παρουσία "Dimensions" για έλεγχο ισότητας |
|

**Returns:**
boolean - True εάν είναι ίσες, false εάν δεν είναι ίσες

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο,
που προφανώς είναι μια άλλη "Dimensions" παρουσία


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Άλλο αντικείμενο, που προφανώς είναι τύπου "Dimensions", το οποίο πρέπει να ελεγχθεί για ισότητα με αυτό |
|

**Returns:**
boolean - True εάν είναι ίσες, false εάν δεν είναι ίσες

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το αντικείμενο, ο οποίος δεν μπορεί να αλλάξει κατά τη διάρκεια του
διάρκειας ζωής


**Returns:**
int - Αμετάβλητος (για αυτήν την παρουσία) hash-code ως υπογεγραμμένος 4-μπάιτ ακέραιος

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


Ελέγχει εάν δύο τιμές "Dimensions" είναι ίσες, δηλαδή έχουν ίσες
πλάτος και ύψος, ή και τα δύο είναι κενά


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Πρώτη παρουσία για έλεγχο |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Δεύτερη παρουσία για έλεγχο |
|

**Returns:**
boolean - True εάν είναι ίσες, false εάν δεν είναι ίσες

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


Ελέγχει εάν δύο τιμές "Dimensions" δεν είναι ίσες, δηλαδή οι
σχετικό πλάτος και/ή ύψος είναι διαφορετικά


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Πρώτη παρουσία για έλεγχο |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | Δεύτερη παρουσία για έλεγχο |
|

**Returns:**
boolean - True εάν είναι διαφορετικά, false εάν είναι ίσα

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτού του "Dimensions"

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - αντικείμενο String, που περιέχει πλάτος και ύψος σε μορφή W:(width)×H:(height)

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


Επιστρέφει ένα πλήρες αντίγραφο αυτού του αντικειμένου


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


Επιστρέφει μια κενή παρουσία Dimensions


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
