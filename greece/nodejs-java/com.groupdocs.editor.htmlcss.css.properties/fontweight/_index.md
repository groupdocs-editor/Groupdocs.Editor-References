---
title: "FontWeight"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Η ιδιότητα Font-weight ορίζει το βάρος ή την ένταση της γραμματοσειράς."
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

Η ιδιότητα Font-weight ορίζει το βάρος (ή την ένταση) της γραμματοσειράς. Τα διαθέσιμα βάρη εξαρτώνται από την τρέχουσα ρυθμισμένη font-family.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Lighter](#Lighter) | Ένα σχετικό βάρος γραμματοσειράς ελαφρύτερο από το γονικό στοιχείο |
|
|  | [Bolder](#Bolder) | Ένα σχετικό βάρος γραμματοσειράς βαρύτερο από το γονικό στοιχείο |
|
|  | [Normal](#Normal) | Κανονικό βάρος γραμματοσειράς. |
|
|  | [Bold](#Bold) | Έντονο βάρος γραμματοσειράς. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isInitial()](#isInitial--) | Δείχνει εάν αυτό το μέγεθος γραμματοσειράς έχει αρχική τιμή (Medium) |
|
|  | [getNumber()](#getNumber--) | Επιστρέφει έναν αριθμό - ακέραιη τιμή μεταξύ 1 και 1000, συμπεριλαμβανομένων, που περιγράφει το πάχος της γραμματοσειράς, ή ρίχνει εξαίρεση, εάν το τρέχον πάχος δεν είναι απόλυτο, αλλά σχετικό |
|
|  | [isAbsolute()](#isAbsolute--) | Δείχνει εάν αυτή η παρουσία font-weight αποθηκεύει μια απόλυτη τιμή του βάρους (πάχος) της γραμματοσειράς, ως ακέραιο αριθμό |
|
|  | [isRelative()](#isRelative--) | Δείχνει εάν αυτή η παρουσία font-weight αποθηκεύει μια σχετική τιμή του βάρους (πάχος) της γραμματοσειράς - σε σύγκριση με το πάχος του γονικού στοιχείου |
|
|  | [getValue()](#getValue--) | Επιστρέφει μια τιμή αυτής της font-weight ως συμβολοσειρά |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Καθορίζει εάν οι καθορισμένες εμφανίσεις FontWeight είναι ίσες |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία FontWeight είναι ίση με την καθορισμένη μη μετατρεπόμενη |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Ελέγχει εάν δύο "FontWeight" τιμές είναι ίσες |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Ελέγχει εάν δύο "FontWeight" τιμές δεν είναι ίσες |
|
|  | [fromNumber(int number)](#fromNumber-int-) | Δημιουργεί μια font-weight από τον καθορισμένο αριθμό |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Προσπαθεί να αναλύσει μια καθορισμένη συμβολοσειρά και να επιστρέψει μια έγκυρη παρουσία FontWeight σε περίπτωση επιτυχίας |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


Ένα σχετικό βάρος γραμματοσειράς ελαφρύτερο από το γονικό στοιχείο


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


Ένα σχετικό βάρος γραμματοσειράς βαρύτερο από το γονικό στοιχείο


### Normal {#Normal}
```
public static final FontWeight Normal
```


Κανονικό βάρος γραμματοσειράς. Ίδιο με το 400.


### Bold {#Bold}
```
public static final FontWeight Bold
```


Έντονο βάρος γραμματοσειράς. Ίδιο με το 700.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Δείχνει εάν αυτό το μέγεθος γραμματοσειράς έχει αρχική τιμή (Medium)


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Επιστρέφει έναν αριθμό - ακέραιη τιμή μεταξύ 1 και 1000, συμπεριλαμβανομένων, που περιγράφει το πάχος της γραμματοσειράς, ή ρίχνει εξαίρεση, εάν το τρέχον πάχος δεν είναι απόλυτο, αλλά σχετικό


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Δείχνει εάν αυτή η παρουσία font-weight αποθηκεύει μια απόλυτη τιμή του βάρους (πάχος) της γραμματοσειράς, ως ακέραιο αριθμό


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Δείχνει εάν αυτή η παρουσία font-weight αποθηκεύει μια σχετική τιμή του βάρους (πάχος) της γραμματοσειράς - σε σύγκριση με το πάχος του γονικού στοιχείου


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Επιστρέφει μια τιμή αυτής της font-weight ως συμβολοσειρά


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Καθορίζει εάν οι καθορισμένες εμφανίσεις FontWeight είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Άλλη παρουσία FontWeight για έλεγχο της ισότητας |
|

**Returns:**
boolean - true εάν είναι ίσες, false εάν είναι διαφορετικές

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτή η παρουσία FontWeight είναι ίση με την καθορισμένη μη μετατρεπόμενη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Άλλη μη μετατρεπόμενη παρουσία FontWeight, μπορεί να είναι null |
|

**Returns:**
boolean - true εάν είναι ίσα, false εάν δεν είναι ίσα, null ή άλλου τύπου

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία


**Returns:**
int - Hash-code ως υπογεγραμμένος ακέραιος

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


Ελέγχει εάν δύο "FontWeight" τιμές είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Πρώτη τιμή για έλεγχο |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Δεύτερη τιμή για έλεγχο |
|

**Returns:**
boolean - true εάν είναι ίσα, false διαφορετικά

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


Ελέγχει εάν δύο "FontWeight" τιμές δεν είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Πρώτη τιμή για έλεγχο |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Δεύτερη τιμή για έλεγχο |
|

**Returns:**
boolean - false εάν είναι ίσα, true διαφορετικά

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Δημιουργεί μια font-weight από τον καθορισμένο αριθμό


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | number | int | Απέρριπτος ακέραιος, πρέπει να βρίσκεται στο εύρος [1..1000] |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Προσπαθεί να αναλύσει μια καθορισμένη συμβολοσειρά και να επιστρέψει μια έγκυρη παρουσία FontWeight σε περίπτωση επιτυχίας


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | εισόδους | java.lang.String | Συμβολοσειρά εισόδου για ανάλυση |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Έγκυρη τιμή FontWeight σε περίπτωση επιτυχίας ή #Normal.Normal σε περίπτωση αποτυχίας |
|

**Returns:**
boolean - Επιτυχία (true) ή αποτυχία (false) της ανάλυσης

