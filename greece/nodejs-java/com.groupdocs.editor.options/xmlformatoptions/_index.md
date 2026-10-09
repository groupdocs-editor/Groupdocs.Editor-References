---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Περιέχει επιλογές που επιτρέπουν την προσαρμογή της μορφοποίησης του εγγράφου XML όταν αυτό αντιπροσωπεύεται ως HTML"
type: docs
weight: 52
url: /el/nodejs-java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

Περιέχει επιλογές που επιτρέπουν την προσαρμογή της μορφοποίησης του εγγράφου XML, όταν εμφανίζεται ως HTML.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | Όταν είναι ενεργοποιημένο, κάθε ζεύγος χαρακτηριστικό-τιμή σε κάθε στοιχείο XML θα τοποθετείται σε νέα γραμμή. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | Όταν είναι ενεργοποιημένο, κάθε ζεύγος χαρακτηριστικό-τιμή σε κάθε στοιχείο XML θα τοποθετείται σε νέα γραμμή. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | Όταν είναι ενεργοποιημένο, οι φύλλα κόμβοι κειμένου (κειμενικό περιεχόμενο μέσα σε στοιχεία XML, που δεν έχουν παιδιά) θα αποδίδονται σε νέα γραμμή με μεγαλύτερη αριστερή εσοχή. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | Όταν είναι ενεργοποιημένο, οι φύλλα κόμβοι κειμένου (κειμενικό περιεχόμενο μέσα σε στοιχεία XML, που δεν έχουν παιδιά) θα αποδίδονται σε νέα γραμμή με μεγαλύτερη αριστερή εσοχή. |
|
|  | [getLeftIndent()](#getLeftIndent--) | Επιτρέπει τον καθορισμό μιας μετατόπισης για την αριστερή εσοχή κάθε νέας γραμμής. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Επιτρέπει τον καθορισμό μιας μετατόπισης για την αριστερή εσοχή κάθε νέας γραμμής. |
|
|  | [isDefault()](#isDefault--) | Δείχνει εάν αυτή η παρουσία των επιλογών μορφοποίησης XML έχει προεπιλεγμένη τιμή |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


Όταν είναι ενεργοποιημένο, κάθε ζεύγος χαρακτηριστικό-τιμή σε κάθε στοιχείο XML θα τοποθετείται σε νέα γραμμή.
Από προεπιλογή είναι ψευδές (απενεργοποιημένο) \u2014 όλα τα ζεύγη χαρακτηριστικό-τιμή τοποθετούνται σε μία γραμμή.


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


Όταν είναι ενεργοποιημένο, κάθε ζεύγος χαρακτηριστικό-τιμή σε κάθε στοιχείο XML θα τοποθετείται σε νέα γραμμή.
Από προεπιλογή είναι ψευδές (απενεργοποιημένο) \u2014 όλα τα ζεύγη χαρακτηριστικό-τιμή τοποθετούνται σε μία γραμμή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


Όταν είναι ενεργοποιημένο, οι φύλλα κόμβοι κειμένου (κειμενικό περιεχόμενο μέσα σε στοιχεία XML, που δεν έχουν παιδιά) θα αποδίδονται σε νέα γραμμή με μεγαλύτερη αριστερή εσοχή.
Από προεπιλογή είναι ψευδές (απενεργοποιημένο) \u2014 οι φύλλοι κόμβοι κειμένου τοποθετούνται στην ίδια γραμμή με τους γονείς τους, χωρίς νέα εσοχή.


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


Όταν είναι ενεργοποιημένο, οι φύλλα κόμβοι κειμένου (κειμενικό περιεχόμενο μέσα σε στοιχεία XML, που δεν έχουν παιδιά) θα αποδίδονται σε νέα γραμμή με μεγαλύτερη αριστερή εσοχή.
Από προεπιλογή είναι ψευδές (απενεργοποιημένο) \u2014 οι φύλλοι κόμβοι κειμένου τοποθετούνται στην ίδια γραμμή με τους γονείς τους, χωρίς νέα εσοχή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


Επιτρέπει τον καθορισμό μιας μετατόπισης για την αριστερή εσοχή κάθε νέας γραμμής. Δεν μπορεί να είναι τιμή χωρίς μονάδα και μη μηδενική. Από προεπιλογή είναι 10pt.


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


Επιτρέπει τον καθορισμό μιας μετατόπισης για την αριστερή εσοχή κάθε νέας γραμμής. Δεν μπορεί να είναι τιμή χωρίς μονάδα και μη μηδενική. Από προεπιλογή είναι 10pt.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Δείχνει εάν αυτή η παρουσία των επιλογών μορφοποίησης XML έχει προεπιλεγμένη τιμή


**Returns:**
boolean
