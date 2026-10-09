---
title: "ArgbColor"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Αντιπροσωπεύει μία τιμή χρώματος σε μορφή ARGB με μετατροπείς και σειριοποιητές"
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

Αντιπροσωπεύει μία τιμή χρώματος σε μορφή ARGB με μετατροπείς και σειριοποιητές

<br />

*** ** * ** ***

Αυτός ο τύπος έχει σχεδιαστεί ώστε να είναι χρήσιμος για (αλλά όχι μόνο) λειτουργίες CSS. Δείτε περισσότερα: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Δημιουργεί μία τιμή [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) από τα καθορισμένα κανάλια Red, Green, Blue και Alpha |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Δημιουργεί μία τιμή [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) από τα καθορισμένα κανάλια Red, Green, Blue, ενώ το κανάλι Alpha είναι πλήρως αδιαφανές |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Δημιουργεί ένα πλήρως αδιαφανές (A=255) χρώμα από μία μοναδική τιμή, η οποία θα εφαρμοστεί σε όλα τα κανάλια |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | Δημιουργεί μία τιμή [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) από το καθορισμένο [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) |
|
|  | [getValue()](#getValue--) | Λαμβάνει την τιμή Int32 του χρώματος. |
|
|  | [getA()](#getA--) | Λαμβάνει το μέρος alpha του χρώματος. |
|
|  | [getAlpha()](#getAlpha--) | Λαμβάνει το μέρος alpha του χρώματος σε ποσοστό (0..1). |
|
|  | [getR()](#getR--) | Λαμβάνει το μέρος red του χρώματος. |
|
|  | [getG()](#getG--) | Λαμβάνει το μέρος green του χρώματος. |
|
|  | [getB()](#getB--) | Λαμβάνει το μέρος blue του χρώματος. |
|
|  | [isEmpty()](#isEmpty--) | Μη αρχικοποιημένο χρώμα - όλα τα 4 κανάλια έχουν τιμή 0. |
|
|  | [isDefault()](#isDefault--) | Δείχνει εάν αυτή η παρουσία [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) είναι προεπιλεγμένη (Διαφανής) - όλα τα 4 κανάλια έχουν τιμή 0 |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | Δείχνει εάν αυτή η παρουσία [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) είναι πλήρως διαφανής - το κανάλι Alpha έχει την ελάχιστη (0) τιμή, έτσι τα άλλα κανάλια R, G και B δεν έχουν ορατό αποτέλεσμα. |
|
|  | [isTranslucent()](#isTranslucent--) | Δείχνει εάν αυτή η παρουσία [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) είναι ημιδιαφανής (δεν είναι πλήρως διαφανής, αλλά ούτε και πλήρως αδιαφανής) |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | Δείχνει εάν αυτή η παρουσία [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) είναι πλήρως αδιαφανής, χωρίς διαφάνεια (το κανάλι Alpha έχει τη μέγιστη τιμή) |
|
|  | [toSystemColor()](#toSystemColor--) | Μετατρέπει μια τιμή αυτής της παρουσίασης [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) σε παρουσία [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) και την επιστρέφει |
|
|  | [toRGBA()](#toRGBA--) | Σειριοποιεί αυτό το [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) αντικείμενο στη σημειογραφία συνάρτησης CSS 'rgba' |
|
|  | [toRGB()](#toRGB--) | Σειριοποιεί αυτό το [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) αντικείμενο στη σημειογραφία συνάρτησης CSS 'rgb' |
|
|  | [serializeDefault()](#serializeDefault--) | Σειριοποιεί αυτό το [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) αντικείμενο στην πιο κατάλληλη σημειογραφία συνάρτησης CSS ανάλογα με τη διαφάνεια |
|
|  | [toString()](#toString--) | Ίδιο με #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Συγκρίνει δύο χρώματα και επιστρέφει μια boolean τιμή που υποδεικνύει αν τα δύο ταιριάζουν. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Συγκρίνει δύο χρώματα και επιστρέφει μια boolean τιμή που υποδεικνύει αν τα δύο δεν ταιριάζουν. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Ελέγχει δύο χρώματα [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) για ισότητα |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | Ελέγχει δύο χρώματα [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) για ισότητα |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Δοκιμάζει αν ένα άλλο αντικείμενο είναι ίσο με αυτό το [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) αντικείμενο. |
|
|  | [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό hash που ορίζει το τρέχον χρώμα. |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


Δημιουργεί μία τιμή [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) από τα καθορισμένα κανάλια Red, Green, Blue και Alpha


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κόκκινο | int | Τιμή καναλιού κόκκινου |
|
|  | πράσινο | int | Τιμή καναλιού πράσινου |
|
|  | μπλε | int | Τιμή καναλιού μπλε |
|
|  | άλφα | int | Τιμή καναλιού άλφα |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Δημιουργεί μία τιμή [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) από τα καθορισμένα κανάλια Red, Green, Blue, ενώ το κανάλι Alpha είναι πλήρως αδιαφανές


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κόκκινο | int | Τιμή καναλιού κόκκινου |
|
|  | πράσινο | int | Τιμή καναλιού πράσινου |
|
|  | μπλε | int | Τιμή καναλιού μπλε |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Δημιουργεί ένα πλήρως αδιαφανές (A=255) χρώμα από μία μοναδική τιμή, η οποία θα εφαρμοστεί σε όλα τα κανάλια


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | byte | Μια τιμή byte, ίδια για τα κανάλια κόκκινο, πράσινο και μπλε |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Δημιουργεί μία τιμή [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) από το καθορισμένο [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| χρώμα | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


Λαμβάνει την τιμή Int32 του χρώματος.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Λαμβάνει το μέρος alpha του χρώματος.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Λαμβάνει το μέρος alpha του χρώματος σε ποσοστό (0..1).


**Returns:**
διπλός
### getR() {#getR--}
```
public final int getR()
```


Λαμβάνει το μέρος red του χρώματος.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Λαμβάνει το μέρος green του χρώματος.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Λαμβάνει το μέρος blue του χρώματος.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Μη αρχικοποιημένο χρώμα - όλα τα 4 κανάλια έχουν τιμή 0. Το ίδιο με Default και Transparent.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Δείχνει εάν αυτή η παρουσία [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) είναι προεπιλεγμένη (Διαφανής) - όλα τα 4 κανάλια έχουν τιμή 0


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Δείχνει εάν αυτή η παρουσία [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) είναι πλήρως διαφανής - το κανάλι Alpha έχει την ελάχιστη (0) τιμή, έτσι τα άλλα κανάλια R, G και B δεν έχουν ορατό αποτέλεσμα.


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Δείχνει εάν αυτή η παρουσία [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) είναι ημιδιαφανής (δεν είναι πλήρως διαφανής, αλλά ούτε και πλήρως αδιαφανής)


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Δείχνει εάν αυτή η παρουσία [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) είναι πλήρως αδιαφανής, χωρίς διαφάνεια (το κανάλι Alpha έχει τη μέγιστη τιμή)


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Μετατρέπει μια τιμή αυτής της παρουσίασης [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) σε παρουσία [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) και την επιστρέφει


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Σειριοποιεί αυτό το [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) αντικείμενο στη σημειογραφία συνάρτησης CSS 'rgba'


**Returns:**
java.lang.String - Μια συμβολοσειρά με μορφή 'rgba(r, g, b, a)'

### toRGB() {#toRGB--}
```
public final String toRGB()
```


Σειριοποιεί αυτό το [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) αντικείμενο στη σημειογραφία συνάρτησης CSS 'rgb'


**Returns:**
java.lang.String - Μια συμβολοσειρά με μορφή 'rgb(r, g, b)'

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Σειριοποιεί αυτό το [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) αντικείμενο στην πιο κατάλληλη σημειογραφία συνάρτησης CSS ανάλογα με τη διαφάνεια


**Returns:**
java.lang.String - Μια συμβολοσειρά με μορφή 'rgba(r, g, b, a)' ή 'rgb(r, g, b)'

### toString() {#toString--}
```
public String toString()
```


Ίδιο με #serializeDefault.serializeDefault


**Returns:**
java.lang.String - Ίδια τιμή επιστροφής όπως στο #serializeDefault.serializeDefault

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


Συγκρίνει δύο χρώματα και επιστρέφει μια boolean τιμή που υποδεικνύει αν τα δύο ταιριάζουν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Το πρώτο χρώμα προς χρήση. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Το δεύτερο χρώμα προς χρήση. |
|

**Returns:**
boolean - Αληθές εάν και τα δύο χρώματα είναι ίσα, διαφορετικά ψευδές.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


Συγκρίνει δύο χρώματα και επιστρέφει μια boolean τιμή που υποδεικνύει αν τα δύο δεν ταιριάζουν.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Το πρώτο χρώμα προς χρήση. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Το δεύτερο χρώμα προς χρήση. |
|

**Returns:**
boolean - Αληθές εάν και τα δύο χρώματα δεν είναι ίσα, διαφορετικά ψευδές.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


Ελέγχει δύο χρώματα [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) για ισότητα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | Το άλλο χρώμα [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |
|

**Returns:**
boolean - Αληθές εάν και τα δύο χρώματα είναι ίσα, διαφορετικά ψευδές.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


Ελέγχει δύο χρώματα [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) για ισότητα


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | Το άλλο χρώμα [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor), μετατρεπόμενο σε ICssDataType |
|

**Returns:**
boolean - Αληθές εάν και τα δύο χρώματα είναι ίσα, διαφορετικά ψευδές.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Δοκιμάζει αν ένα άλλο αντικείμενο είναι ίσο με αυτό το [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) αντικείμενο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | άλλο | java.lang.Object | Το αντικείμενο με το οποίο θα δοκιμαστεί. |
|

**Returns:**
boolean - Αληθές εάν τα δύο αντικείμενα είναι ίσα, διαφορετικά ψευδές.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό hash που ορίζει το τρέχον χρώμα.


**Returns:**
int - Η ακέραια τιμή του κώδικα κατακερματισμού.

