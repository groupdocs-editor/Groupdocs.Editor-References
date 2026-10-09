---
title: "Längd"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar ett CSS-längdvärde i någon stödjande enhet inklusive procent och enhetstyp utan enhet."
type: docs
weight: 12
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

Representerar ett CSS-längdvärde i någon stödjande enhet, inklusive procent
och enhetstyp utan enhet. Värden kan vara heltal eller flyttal, negativa, noll och
positiva. Oföränderlig struktur.

*** ** * ** ***


Denna typ omfattar följande CSS-datatyper:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Length()](#Length--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | Enhetlös heltalsnoll - standardvärde, samma som standard utan parametrar |
konstruktor
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | Skapar och returnerar en instans av Length-typen med angivet flyttal |
och enhet
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | Skapar och returnerar en instans av Length-typen med angivet dubbelprecisionstal |
och enhet
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | Skapar och returnerar en instans av Length-typen med angivet heltal |
tal och enhet
|
|  | [isUnitlessZero()](#isUnitlessZero--) | Bestämmer om denna instans är ett enhetslöst nollvärde eller inte. |
|
|  | [isDefault()](#isDefault--) | Indikerar om detta Length-instans har ett standardvärde \u2014 enhetslös |
noll.
|
|  | [getUnitType()](#getUnitType--) | Returnerar en enhetstyp för detta Length-instans. |
|
|  | [isInteger()](#isInteger--) | Indikerar om det numeriska värdet för detta Length-instans var |
ursprungligen specificerat och lagrat som ett heltal (INT32) nummer
|
|  | [isFloat()](#isFloat--) | Indikerar om det numeriska värdet för detta Length-instans var |
ursprungligen specificerat och lagrat som ett flyttal (FP32) nummer
|
|  | [getFloatValue()](#getFloatValue--) | Returnerar ett flyttal-numeriskt värde för Length-instansen. |
|
|  | [getIntegerValue()](#getIntegerValue--) | Returnerar ett heltal-numeriskt värde för detta Length-instans, om det är |
internalt lagrat som ett heltal, eller kastar ett undantag, om det var
ursprungligen lagrat som ett flyttal.
|
|  | [isAbsolute()](#isAbsolute--) | Hämtar om längden är given i absoluta enheter. |
|
|  | [isRelative()](#isRelative--) | Hämtar om längden är given i relativa enheter. |
|
|  | [isZero()](#isZero--) | Bestämmer om det numeriska värde för denna längd är ett nolltal |
|
|  | [isNegative()](#isNegative--) | Bestämmer om det numeriska värdet för denna längd är ett negativt tal |
|
|  | [isPositive()](#isPositive--) | Bestämmer om det numeriska värdet för denna längd är ett positivt tal |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | Värdet har en enhetslös typ, men är inte noll - positivt eller negativt |
number
|
|  | [toPixel()](#toPixel--) | Konverterar längden till ett antal pixlar, om möjligt. |
|
|  | [to(int unit)](#to-int-) | Konverterar längden till den angivna enheten, om möjligt. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | Returnerar en strängrepresentation av denna längd i angiven enhetstyp. |
|
|  | [serializeDefault()](#serializeDefault--) | Returnerar en strängrepresentation av denna längd i dess ursprungliga inhemska |
form (som den lagras), utan att konvertera längdvärdet till någon annan
enhetstyp
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Definierar huruvida detta värde är lika med den andra angivna längden |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer huruvida denna längd är lika med specificerat objekt |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | Multiplicerar den givna Length med den angivna faktorn |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Kontrollerar likheten mellan de två givna längderna. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Kontrollerar ojämlikheten mellan de två givna längderna. |
|
|  | [hashCode()](#hashCode--) | Beräknar och returnerar en hashkod för detta Length‑objekt genom att kombinera |
hashkoder för värdet och enhetstypen
|
|  | [deepClone()](#deepClone--) | Returnerar en fullständig kopia av detta Length‑objekt |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Försöker tolka angivet enhetsnamn och returnera motsvarande värde av en |
Unit‑enum.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | Försöker tolka en specificerad sträng som ett Length‑värde, inklusive dess |
det numeriska värdet och enhetsnamnet
|
|  | [parse(String input)](#parse-java.lang.String-) | Tolkar och returnerar den specificerade strängen som ett Length‑värde, inklusive dess |
det numeriska värdet och enhetsnamnet, eller kastar ett undantag vid fel
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


Enhetlös heltalsnoll - standardvärde, samma som standard utan parametrar
konstruktor


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


Skapar och returnerar en instans av Length-typen med angivet flyttal
och enhet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | float | \>Vilken som helst float (FP32)-nummer |
|
|  | enhet | int | Vilken som helst giltig enhetstyp |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


Skapar och returnerar en instans av Length-typen med angivet dubbelprecisionstal
och enhet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Vilken som helst double (FP64)-nummer, som kommer att konverteras till float (FP32) |
|
|  | enhet | int | Vilken som helst giltig enhetstyp |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


Skapar och returnerar en instans av Length-typen med angivet heltal
tal och enhet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Vilket som helst heltal |
|
|  | enhet | int | Vilken som helst giltig enhetstyp |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


Bestämmer huruvida detta objekt är ett enhetslöst nollvärde eller inte. Enhetslöst nollvärde
är standardvärdet för den här typen. Samma som IsDefault-egenskapen.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indikerar om detta Length-instans har ett standardvärde \u2014 enhetslös
noll. Samma som IsUnitlessZero-egenskapen.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


Returnerar en enhetstyp för detta Length-instans.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Indikerar om det numeriska värdet för detta Length-instans var
ursprungligen specificerat och lagrat som ett heltal (INT32) nummer


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Indikerar om det numeriska värdet för detta Length-instans var
ursprungligen specificerat och lagrat som ett flyttal (FP32) nummer


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Returnerar ett float numeriskt värde för Length-instansen. Kastar aldrig en
undantag - konverterar Integer-värde till Float om nödvändigt.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Returnerar ett heltal-numeriskt värde för detta Length-instans, om det är
internalt lagrat som ett heltal, eller kastar ett undantag, om det var
ursprungligen lagrat som ett flyttal.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Hämtar om längden är given i absoluta enheter. En sådan längd kan vara
konverterad till pixlar.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Hämtar om längden är given i relativa enheter. En sådan längd kan inte vara
konverterad till pixlar.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


Bestämmer om det numeriska värde för denna längd är ett nolltal


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


Bestämmer om det numeriska värdet för denna längd är ett negativt tal


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


Bestämmer om det numeriska värdet för denna längd är ett positivt tal


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


Värdet har en enhetslös typ, men är inte noll - positivt eller negativt
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


Konverterar längden till ett antal pixlar, om möjligt. Om den aktuella
enheten är relativ, kastas ett undantag.


**Returns:**
float - Antalet pixlar som representeras av den aktuella längden.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


Konverterar längden till den angivna enheten, om möjligt. Om den aktuella eller
den angivna enheten är relativ, kastas ett undantag.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | enhet | int | Enheten att konvertera till. |
|

**Returns:**
float - Värdet i den angivna enheten för den aktuella längden.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


Returnerar en strängrepresentation av denna längd i angiven enhetstyp.
Numeriskt värde kommer att konverteras i enlighet med enhetstypens förändring.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | enhet | int | Angiven enhet, till vilken denna instans ska konverteras innan den serialiseras till strängen. Måste vara giltig. Får inte vara enhetslös. |
|

**Returns:**
java.lang.String - Strängrepresentation

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Returnerar en strängrepresentation av denna längd i dess ursprungliga inhemska
form (som den lagras), utan att konvertera längdvärdet till någon annan
enhetstyp


**Returns:**
java.lang.String - Stränginstans

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


Definierar huruvida detta värde är lika med den andra angivna längden


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Annan instans av Length-typ |
|

**Returns:**
boolean - Sant om lika, annars falskt

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer huruvida denna längd är lika med specificerat objekt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Annan instans av Length-typ, som är boxad till System.Object eller någon annan abstrakt typ eller gränssnitt |
|

**Returns:**
boolean - Sant om lika, annars falskt

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


Multiplicerar den givna Length med den angivna faktorn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - multiplikator |
|
|  | faktor | int | Godtyckligt heltal - faktor |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


Kontrollerar likheten mellan de två givna längderna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Den vänstra längdoperanden. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Den rätta längdoperanden. |
|

**Returns:**
boolean - Sant om båda längderna är lika, annars falskt.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


Kontrollerar ojämlikheten mellan de två givna längderna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Den vänstra längdoperanden. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Den rätta längdoperanden. |
|

**Returns:**
boolean - Sant om båda längderna inte är lika, annars falskt.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Beräknar och returnerar en hashkod för detta Length‑objekt genom att kombinera
hashkoder för värdet och enhetstypen


**Returns:**
int - Heltal

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


Returnerar en fullständig kopia av detta Length‑objekt


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


Försöker tolka angivet enhetsnamn och returnera motsvarande värde av en
Unit enum. Returnerar LengthUnit.Unitless om lämplig LengthUnit inte kan hittas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | unitName | java.lang.String | String som representerar ett enhetsnamn |
|

**Returns:**
int - Värde av Unit enum i alla fall, LengthUnit.Unitless när lämplig enhet inte kan hittas

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


Försöker tolka en specificerad sträng som ett Length‑värde, inklusive dess
det numeriska värdet och enhetsnamnet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | input | java.lang.String | Indatasträng som ska parsas |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Utdataparameter som innehåller resultatet av parsning. Om parsning misslyckas, innehåller ett standardvärde för Length \\u2014 en enhetslös noll. |
|

**Returns:**
boolean - Sant om parsning lyckas, falskt om den misslyckas

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


Tolkar och returnerar den specificerade strängen som ett Length‑värde, inklusive dess
det numeriska värdet och enhetsnamnet, eller kastar ett undantag vid fel


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | input | java.lang.String | Indatasträng som ska parsas |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

