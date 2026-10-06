---
title: "AudioType"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά μία υποστηριζόμενη μορφή τύπου ήχου"
type: docs
weight: 10
url: /el/java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Αντιπροσωπεύει έναν υποστηριζόμενο τύπο ήχου (μορφή).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | Επίσημη ονομασία αυτού του μορφότυπου ήχου |
|
|  | [getFileExtension()](#getFileExtension--) | Επέκταση ονόματος αρχείου (χωρίς το χαρακτήρα τελείας) για αυτόν τον μορφότυπο ήχου |
|
|  | [getMimeCode()](#getMimeCode--) | Κωδικός MIME για αυτόν τον μορφότυπο ήχου |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το καθορισμένο "AudioType" αντικείμενο |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το καθορισμένο μη μετατρεπόμενο αντικείμενο, το οποίο προφανώς είναι ένα άλλο "AudioType" αντικείμενο |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Ελέγχει εάν δύο τιμές "AudioType" είναι ίσες |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Ελέγχει εάν δύο τιμές "AudioType" δεν είναι ίσες |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κώδικα κατακερματισμού, ο οποίος είναι ένας σταθερός αριθμός για αυτόν τον συγκεκριμένο τύπο τιμής |
|
|  | [getUndefined()](#getUndefined--) | Ειδική τιμή, η οποία σηματοδοτεί μη ορισμένη, άγνωστη ή μη υποστηριζόμενη μορφή ήχου |
|
|  | [getMp3()](#getMp3--) | Αναπαριστά μια μορφή ήχου MPEG-1 Audio Layer III |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Επιστρέφει τιμή AudioType, η οποία είναι ισοδύναμη με την επέκταση του ονόματος αρχείου, η οποία εξάγεται από το καθορισμένο όνομα αρχείου |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Επίσημη ονομασία αυτού του μορφότυπου ήχου


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Επέκταση ονόματος αρχείου (χωρίς το χαρακτήρα τελείας) για αυτόν τον μορφότυπο ήχου


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Κωδικός MIME για αυτόν τον μορφότυπο ήχου


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το καθορισμένο "AudioType" αντικείμενο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Άλλη παρουσία AudioType για έλεγχο με αυτήν |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτό το αντικείμενο είναι ίσο με το καθορισμένο μη μετατρεπόμενο αντικείμενο, το οποίο προφανώς είναι ένα άλλο "AudioType" αντικείμενο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Άλλη παρουσία πιθανώς του struct AudioType, η οποία είχε τοποθετηθεί σε System.Object |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


Ελέγχει εάν δύο τιμές "AudioType" είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Πρώτη AudioType για έλεγχο |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Δεύτερη AudioType για έλεγχο |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


Ελέγχει εάν δύο τιμές "AudioType" δεν είναι ίσες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Πρώτη AudioType για έλεγχο |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Δεύτερη AudioType για έλεγχο |
|

**Returns:**
boolean - Αληθές εάν είναι ίσες, ψευδές εάν δεν είναι ίσες

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κώδικα κατακερματισμού, ο οποίος είναι ένας σταθερός αριθμός για αυτόν τον συγκεκριμένο τύπο τιμής


**Returns:**
int - 4-μπάιτ υπογεγραμμένος ακέραιος, 0 για τιμή Undefined

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Ειδική τιμή, η οποία σηματοδοτεί μη ορισμένη, άγνωστη ή μη υποστηριζόμενη μορφή ήχου


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


Αναπαριστά μια μορφή ήχου MPEG-1 Audio Layer III


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Επιστρέφει τιμή AudioType, η οποία είναι ισοδύναμη με την επέκταση του ονόματος αρχείου, η οποία εξάγεται από το καθορισμένο όνομα αρχείου


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα αρχείου | java.lang.String | Τυχαίο όνομα αρχείου, μπορεί να είναι σχετικό ή πλήρης διαδρομή |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

