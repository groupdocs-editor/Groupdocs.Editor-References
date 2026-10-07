---
title: "Ratio"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt een ratio CSS‑datatype voor dat wordt gebruikt voor het beschrijven van beeldverhoudingen in media‑queries en voor rasterafbeeldingen door de verhouding tussen twee eenheidloze waarden, genaamd teller en noemer, aan te geven."
type: docs
weight: 14
url: /nl/java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

Stelt een \"ratio\" CSS‑datatype voor, dat wordt gebruikt voor het beschrijven van aspect
verhoudingen in media‑queries en voor rasterafbeeldingen door de proportie
tussen twee eenheidloze waarden genaamd \"numerator\" en \"denominator\". Onveranderlijk
struct.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Single](#Single) | Enkele standaardratio 1/1 |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | Retourneert een teller van deze ratio |
|
|  | [getDenominator()](#getDenominator--) | Retourneert een noemer van deze ratio |
|
|  | [calculate()](#calculate--) | Berekent en retourneert deze ratio als een enkel zwevend‑kommagetal |
|
|  | [getInverseRatio()](#getInverseRatio--) | Genereert en retourneert een inverse (reciprocale) ratio voor deze ratio |
|
|  | [serializeDefault()](#serializeDefault--) | Serialiseert deze ratio naar een string en retourneert deze |
|
|  | [toString()](#toString--) | Retourneert een stringrepresentatie van deze ratio; hetzelfde als |
\"SerializeDefault()\"
|
|  | [isDefault()](#isDefault--) | Bepaalt of deze ratio de standaardwaarde heeft of een \"1/1\" (Enkel) is |
|
|  | [deepClone()](#deepClone--) | Retourneert een volledige kopie van deze ratio |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Bepaalt of deze instantie gelijk is aan de opgegeven \"Ratio\"‑instantie |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object, |
die vermoedelijk een andere "Ratio" instantie is
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Vergelijkt twee verhoudingen en retourneert een boolean die aangeeft of de twee overeenkomen. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Vergelijkt twee verhoudingen en retourneert een boolean die aangeeft of de twee niet |
overeenkomen.
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode voor deze instantie, die niet kan worden gewijzigd tijdens zijn |
levensduur
|
|  | [create(int numerator, int denominator)](#create-int-int-) | Maakt en retourneert één Ratio‑instantie van de opgegeven teller en |
noemer
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


Enkele standaardratio 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Retourneert een teller van deze ratio


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Retourneert een noemer van deze ratio


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


Berekent en retourneert deze ratio als een enkel zwevend‑kommagetal


**Returns:**
double - Floating-point getal met dubbele precisie

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Genereert en retourneert een inverse (reciprocale) ratio voor deze ratio


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serialiseert deze ratio naar een string en retourneert deze


**Returns:**
java.lang.String - String in "teller/noemer" formaat

### toString() {#toString--}
```
public String toString()
```


Retourneert een stringrepresentatie van deze ratio; hetzelfde als
\"SerializeDefault()\"


**Returns:**
java.lang.String - String in "teller/noemer" formaat

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Bepaalt of deze ratio de standaardwaarde heeft of een \"1/1\" (Enkel) is


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Retourneert een volledige kopie van deze ratio


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Bepaalt of deze instantie gelijk is aan de opgegeven \"Ratio\"‑instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Andere Ratio‑instantie om op gelijkheid met deze te controleren |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object,
die vermoedelijk een andere "Ratio" instantie is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | anders | java.lang.Object | Andere System.Object‑instantie, die vermoedelijk van het type Ratio is, om op gelijkheid met deze te controleren |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


Vergelijkt twee verhoudingen en retourneert een boolean die aangeeft of de twee overeenkomen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | De eerste te gebruiken verhouding. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | De tweede te gebruiken verhouding. |
|

**Returns:**
boolean - Waar als beide verhoudingen gelijk zijn, anders onwaar.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


Vergelijkt twee verhoudingen en retourneert een boolean die aangeeft of de twee niet
overeenkomen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | De eerste te gebruiken verhouding. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | De tweede te gebruiken verhouding. |
|

**Returns:**
boolean - Waar als beide verhoudingen niet gelijk zijn, anders onwaar.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor deze instantie, die niet kan worden gewijzigd tijdens zijn
levensduur


**Returns:**
int - Ondertekend 4-byte geheel getal, dat onveranderlijk is voor deze instantie

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Maakt en retourneert één Ratio‑instantie van de opgegeven teller en
noemer


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | teller | int | Teller voor de verhouding. Moet een strikt positief geheel getal zijn. |
|
|  | noemer | int | Noemer voor de verhouding. Moet een strikt positief geheel getal zijn. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

