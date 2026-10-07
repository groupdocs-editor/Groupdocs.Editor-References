---
title: "FontSize"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt een font size voor als een speciale eenheid of een lengtemaat die de grootte van het font specificeert, historisch de breedte van de hoofdletter M."
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Stelt een lettergrootte voor als een speciale eenheid of een lengtemaat, die de grootte van het lettertype specificeert (historisch de breedte van de hoofdletter "M").

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Medium](#Medium) | Middelgrote grootte. |
|
|  | [XxSmall](#XxSmall) | De zeer kleine absolute-grootte |
|
|  | [XSmall](#XSmall) | De middelmatig kleine absolute-grootte |
|
|  | [Small](#Small) | De normaal kleine absolute-grootte |
|
|  | [Large](#Large) | De normaal grote absolute-grootte |
|
|  | [XLarge](#XLarge) | De middelmatig grote absolute-grootte |
|
|  | [XxLarge](#XxLarge) | De zeer grote absolute-grootte |
|
|  | [Larger](#Larger) | Grotere relatieve grootte - font zal groter zijn ten opzichte van de font-size van het bovenliggende element, ongeveer volgens de verhouding die wordt gebruikt om de absolute-grootte trefwoorden hierboven te scheiden. |
|
|  | [Smaller](#Smaller) | Kleinere relatieve grootte - font zal kleiner zijn ten opzichte van de font-size van het bovenliggende element, ongeveer volgens de verhouding die wordt gebruikt om de absolute-grootte trefwoorden hierboven te scheiden. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isInitial()](#isInitial--) | Geeft aan of deze font-size een initiële waarde heeft (Medium) |
|
|  | [getValue()](#getValue--) | Retourneert een waarde van deze font size als een string |
|
|  | [isLengthDefined()](#isLengthDefined--) | Geeft aan of deze font-size is gedefinieerd met een [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) waarde |
|
|  | [getLength()](#getLength--) | Een length-waarde, als deze font-size ermee is gedefinieerd, of gooit een uitzondering anders |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Geeft aan of deze font-size is gedefinieerd met een absolute grootte als sleutelwoord, gebaseerd op de standaard font-size van de gebruiker (die medium is) |
|
|  | [isRelativeSize()](#isRelativeSize--) | Geeft aan of deze font-size is gedefinieerd met een relatieve grootte als sleutelwoord. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Bepaalt of deze font-size instantie gelijk is aan de opgegeven |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze font-size instantie gelijk is aan de opgegeven niet-gecastte |
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode voor deze instantie. |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Controleert of twee "FontSize"-waarden gelijk zijn |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Controleert of twee "FontSize"-waarden niet gelijk zijn |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Maakt een font-size aan van een opgegeven length |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Probeert een opgegeven sleutelwoord te herkennen als een juiste sleutelwoordwaarde van de 'font-size' en retourneert het bij succes of NULL bij falen. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Medium grootte. Initiële waarde.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


De zeer kleine absolute-grootte


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


De middelmatig kleine absolute-grootte


### Small {#Small}
```
public static final FontSize Small
```


De normaal kleine absolute-grootte


### Large {#Large}
```
public static final FontSize Large
```


De normaal grote absolute-grootte


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


De middelmatig grote absolute-grootte


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


De zeer grote absolute-grootte


### Larger {#Larger}
```
public static final FontSize Larger
```


Grotere relatieve grootte - font zal groter zijn ten opzichte van de font-size van het bovenliggende element, ongeveer volgens de verhouding die wordt gebruikt om de absolute-grootte trefwoorden hierboven te scheiden.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Kleinere relatieve grootte - font zal kleiner zijn ten opzichte van de font-size van het bovenliggende element, ongeveer volgens de verhouding die wordt gebruikt om de absolute-grootte trefwoorden hierboven te scheiden.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Geeft aan of deze font-size een initiële waarde heeft (Medium)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Retourneert een waarde van deze font size als een string


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Geeft aan of deze font-size is gedefinieerd met een [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) waarde


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


Een length-waarde, als deze font-size ermee is gedefinieerd, of gooit een uitzondering anders


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Geeft aan of deze font-size is gedefinieerd met een absolute grootte als sleutelwoord, gebaseerd op de standaard font-size van de gebruiker (die medium is)


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Geeft aan of deze font-size is gedefinieerd met een relatieve grootte als sleutelwoord. Het lettertype zal groter of kleiner zijn ten opzichte van de font-size van het bovenliggende element, ongeveer volgens de verhouding die wordt gebruikt om de absolute-size sleutelwoorden te scheiden.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Bepaalt of deze font-size instantie gelijk is aan de opgegeven


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Andere font-size instantie |
|

**Returns:**
boolean - true als ze gelijk zijn, false anders

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze font-size instantie gelijk is aan de opgegeven niet-gecastte


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere niet-gecastte font-size instantie, kan null zijn |
|

**Returns:**
boolean - true als ze gelijk zijn, false als ze niet gelijk zijn, null of van een ander type

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor deze instantie.


**Returns:**
int - Hash-code als een ondertekend geheel getal

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Controleert of twee "FontSize"-waarden gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Eerste waarde om te controleren |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Tweede waarde om te controleren |
|

**Returns:**
boolean - true als ze gelijk zijn, false anders

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Controleert of twee "FontSize"-waarden niet gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Eerste waarde om te controleren |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Tweede waarde om te controleren |
|

**Returns:**
boolean - false als ze gelijk zijn, true anders

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Maakt een font-size aan van een opgegeven length


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Een length-waarde, mag niet eenheidloos of negatief zijn |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


Probeert een opgegeven sleutelwoord te herkennen als een juiste sleutelwoordwaarde van de 'font-size' en retourneert het bij succes of NULL bij falen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | trefwoord | java.lang.String | Een trefwoord om te parseren |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Resultaat, van het parseren was succesvol, of #Medium.Medium anders |
|

**Returns:**
boolean - true als parseren succesvol was, false anders

