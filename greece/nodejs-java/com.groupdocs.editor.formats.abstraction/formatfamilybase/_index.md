---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει τη βασική κλάση για τις οικογένειες μορφών που παρέχει κοινή λειτουργικότητα για τα στιγμιότυπα οικογένειας μορφών."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

Αντιπροσωπεύει τη βασική κλάση για οικογένειες μορφότυπων, παρέχοντας κοινή λειτουργικότητα για τις περιπτώσεις οικογένειας μορφότυπου.

<br />

*** ** * ** ***

Αυτή η κλάση είναι αφηρημένη και πρέπει να κληρονομηθεί από μια παράγωγη κλάση που καθορίζει τις πραγματικές λεπτομέρειες της οικογένειας μορφής.

<br />


## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getId()](#getId--) | Λαμβάνει το μοναδικό αναγνωριστικό για την οικογένεια μορφής. |
|
|  | [getName()](#getName--) | Λαμβάνει το όνομα της οικογένειας μορφής. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την καθορισμένη παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [toString()](#toString--) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | Ανακτά όλες τις παρουσίες του καθορισμένου τύπου |
T
που προέρχονται από το [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την καθορισμένη παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου |
T
που έχει το καθορισμένο αναγνωριστικό.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου |
T
που έχει το καθορισμένο όνομα.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Καθορίζει εάν δύο παρουσίες [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) είναι ίσες. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Καθορίζει εάν δύο παρουσίες [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) δεν είναι ίσες. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Καθορίζει εάν μια παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) είναι ίση με ένα καθορισμένο όνομα συμβολοσειράς. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Καθορίζει εάν μια παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) δεν είναι ίση με ένα καθορισμένο όνομα συμβολοσειράς. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Μετατρέπει μια παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) σε ακέραιο έμμεσα. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Μετατρέπει μια παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) σε συμβολοσειρά έμμεσα. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει ένα όνομα οικογένειας μορφής σε αντικείμενο [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [fromId(int id)](#fromId-int-) | Μετατρέπει έναν ακέραιο που αντιπροσωπεύει ένα αναγνωριστικό οικογένειας μορφής σε αντικείμενο [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
### getId() {#getId--}
```
public final int getId()
```


Λαμβάνει το μοναδικό αναγνωριστικό για την οικογένεια μορφής.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Λαμβάνει το όνομα της οικογένειας μορφής.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με την καθορισμένη παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Η παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) για σύγκριση με την τρέχουσα παρουσία. |
|

**Returns:**
boolean -  true  εάν η καθορισμένη [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) είναι ίση με την τρέχουσα παρουσία· διαφορετικά,  false .

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο.


**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο, η οποία είναι η τιμή της ιδιότητας  Name .

<br />

*** ** * ** ***

Αυτή η μέθοδος παρακάμπτει το  object.ToString  για να επιστρέψει την ιδιότητα  Name  του αντικειμένου.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


Ανακτά όλες τις παρουσίες του καθορισμένου τύπου
T
που προέρχονται από το [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Μια επαναλήψιμη συλλογή παρουσιών του καθορισμένου τύπου  T .


T
: Ο τύπος της οικογένειας μορφής.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με την καθορισμένη παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Η παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) για σύγκριση με την τρέχουσα παρουσία. |
|

**Returns:**
boolean -  true  εάν η καθορισμένη [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) είναι ίση με την τρέχουσα παρουσία· διαφορετικά,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για το τρέχον αντικείμενο.


**Returns:**
int - Ένας κώδικας κατακερματισμού για το τρέχον αντικείμενο, κατάλληλος για χρήση σε αλγόριθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού.

<br />

*** ** * ** ***

Αυτή η μέθοδος παρακάμπτει το  object.GetHashCode . Ο κώδικας κατακερματισμού υπολογίζεται χρησιμοποιώντας τις ιδιότητες  Id  και  Name  του αντικειμένου. Το πλαίσιο  unchecked  επιτρέπει υπερχείλιση, η οποία είναι αποδεκτή σε ένα πλαίσιο υπολογισμού κώδικα κατακερματισμού.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου
T
που έχει το καθορισμένο αναγνωριστικό.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | τιμή | int | Το αναγνωριστικό της οικογένειας μορφής. |


T
: Ο τύπος της οικογένειας μορφής.
|

**Returns:**
T - Μία παρουσία του καθορισμένου τύπου  T  με το καθορισμένο αναγνωριστικό.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


Ανακτά ένα στιγμιότυπο του καθορισμένου τύπου
T
που έχει το καθορισμένο όνομα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | name | java.lang.String | Το όνομα της οικογένειας μορφής. |


T
: Ο τύπος της οικογένειας μορφής.
|

**Returns:**
T - Μία παρουσία του καθορισμένου τύπου  T  με το καθορισμένο όνομα.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Καθορίζει εάν δύο παρουσίες [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) είναι ίσες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Η πρώτη παρουσία του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) για σύγκριση. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Η δεύτερη παρουσία του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) για σύγκριση. |
|

**Returns:**
boolean - true εάν οι δύο παρουσίες του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) είναι ίσες; διαφορετικά, false.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Καθορίζει εάν δύο παρουσίες [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) δεν είναι ίσες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Η πρώτη παρουσία του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) για σύγκριση. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Η δεύτερη παρουσία του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) για σύγκριση. |
|

**Returns:**
boolean - true εάν οι δύο παρουσίες του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) δεν είναι ίσες; διαφορετικά, false.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


Καθορίζει εάν μια παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) είναι ίση με ένα καθορισμένο όνομα συμβολοσειράς.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Η παρουσία του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) για σύγκριση. |
|
|  | name | java.lang.String | Το όνομα συμβολοσειράς για σύγκριση με την παρουσία του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - true εάν το όνομα της παρουσίας του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) είναι ίσο με το καθορισμένο όνομα συμβολοσειράς; διαφορετικά, false.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


Καθορίζει εάν μια παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) δεν είναι ίση με ένα καθορισμένο όνομα συμβολοσειράς.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Η παρουσία του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) για σύγκριση. |
|
|  | name | java.lang.String | Το όνομα συμβολοσειράς για σύγκριση με την παρουσία του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - true εάν το όνομα της παρουσίας του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) δεν είναι ίσο με το καθορισμένο όνομα συμβολοσειράς; διαφορετικά, false.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


Μετατρέπει μια παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) σε ακέραιο έμμεσα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Η παρουσία του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) για μετατροπή. |
|

**Returns:**
int - Το μοναδικό αναγνωριστικό της παρουσίας του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


Μετατρέπει μια παρουσία [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) σε συμβολοσειρά έμμεσα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Η παρουσία του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) για μετατροπή. |
|

**Returns:**
java.lang.String - Το όνομα της παρουσίας του [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


Μετατρέπει μια συμβολοσειρά που αντιπροσωπεύει ένα όνομα οικογένειας μορφής σε αντικείμενο [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | οικογένεια | java.lang.String | Το όνομα της οικογένειας μορφής για μετατροπή. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


Μετατρέπει έναν ακέραιο που αντιπροσωπεύει ένα αναγνωριστικό οικογένειας μορφής σε αντικείμενο [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | id | int | Το ID της οικογένειας μορφής για μετατροπή. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

