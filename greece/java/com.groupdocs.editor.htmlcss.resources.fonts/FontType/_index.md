---
title: "FontType"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει έναν υποστηριζόμενο τύπο γραμματοσειράς."
type: docs
weight: 12
url: /el/java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
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
|  | [getUndefined()](#getUndefined--) | Ειδική τιμή, που σηματοδοτεί μη ορισμένη, άγνωστη ή μη υποστηριζόμενη γραμματοσειρά |
πόρος
|
|  | [getWoff()](#getWoff--) | Αναπαριστά τύπο γραμματοσειράς WOFF (Web Open Font Format) |
|
|  | [getWoff2()](#getWoff2--) | Αναπαριστά τύπο γραμματοσειράς WOFF2 (Web Open Font Format έκδοση 2) |
|
|  | [getTtf()](#getTtf--) | Αναπαριστά τύπο γραμματοσειράς TTF (TrueType Font) |
|
|  | [getOtf()](#getOtf--) | Αναπαριστά τύπο γραμματοσειράς OTF (OpenType Font) |
|
|  | [getTtc()](#getTtc--) | Αναπαριστά γραμματοσειρά TrueType Collection (TTC) |
|
|  | [getEot()](#getEot--) | Αναπαριστά τύπο γραμματοσειράς EOT (Embedded OpenType) |
|
|  | [getCssName()](#getCssName--) | Επιστρέφει το CSS-συμβατό όνομα αυτού του τύπου γραμματοσειράς, το οποίο χρησιμοποιείται στο |
|
|  | [getFormalName()](#getFormalName--) | Επιστρέφει ένα επίσημο όνομα αυτού του τύπου γραμματοσειράς |
|
|  | [getFileExtension()](#getFileExtension--) | Επέκταση ονόματος αρχείου (χωρίς χαρακτήρα τελείας) για αυτόν τον τύπο γραμματοσειράς |
|
|  | [getFontFormat()](#getFontFormat--) | Μορφή γραμματοσειράς για τη μορφή @font-face |
|
|  | [getMimeCode()](#getMimeCode--) | Κωδικός MIME ενός συγκεκριμένου τύπου γραμματοσειράς |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Επιστρέφει την τιμή FontType, η οποία είναι ισοδύναμη με το καθορισμένο CSS-συμβατό |
όνομα του τύπου γραμματοσειράς
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Επιστρέφει την τιμή FontType, η οποία είναι ισοδύναμη με την επέκταση ονόματος αρχείου, η οποία |
εξάγεται από το καθορισμένο όνομα αρχείου
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Επιστρέφει την τιμή FontType, η οποία είναι ισοδύναμη με τον καθορισμένο κωδικό MIME |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Επιστρέφει τον πρώτο τύπο γραμματοσειράς από το καθορισμένο σύνολο, ο οποίος δεν είναι "Undefined" |
τιμή, ή τύπο γραμματοσειράς "Undefined" διαφορετικά (όταν όλα τα στοιχεία είναι
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο "FontType" |
αντικείμενο
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν αυτή η περίπτωση είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο, |
που προφανώς είναι μια άλλη παρουσία "FontType"
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Ελέγχει εάν δύο τιμές "FontType" είναι ίσες |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Ελέγχει εάν δύο τιμές "FontType" δεν είναι ίσες |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι ένας σταθερός αριθμός για αυτή τη συγκεκριμένη τιμή |
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


Ειδική τιμή, που σηματοδοτεί μη ορισμένη, άγνωστη ή μη υποστηριζόμενη γραμματοσειρά
πόρος


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


Αναπαριστά τύπο γραμματοσειράς WOFF (Web Open Font Format)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


Αναπαριστά τύπο γραμματοσειράς WOFF2 (Web Open Font Format έκδοση 2)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


Αναπαριστά τύπο γραμματοσειράς TTF (TrueType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


Αναπαριστά τύπο γραμματοσειράς OTF (OpenType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


Αναπαριστά γραμματοσειρά TrueType Collection (TTC)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


Αναπαριστά τύπο γραμματοσειράς EOT (Embedded OpenType)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Επιστρέφει το CSS-συμβατό όνομα αυτού του τύπου γραμματοσειράς, το οποίο χρησιμοποιείται στο


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


Επέκταση ονόματος αρχείου (χωρίς χαρακτήρα τελείας) για αυτόν τον τύπο γραμματοσειράς


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Μορφή γραμματοσειράς για τη μορφή @font-face


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


Επιστρέφει την τιμή FontType, η οποία είναι ισοδύναμη με το καθορισμένο CSS-συμβατό
όνομα του τύπου γραμματοσειράς


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | CSS-συμβατό όνομα του τύπου γραμματοσειράς |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Επιστρέφει την τιμή FontType, η οποία είναι ισοδύναμη με την επέκταση ονόματος αρχείου, η οποία
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


Επιστρέφει την τιμή FontType, η οποία είναι ισοδύναμη με τον καθορισμένο κωδικό MIME


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Κωδικός MIME |
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


Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο "FontType"
αντικείμενο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Άλλη παρουσία FontType για έλεγχο με αυτήν |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει αν αυτή η περίπτωση είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο,
που προφανώς είναι μια άλλη παρουσία "FontType"


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Άλλη παρουσία προφανώς του struct FontType, η οποία είχε μετατραπεί σε System.Object |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

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
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

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
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι ένας σταθερός αριθμός για αυτή τη συγκεκριμένη τιμή
τύπος


**Returns:**
int - 4-μπάιτ υπογεγραμμένος ακέραιος, 0 για τιμή Undefined

