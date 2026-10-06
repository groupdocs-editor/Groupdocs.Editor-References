---
title: "WebFont"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Αναπαριστά ρυθμίσεις γραμματοσειράς για το web."
type: docs
weight: 43
url: /el/java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

Αναπαριστά ρυθμίσεις γραμματοσειράς για το web.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getColor()](#getColor--) | Χρώμα γραμματοσειράς σε μορφή ARGB32 |
|
|  | [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Χρώμα γραμματοσειράς σε μορφή ARGB32 |
|
|  | [getWeight()](#getWeight--) | Ορίζει το βάρος (ή την έντονη γραφή) της γραμματοσειράς |
|
|  | [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Ορίζει το βάρος (ή την έντονη γραφή) της γραμματοσειράς |
|
|  | [getStyle()](#getStyle--) | Ορίζει εάν μια γραμματοσειρά πρέπει να μορφοποιηθεί με κανονική, πλάγια ή λοξή μορφή από την οικογένεια γραμματοσειρών της. |
|
|  | [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Ορίζει εάν μια γραμματοσειρά πρέπει να μορφοποιηθεί με κανονική, πλάγια ή λοξή μορφή από την οικογένεια γραμματοσειρών της. |
|
|  | [getLine()](#getLine--) | Ορίζει μια γραμμή ή συνδυασμό γραμμών, που εφαρμόζεται στο κείμενο |
|
|  | [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Ορίζει μια γραμμή ή συνδυασμό γραμμών, που εφαρμόζεται στο κείμενο |
|
|  | [getSize()](#getSize--) | Ορίζει το μέγεθος της γραμματοσειράς σε απόλυτες ή σχετικές μονάδες |
|
|  | [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Ορίζει το μέγεθος της γραμματοσειράς σε απόλυτες ή σχετικές μονάδες |
|
|  | [getName()](#getName--) | Ορίζει το όνομα της γραμματοσειράς. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα της γραμματοσειράς. |
|
|  | [deepClone()](#deepClone--) | Δημιουργεί και επιστρέφει ένα πλήρες βαθύ αντίγραφο αυτής της παρουσίας του [WebFont](../../com.groupdocs.editor.options/webfont) |
|
|  | [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | Καθορίζει εάν αυτή η παρουσία του WebFont είναι ίση με την καθορισμένη |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία του WebFont είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο |
|
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


Χρώμα γραμματοσειράς σε μορφή ARGB32


**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


Χρώμα γραμματοσειράς σε μορφή ARGB32


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


Ορίζει το βάρος (ή την έντονη γραφή) της γραμματοσειράς


**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


Ορίζει το βάρος (ή την έντονη γραφή) της γραμματοσειράς


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


Ορίζει εάν μια γραμματοσειρά πρέπει να μορφοποιηθεί με κανονική, πλάγια ή λοξή μορφή από την οικογένεια γραμματοσειρών της.


**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


Ορίζει εάν μια γραμματοσειρά πρέπει να μορφοποιηθεί με κανονική, πλάγια ή λοξή μορφή από την οικογένεια γραμματοσειρών της.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


Ορίζει μια γραμμή ή συνδυασμό γραμμών, που εφαρμόζεται στο κείμενο


**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


Ορίζει μια γραμμή ή συνδυασμό γραμμών, που εφαρμόζεται στο κείμενο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


Ορίζει το μέγεθος της γραμματοσειράς σε απόλυτες ή σχετικές μονάδες


**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


Ορίζει το μέγεθος της γραμματοσειράς σε απόλυτες ή σχετικές μονάδες


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


Ορίζει το όνομα της γραμματοσειράς. Εάν δεν καθοριστεί, θα χρησιμοποιηθεί η προεπιλεγμένη γραμματοσειρά


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ορίζει το όνομα της γραμματοσειράς. Εάν δεν καθοριστεί, θα χρησιμοποιηθεί η προεπιλεγμένη γραμματοσειρά


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


Δημιουργεί και επιστρέφει ένα πλήρες βαθύ αντίγραφο αυτής της παρουσίας του [WebFont](../../com.groupdocs.editor.options/webfont)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one

### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


Καθορίζει εάν αυτή η παρουσία του WebFont είναι ίση με την καθορισμένη


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [WebFont](../../com.groupdocs.editor.options/webfont) | Ένα άλλο WebFont για έλεγχο ισότητας, μπορεί να είναι NULL |
|

**Returns:**
boolean - true εάν είναι ίσο, false εάν δεν είναι ίσο

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτή η παρουσία του WebFont είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | obj | java.lang.Object | Object, που αναμένεται να είναι μια παρουσία του [WebFont](../../com.groupdocs.editor.options/webfont) |
|

**Returns:**
boolean - true εάν είναι ίσο, false εάν δεν είναι ίσο

