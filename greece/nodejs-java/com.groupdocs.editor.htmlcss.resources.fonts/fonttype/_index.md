---
title: "FontType"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει έναν υποστηριζόμενο τύπο γραμματοσειράς."
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

Αντιπροσωπεύει έναν υποστηριζόμενο τύπο γραμματοσειράς.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontType()](#FontType--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Ειδική τιμή, που σηματοδοτεί ακαθόριστη, άγνωστη ή μη υποστηριζόμενη γραμματοσειρά |
πόρος
|
|  | [getWoff()](#getWoff--) | Αντιπροσωπεύει έναν τύπο γραμματοσειράς WOFF (Web Open Font Format) |
|
|  | [getWoff2()](#getWoff2--) | Αντιπροσωπεύει έναν τύπο γραμματοσειράς WOFF2 (Web Open Font Format version 2) |
|
|  | [getTtf()](#getTtf--) | Αντιπροσωπεύει έναν τύπο γραμματοσειράς TTF (TrueType Font) |
|
|  | [getOtf()](#getOtf--) | Αντιπροσωπεύει έναν τύπο γραμματοσειράς OTF (OpenType Font) |
|
|  | [getTtc()](#getTtc--) | Αντιπροσωπεύει μια γραμματοσειρά TrueType Collection (TTC) |
|
|  | [getEot()](#getEot--) | Αντιπροσωπεύει έναν τύπο γραμματοσειράς EOT (Embedded OpenType) |
|
|  | [getCssName()](#getCssName--) | Επιστρέφει όνομα συμβατό με CSS αυτού του τύπου γραμματοσειράς, που χρησιμοποιείται στο |
|
|  | [getFormalName()](#getFormalName--) | Επιστρέφει ένα επίσημο όνομα αυτού του τύπου γραμματοσειράς |
|
|  | [getFileExtension()](#getFileExtension--) | Επέκταση ονόματος αρχείου (χωρίς το χαρακτήρα τελείας) για αυτόν τον τύπο γραμματοσειράς |
|
|  | [getFontFormat()](#getFontFormat--) | Μορφή γραμματοσειράς για μορφή @font-face |
|
|  | [getMimeCode()](#getMimeCode--) | Κωδικός MIME ενός συγκεκριμένου τύπου γραμματοσειράς |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Επιστρέφει τιμή FontType, η οποία είναι ισοδύναμη με το καθορισμένο CSS-compatible |
όνομα του τύπου γραμματοσειράς
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Επιστρέφει τιμή FontType, η οποία είναι ισοδύναμη με την επέκταση ονόματος αρχείου, η οποία |
εξάγεται από το καθορισμένο όνομα αρχείου
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Επιστρέφει τιμή FontType, η οποία είναι ισοδύναμη με τον καθορισμένο MIME-code |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Επιστρέφει τον πρώτο τύπο γραμματοσειράς από το καθορισμένο σύνολο, ο οποίος δεν είναι "Undefined" |
τιμή, ή τύπο γραμματοσειράς "Undefined" διαφορετικά (όταν όλα τα στοιχεία είναι
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Καθορίζει εάν αυτή η περίπτωση είναι ίση με το καθορισμένο "FontType" |
αντίγραφο
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο, |
η οποία προφανώς είναι άλλη περίπτωση "FontType"
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Ελέγχει εάν δύο τιμές "FontType" είναι ίσες |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Ελέγχει εάν δύο τιμές "FontType" δεν είναι ίσες |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό hash, ο οποίος είναι ένας σταθερός αριθμός για αυτή τη συγκεκριμένη τιμή |
τύπος
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


Ειδική τιμή, που σηματοδοτεί ακαθόριστη, άγνωστη ή μη υποστηριζόμενη γραμματοσειρά
πόρος


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


Αντιπροσωπεύει έναν τύπο γραμματοσειράς WOFF (Web Open Font Format)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


Αντιπροσωπεύει έναν τύπο γραμματοσειράς WOFF2 (Web Open Font Format version 2)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


Αντιπροσωπεύει έναν τύπο γραμματοσειράς TTF (TrueType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


Αντιπροσωπεύει έναν τύπο γραμματοσειράς OTF (OpenType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


Αντιπροσωπεύει μια γραμματοσειρά TrueType Collection (TTC)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


Αντιπροσωπεύει έναν τύπο γραμματοσειράς EOT (Embedded OpenType)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Επιστρέφει όνομα συμβατό με CSS αυτού του τύπου γραμματοσειράς, που χρησιμοποιείται στο


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Επιστρέφει ένα επίσημο όνομα αυτού του τύπου γραμματοσειράς


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Επέκταση ονόματος αρχείου (χωρίς το χαρακτήρα τελείας) για αυτόν τον τύπο γραμματοσειράς


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Μορφή γραμματοσειράς για μορφή @font-face


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Κωδικός MIME ενός συγκεκριμένου τύπου γραμματοσειράς


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


Επιστρέφει τιμή FontType, η οποία είναι ισοδύναμη με το καθορισμένο CSS-compatible
όνομα του τύπου γραμματοσειράς


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | name | java.lang.String | Όνομα CSS-compatible του τύπου γραμματοσειράς |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Επιστρέφει τιμή FontType, η οποία είναι ισοδύναμη με την επέκταση ονόματος αρχείου, η οποία
εξάγεται από το καθορισμένο όνομα αρχείου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα αρχείου | java.lang.String | Όνομα αρχείου με επέκταση, μπορεί να είναι πλήρες όνομα |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


Επιστρέφει τιμή FontType, η οποία είναι ισοδύναμη με τον καθορισμένο MIME-code


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | mimeCode | java.lang.String | MIME-code |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


Επιστρέφει τον πρώτο τύπο γραμματοσειράς από το καθορισμένο σύνολο, ο οποίος δεν είναι "Undefined"
τιμή, ή τύπο γραμματοσειράς "Undefined" διαφορετικά (όταν όλα τα στοιχεία είναι
"Undefined")


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Μία ή περισσότερες τιμές FontType, το NULL ή κενή συλλογή δεν επιτρέπεται |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


Καθορίζει εάν αυτή η περίπτωση είναι ίση με το καθορισμένο "FontType"
αντίγραφο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Άλλη περίπτωση FontType για έλεγχο με αυτήν |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο,
η οποία προφανώς είναι άλλη περίπτωση "FontType"


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Άλλη περίπτωση προφανώς του struct FontType, που είχε μετατραπεί σε System.Object |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


Ελέγχει εάν δύο τιμές "FontType" είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Πρώτο FontType για έλεγχο |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Δεύτερο FontType για έλεγχο |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


Ελέγχει εάν δύο τιμές "FontType" δεν είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Πρώτο FontType για έλεγχο |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Δεύτερο FontType για έλεγχο |
|

**Returns:**
boolean - True εάν είναι ίσα, false εάν είναι διαφορετικά

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό hash, ο οποίος είναι ένας σταθερός αριθμός για αυτή τη συγκεκριμένη τιμή
τύπος


**Returns:**
int - 4-μπάιτ υπογεγραμμένος ακέραιος, 0 για τιμή Undefined

