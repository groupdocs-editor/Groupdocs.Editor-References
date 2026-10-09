---
title: "LengthUnit"
second_title: "GroupDocs.Editor για Node.js μέσω Java API Reference"
description: "Όλες οι υποστηριζόμενες μονάδες μήκους"
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

Όλες οι υποστηριζόμενες μονάδες μήκους


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Unitless](#Unitless) | Unitless - δεν υπάρχει ορισμένη μονάδα μήκους. |
|
|  | [Px](#Px) | Pixel. |
|
|  | [Em](#Em) | Em. |
|
|  | [Ex](#Ex) | Ex (x-length). |
|
|  | [Cm](#Cm) | Cm. |
|
|  | [Mm](#Mm) | Mm. |
|
|  | [In](#In) | In. |
|
|  | [Pt](#Pt) | Pt. |
|
|  | [Pc](#Pc) | Pc. |
|
|  | [Ch](#Ch) | Ch. |
|
|  | [Rem](#Rem) | Rem. |
|
|  | [Vw](#Vw) | Vw - πλάτος προβολής. |
|
|  | [Vh](#Vh) | Vh - ύψος προβολής. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | Η τιμή είναι σχετική με μια σταθερή (εξωτερική) τιμή, που είναι το πλαίσιο |
εξαρτημένη.
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


Χωρίς μονάδα - δεν υπάρχει καθορισμένη μονάδα μήκους. Προεπιλεγμένη τιμή.


### Px {#Px}
```
public static final int Px
```


Pixel. Σχετικό με τη συσκευή προβολής. Για την οθόνη, συνήθως
ένα pixel (σημείο) της οθόνης.


### Em {#Em}
```
public static final int Em
```


Em. Αυτή η μονάδα αντιπροσωπεύει το υπολογισμένο μέγεθος γραμματοσειράς του στοιχείου.


### Ex {#Ex}
```
public static final int Ex
```


Ex (x-length). Αυτή η μονάδα αντιπροσωπεύει το x-ύψος του στοιχείου
γραμματοσειράς. Σε γραμματοσειρές με το γράμμα 'x', αυτό είναι γενικά το ύψος του
των πεζών γραμμάτων στη γραμματοσειρά· 1ex \\u2248 0.5em σε πολλές γραμματοσειρές.


### Cm {#Cm}
```
public static final int Cm
```


Cm. Ένα εκατοστό (10 χιλιοστά).


### Mm {#Mm}
```
public static final int Mm
```


Mm. Ένα χιλιοστό.


### In {#In}
```
public static final int In
```


In. Ένα ίντσα (2,54 εκατοστά).


### Pt {#Pt}
```
public static final int Pt
```


Pt. Ένα σημείο είναι 1/72 του ίντσας ή 0,353 χιλιοστά.


### Pc {#Pc}
```
public static final int Pc
```


Pc. Ένα pica (12 σημεία).


### Ch {#Ch}
```
public static final int Ch
```


Ch. Αυτή η μονάδα αντιπροσωπεύει το πλάτος, ή πιο ακριβώς την πρόοδο
μέτρηση, του γλύφου '0' (μηδέν, ο χαρακτήρας Unicode U+0030) στο
γραμματοσειρά του στοιχείου.


### Rem {#Rem}
```
public static final int Rem
```


Rem. Αυτή η μονάδα αντιπροσωπεύει το μέγεθος γραμματοσειράς του ριζικού στοιχείου (π.χ. το
μέγεθος γραμματοσειράς του \<html\> στοιχείου). Όταν χρησιμοποιείται στο μέγεθος γραμματοσειράς στο
Αυτό το στοιχείο ρίζας, αντιπροσωπεύει την αρχική του τιμή.


### Vw {#Vw}
```
public static final int Vw
```


Vw - πλάτος του παραθύρου προβολής. 1/100 του πλάτους του παραθύρου προβολής.


### Vh {#Vh}
```
public static final int Vh
```


Vh - ύψος του παραθύρου προβολής. 1/100 του ύψους του παραθύρου προβολής.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 1/100 της ελάχιστης τιμής μεταξύ του ύψους και του πλάτους
του παραθύρου προβολής.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 1/100 της μέγιστης τιμής μεταξύ του ύψους και του πλάτους
του παραθύρου προβολής.


### Percent {#Percent}
```
public static final int Percent
```


Η τιμή είναι σχετική με μια σταθερή (εξωτερική) τιμή, που είναι το πλαίσιο
εξαρτημένο. 1% = 1/100 της εξωτερικής τιμής.


### getUnit() {#getUnit--}
```
public static Integer[] getUnit()
```




**Returns:**
java.lang.Integer[]
### getUnits() {#getUnits--}
```
public static Map<Integer,String> getUnits()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
