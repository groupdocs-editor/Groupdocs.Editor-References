---
title: "Lengte"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt een CSS-lengtewaarde voor in elke ondersteunde eenheid, inclusief percentage    en eenheidloze type."
type: docs
weight: 12
url: /nl/java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

Stelt een CSS-lengtewaarde voor in elke ondersteunde eenheid, inclusief percentage
en eenheidloze type. Waarden kunnen geheel of float zijn, negatief, nul en
positief. Onveranderlijke structuur.

*** ** * ** ***


Dit type omvat de volgende CSS-gegevens typen:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Length()](#Length--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | Eenheidloze gehele nul - standaardwaarde, dezelfde als standaard zonder parameters |
constructor
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | Maakt en retourneert een instantie van het type Length op basis van een opgegeven float‑getal |
en eenheid
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | Maakt en retourneert een instantie van het type Length op basis van een opgegeven double‑getal |
en eenheid
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | Maakt en retourneert een instantie van het type Length op basis van een opgegeven integer |
getal en eenheid
|
|  | [isUnitlessZero()](#isUnitlessZero--) | Bepaalt of deze instantie een eenheidloze nul is of niet. |
|
|  | [isDefault()](#isDefault--) | Geeft aan of deze Length‑instantie een standaardwaarde heeft \\u2014 eenheidloos |
nul.
|
|  | [getUnitType()](#getUnitType--) | Retourneert een eenheidstype van deze Length‑instantie. |
|
|  | [isInteger()](#isInteger--) | Geeft aan of de numerieke waarde van deze Length‑instantie was |
oorspronkelijk gespecificeerd en opgeslagen als een integer (INT32) getal
|
|  | [isFloat()](#isFloat--) | Geeft aan of de numerieke waarde van deze Length‑instantie was |
oorspronkelijk gespecificeerd en opgeslagen als een float (FP32) getal
|
|  | [getFloatValue()](#getFloatValue--) | Retourneert een float‑numerieke waarde van de Length‑instantie. |
|
|  | [getIntegerValue()](#getIntegerValue--) | Retourneert een integer‑numerieke waarde van deze Length‑instantie, indien deze |
internaal opgeslagen is als een integer, of een uitzondering werpt, indien deze
oorspronkelijk opgeslagen is als een float‑getal.
|
|  | [isAbsolute()](#isAbsolute--) | Bepaalt of de lengte is opgegeven in absolute eenheden. |
|
|  | [isRelative()](#isRelative--) | Geeft aan of de lengte in relatieve eenheden is opgegeven. |
|
|  | [isZero()](#isZero--) | Bepaalt of de numerieke waarde van deze lengte nul is |
|
|  | [isNegative()](#isNegative--) | Bepaalt of de numerieke waarde van deze lengte negatief is |
|
|  | [isPositive()](#isPositive--) | Bepaalt of de numerieke waarde van deze lengte positief is |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | De waarde heeft een eenheidloos type, maar is geen nul - positief of negatief |
number
|
|  | [toPixel()](#toPixel--) | Converteert de lengte naar een aantal pixels, indien mogelijk. |
|
|  | [to(int unit)](#to-int-) | Converteert de lengte naar de opgegeven eenheid, indien mogelijk. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | Retourneert een tekenreeksrepresentatie van deze lengte in het opgegeven eenheidstype. |
|
|  | [serializeDefault()](#serializeDefault--) | Retourneert een tekenreeksrepresentatie van deze lengte in zijn oorspronkelijke native |
vorm (zoals deze is opgeslagen), zonder de lengtawaarde naar een andere te converteren
eenheidstype
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Definieert of deze waarde gelijk is aan de andere opgegeven lengte |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze lengte gelijk is aan het opgegeven object |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | Vermenigvuldigt de gegeven Length met de opgegeven factor |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Controleert de gelijkheid van de twee gegeven lengtes. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Controleert de ongelijkheid van de twee gegeven lengtes. |
|
|  | [hashCode()](#hashCode--) | Berekent en retourneert een hashcode van deze Length-instantie door te combineren |
hashcodes van de waarde en het eenheidstype
|
|  | [deepClone()](#deepClone--) | Retourneert een volledige kopie van deze Length-instantie |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Probeert de opgegeven eenheidsnaam te parseren en retourneert de overeenkomstige waarde van een |
Eenheid-enum.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | Probeert een opgegeven tekenreeks te parseren als een Length-waarde, inclusief zijn |
numerieke waarde en eenheidsnaam
|
|  | [parse(String input)](#parse-java.lang.String-) | Parseert en retourneert de opgegeven tekenreeks als een Length-waarde, inclusief zijn |
numerieke waarde en eenheidsnaam, of gooit een uitzondering bij falen.
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


Eenheidloze gehele nul - standaardwaarde, dezelfde als standaard zonder parameters
constructor


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


Maakt en retourneert een instantie van het type Length op basis van een opgegeven float‑getal
en eenheid


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | float | \>Elke float (FP32) getal |
|
|  | eenheid | int | Elk geldig eenheidstype |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


Maakt en retourneert een instantie van het type Length op basis van een opgegeven double‑getal
en eenheid


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | Elk double (FP64) getal, dat wordt geconverteerd naar float (FP32) |
|
|  | eenheid | int | Elk geldig eenheidstype |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


Maakt en retourneert een instantie van het type Length op basis van een opgegeven integer
getal en eenheid


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | Elk geheel getal |
|
|  | eenheid | int | Elk geldig eenheidstype |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


Bepaalt of deze instantie een eenheidsloos nul is of niet. Eenheidsloos nul
is de standaardwaarde van dit type. Hetzelfde als de IsDefault-eigenschap.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Geeft aan of deze Length‑instantie een standaardwaarde heeft \\u2014 eenheidloos
nul. Hetzelfde als de IsUnitlessZero-eigenschap.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


Retourneert een eenheidstype van deze Length‑instantie.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Geeft aan of de numerieke waarde van deze Length‑instantie was
oorspronkelijk gespecificeerd en opgeslagen als een integer (INT32) getal


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Geeft aan of de numerieke waarde van deze Length‑instantie was
oorspronkelijk gespecificeerd en opgeslagen als een float (FP32) getal


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Retourneert een float numerieke waarde van de Length‑instantie. Werpt nooit een
exceptie - converteert Integer‑waarde naar Float indien nodig.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Retourneert een integer‑numerieke waarde van deze Length‑instantie, indien deze
internaal opgeslagen is als een integer, of een uitzondering werpt, indien deze
oorspronkelijk opgeslagen is als een float‑getal.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Haalt op of de lengte is opgegeven in absolute eenheden. Zo'n lengte kan
worden geconverteerd naar pixels.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Haalt op of de lengte is opgegeven in relatieve eenheden. Zo'n lengte kan niet
worden geconverteerd naar pixels.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


Bepaalt of de numerieke waarde van deze lengte nul is


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


Bepaalt of de numerieke waarde van deze lengte negatief is


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


Bepaalt of de numerieke waarde van deze lengte positief is


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


De waarde heeft een eenheidloos type, maar is geen nul - positief of negatief
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


Converteert de lengte naar een aantal pixels, indien mogelijk. Als de huidige
eenheid relatief is, wordt er een exceptie gegooid.


**Returns:**
float - Het aantal pixels dat wordt weergegeven door de huidige lengte.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


Converteert de lengte naar de opgegeven eenheid, indien mogelijk. Als de huidige of
de opgegeven eenheid relatief is, wordt er een exceptie gegooid.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | eenheid | int | De eenheid om naar te converteren. |
|

**Returns:**
float - De waarde in de opgegeven eenheid van de huidige lengte.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


Retourneert een tekenreeksrepresentatie van deze lengte in het opgegeven eenheidstype.
Numerieke waarde wordt geconverteerd overeenkomstig de wijziging van het eenheidstype.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | eenheid | int | Gespecificeerde eenheid, waarnaar deze instantie moet worden geconverteerd vóór het serialiseren naar de string. Moet geldig zijn. Kan geen eenheidsloos zijn. |
|

**Returns:**
java.lang.String - Stringrepresentatie

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Retourneert een tekenreeksrepresentatie van deze lengte in zijn oorspronkelijke native
vorm (zoals deze is opgeslagen), zonder de lengtawaarde naar een andere te converteren
eenheidstype


**Returns:**
java.lang.String - String‑instantie

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


Definieert of deze waarde gelijk is aan de andere opgegeven lengte


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Andere instantie van het Length‑type |
|

**Returns:**
boolean - Waar als gelijk, anders onwaar

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze lengte gelijk is aan het opgegeven object


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere instantie van het Length-type, die is verpakt naar System.Object of een ander abstract type of interface |
|

**Returns:**
boolean - Waar als gelijk, anders onwaar

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


Vermenigvuldigt de gegeven Length met de opgegeven factor


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - vermenigvuldiger |
|
|  | factor | int | Willekeurige integer - factor |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


Controleert de gelijkheid van de twee gegeven lengtes.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | De linkse lengte-operand. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | De rechtse lengte-operand. |
|

**Returns:**
boolean - Waar als beide lengtes gelijk zijn, anders onwaar.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


Controleert de ongelijkheid van de twee gegeven lengtes.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | De linkse lengte-operand. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | De rechtse lengte-operand. |
|

**Returns:**
boolean - Waar als beide lengtes niet gelijk zijn, anders onwaar.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Berekent en retourneert een hashcode van deze Length-instantie door te combineren
hashcodes van de waarde en het eenheidstype


**Returns:**
int - Geheel getal

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


Retourneert een volledige kopie van deze Length-instantie


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


Probeert de opgegeven eenheidsnaam te parseren en retourneert de overeenkomstige waarde van een
Unit-enumeratie. Retourneert LengthUnit.Unitless als er geen passende LengthUnit gevonden kan worden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | unitName | java.lang.String | String, die een eenheidsnaam vertegenwoordigt |
|

**Returns:**
int - Waarde van Unit-enumeratie in elk geval, LengthUnit.Unitless wanneer er geen passende eenheid gevonden kan worden

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


Probeert een opgegeven tekenreeks te parseren als een Length-waarde, inclusief zijn
numerieke waarde en eenheidsnaam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | invoer | java.lang.String | Invoertekst, die geparseerd moet worden |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Uitvoerparameter, die een resultaat van het parseren bevat. Als het parseren niet succesvol is, bevat het een standaard Length-waarde \\u2014 een eenheidsloze nul. |
|

**Returns:**
boolean - Waar als het parseren succesvol is, onwaar als het niet succesvol is

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


Parseert en retourneert de opgegeven tekenreeks als een Length-waarde, inclusief zijn
numerieke waarde en eenheidsnaam, of gooit een uitzondering bij falen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | invoer | java.lang.String | Invoertekst, die geparseerd moet worden |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

