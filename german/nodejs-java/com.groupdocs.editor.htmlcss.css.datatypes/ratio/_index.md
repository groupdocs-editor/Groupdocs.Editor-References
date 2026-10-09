---
title: "Verhältnis"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt einen ratio CSS‑Datentyp dar, der verwendet wird, um Seitenverhältnisse in Media Queries zu beschreiben und für Rasterbilder, indem er das Verhältnis zwischen zwei einheitenlosen Werten, genannt Zähler und Nenner, angibt."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

Stellt einen "ratio" CSS‑Datentyp dar, der verwendet wird, um das Seitenverhältnis zu beschreiben
von Verhältnissen in Media Queries und für Rasterbilder, indem die Proportion
zwischen zwei einheitenlosen Werten, genannt "numerator" und "denominator". Unveränderlich
Struktur.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Single](#Single) | Einzelnes Standardverhältnis 1/1 |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | Gibt einen Zähler dieses Verhältnisses zurück |
|
|  | [getDenominator()](#getDenominator--) | Gibt einen Nenner dieses Verhältnisses zurück |
|
|  | [calculate()](#calculate--) | Berechnet und gibt dieses Verhältnis als einzelne Gleitkommazahl zurück |
|
|  | [getInverseRatio()](#getInverseRatio--) | Erzeugt und gibt ein inverses (reziprokes) Verhältnis für dieses Verhältnis zurück |
|
|  | [serializeDefault()](#serializeDefault--) | Serialisiert dieses Verhältnis in einen String und gibt ihn zurück |
|
|  | [toString()](#toString--) | Gibt eine String-Darstellung dieses Verhältnisses zurück; gleich wie |
"SerializeDefault()"
|
|  | [isDefault()](#isDefault--) | Bestimmt, ob dieses Verhältnis den Standardwert hat oder ein "1/1" (Einfach) ist |
|
|  | [deepClone()](#deepClone--) | Gibt eine vollständige Kopie dieses Verhältnisses zurück |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Bestimmt, ob diese Instanz mit der angegebenen "Ratio"-Instanz gleich ist |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Bestimmt, ob diese Instanz mit dem angegebenen nicht gecasteten Objekt gleich ist, |
die vermutlich eine andere "Ratio"-Instanz ist
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Vergleicht zwei Verhältnisse und gibt einen booleschen Wert zurück, der angibt, ob die beiden übereinstimmen. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Vergleicht zwei Verhältnisse und gibt einen booleschen Wert zurück, der angibt, ob die beiden nicht |
übereinstimmen.
|
|  | [hashCode()](#hashCode--) | Gibt einen Hashcode für diese Instanz zurück, der während ihrer |
Lebensdauer
|
|  | [create(int numerator, int denominator)](#create-int-int-) | Erstellt und gibt eine Ratio-Instanz aus dem angegebenen Zähler und |
Nenner
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


Einzelnes Standardverhältnis 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Gibt einen Zähler dieses Verhältnisses zurück


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Gibt einen Nenner dieses Verhältnisses zurück


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


Berechnet und gibt dieses Verhältnis als einzelne Gleitkommazahl zurück


**Returns:**
double - Gleitkommazahl mit doppelter Genauigkeit

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Erzeugt und gibt ein inverses (reziprokes) Verhältnis für dieses Verhältnis zurück


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serialisiert dieses Verhältnis in einen String und gibt ihn zurück


**Returns:**
java.lang.String - Zeichenkette im Format "numerator/denominator"

### toString() {#toString--}
```
public String toString()
```


Gibt eine String-Darstellung dieses Verhältnisses zurück; gleich wie
"SerializeDefault()"


**Returns:**
java.lang.String - Zeichenkette im Format "numerator/denominator"

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bestimmt, ob dieses Verhältnis den Standardwert hat oder ein "1/1" (Einfach) ist


**Returns:**
boolesch
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Gibt eine vollständige Kopie dieses Verhältnisses zurück


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Bestimmt, ob diese Instanz mit der angegebenen "Ratio"-Instanz gleich ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Andere Ratio-Instanz zum Prüfen der Gleichheit mit dieser |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Bestimmt, ob diese Instanz mit dem angegebenen nicht gecasteten Objekt gleich ist,
die vermutlich eine andere "Ratio"-Instanz ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | andere | java.lang.Object | Andere System.Object-Instanz, die vermutlich vom Typ Ratio ist, zum Prüfen der Gleichheit mit dieser |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


Vergleicht zwei Verhältnisse und gibt einen booleschen Wert zurück, der angibt, ob die beiden übereinstimmen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Das erste zu verwendende Verhältnis. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Das zweite zu verwendende Verhältnis. |
|

**Returns:**
boolean - Wahr, wenn beide Verhältnisse gleich sind, sonst falsch.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


Vergleicht zwei Verhältnisse und gibt einen booleschen Wert zurück, der angibt, ob die beiden nicht
übereinstimmen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Das erste zu verwendende Verhältnis. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Das zweite zu verwendende Verhältnis. |
|

**Returns:**
boolean - Wahr, wenn beide Verhältnisse nicht gleich sind, sonst falsch.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für diese Instanz zurück, der während ihrer
Lebensdauer


**Returns:**
int - Vorzeichenbehaftete 4-Byte-Ganzzahl, die für diese Instanz unveränderlich ist

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Erstellt und gibt eine Ratio-Instanz aus dem angegebenen Zähler und
Nenner


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Zähler | int | Zähler für das Verhältnis. Sollte eine streng positive ganze Zahl sein. |
|
|  | Nenner | int | Nenner für das Verhältnis. Sollte eine streng positive ganze Zahl sein. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

