---
title: "ImageType"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αντιπροσωπεύει έναν υποστηριζόμενο τύπο μορφής εικόνας που υποστηρίζει τόσο raster όσο και vector μορφές"
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

Αντιπροσωπεύει έναν υποστηριζόμενο τύπο εικόνας (format), υποστηρίζει τόσο ραστερικές όσο και διανυσματικές μορφές.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Απροσδιόριστος τύπος εικόνας - ειδική τιμή, η οποία δεν θα έπρεπε να εμφανίζεται κανονικά |
|
|  | [getJpeg()](#getJpeg--) | Τύπος εικόνας JPEG |
|
|  | [getPng()](#getPng--) | Τύπος εικόνας PNG |
|
|  | [getBmp()](#getBmp--) | Τύπος εικόνας BMP |
|
|  | [getGif()](#getGif--) | Τύπος εικόνας GIF |
|
|  | [getIcon()](#getIcon--) | Τύπος εικόνας ICON |
|
|  | [getSvg()](#getSvg--) | Τύπος διανυσματικής εικόνας SVG |
|
|  | [getWmf()](#getWmf--) | Τύπος διανυσματικής εικόνας WMF (Windows MetaFile) |
|
|  | [getEmf()](#getEmf--) | Τύπος διανυσματικής εικόνας EMF (Enhanced MetaFile) |
|
|  | [getTiff()](#getTiff--) | Τύπος raster εικόνας TIFF (Tagged Image File Format) |
|
|  | [getFormalName()](#getFormalName--) | Επιστρέφει ένα επίσημο όνομα αυτού του μορφότυπου εικόνας. |
|
|  | [isVector()](#isVector--) | Δείχνει αν αυτό το συγκεκριμένο μορφότυπο είναι διανυσματικό (true) ή raster |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | Επέκταση αρχείου (χωρίς το αρχικό χαρακτήρα τελείας) ενός συγκεκριμένου τύπου εικόνας |
σε πεζά.
|
|  | [toString()](#toString--) | Επιστρέφει την ιδιότητα FormalName |
|
|  | [getMimeCode()](#getMimeCode--) | Κωδικός MIME ενός συγκεκριμένου τύπου εικόνας ως συμβολοσειρά. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Καθορίζει αν αυτή η παρουσία είναι ίση με το καθορισμένο "ImageType" |
αντικείμενο
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν αυτή η περίπτωση είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο, |
που προφανώς είναι μια άλλη παρουσία "ImageType"
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Ορίζει αν δύο συγκεκριμένες παρουσίες ImageType είναι ίσες |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Ορίζει αν δύο συγκεκριμένες παρουσίες ImageType δεν είναι ίσες |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό hash, ο οποίος είναι ένας αμετάβλητος αριθμός για αυτό το συγκεκριμένο |
αντικείμενο
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Επιστρέφει την τιμή ImageType, η οποία είναι ισοδύναμη με την επέκταση ονόματος αρχείου, η οποία |
εξάγεται από το καθορισμένο όνομα αρχείου
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Επιστρέφει την τιμή ImageType, η οποία είναι ισοδύναμη με τον καθορισμένο κωδικό MIME |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


Απροσδιόριστος τύπος εικόνας - ειδική τιμή, η οποία δεν θα έπρεπε να εμφανίζεται κανονικά


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


Τύπος εικόνας JPEG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


Τύπος εικόνας PNG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


Τύπος εικόνας BMP


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


Τύπος εικόνας GIF


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


Τύπος εικόνας ICON


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


Τύπος διανυσματικής εικόνας SVG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


Τύπος διανυσματικής εικόνας WMF (Windows MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


Τύπος διανυσματικής εικόνας EMF (Enhanced MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


Τύπος raster εικόνας TIFF (Tagged Image File Format)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Επιστρέφει ένα επίσημο όνομα αυτού του μορφότυπου εικόνας. Ποτέ δεν επιστρέφει NULL. Εάν
η παρουσία δεν είναι κατεστραμμένη, ποτέ δεν προκαλεί εξαίρεση.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


Δείχνει αν αυτό το συγκεκριμένο μορφότυπο είναι διανυσματικό (true) ή raster
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Επέκταση αρχείου (χωρίς το αρχικό χαρακτήρα τελείας) ενός συγκεκριμένου τύπου εικόνας
σε πεζά. Για τον τύπο Undefined επιστρέφει μια συμβολοσειρά 'unsefined'.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει την ιδιότητα FormalName


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Κωδικός MIME ενός συγκεκριμένου τύπου εικόνας ως συμβολοσειρά. Για τον τύπο Undefined
επιστρέφει μια συμβολοσειρά 'unsefined'.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


Καθορίζει αν αυτή η παρουσία είναι ίση με το καθορισμένο "ImageType"
αντικείμενο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Άλλη παρουσία ImageType για έλεγχο ισότητας με αυτήν |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει αν αυτή η περίπτωση είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο,
που προφανώς είναι μια άλλη παρουσία "ImageType"


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Άλλη παρουσία System.Object, η οποία προφανώς είναι τύπου ImageType, για έλεγχο ισότητας με αυτήν |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


Ορίζει αν δύο συγκεκριμένες παρουσίες ImageType είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Πρώτη παρουσία ImageType για έλεγχο |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Δεύτερη παρουσία ImageType για έλεγχο |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


Ορίζει αν δύο συγκεκριμένες παρουσίες ImageType δεν είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Πρώτη παρουσία ImageType για έλεγχο |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Δεύτερη παρουσία ImageType για έλεγχο |
|

**Returns:**
boolean - True αν είναι διαφορετικές, false αν είναι ίσες

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό hash, ο οποίος είναι ένας αμετάβλητος αριθμός για αυτό το συγκεκριμένο
αντικείμενο


**Returns:**
int - Υπογεγραμμένος ακέραιος 4-μπάιτ

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


Επιστρέφει την τιμή ImageType, η οποία είναι ισοδύναμη με την επέκταση ονόματος αρχείου, η οποία
εξάγεται από το καθορισμένο όνομα αρχείου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα αρχείου | java.lang.String | Τυχαίο όνομα αρχείου, μπορεί να είναι σχετικό ή πλήρης διαδρομή |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


Επιστρέφει την τιμή ImageType, η οποία είναι ισοδύναμη με τον καθορισμένο κωδικό MIME


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Τυχαίος κώδικας MIME |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

