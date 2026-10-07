---
title: "FontSize"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar en teckenstorlek som en speciell enhet eller ett längdvärde som specificerar teckenstorleken, historiskt bredden på den stora bokstaven M."
type: docs
weight: 10
url: /sv/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Representerar en teckenstorlek som en speciell enhet eller ett längdvärde, vilket specificerar storleken på teckensnittet (historiskt bredden på den stora "M").

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Medium](#Medium) | Mellanstorlek. |
|
|  | [XxSmall](#XxSmall) | Den mycket lilla absolute-size |
|
|  | [XSmall](#XSmall) | Den medelmåttigt lilla absolute-size |
|
|  | [Small](#Small) | Den normalt lilla absolute-size |
|
|  | [Large](#Large) | Den normalt stora absolute-size |
|
|  | [XLarge](#XLarge) | Den medelmåttigt stora absolute-size |
|
|  | [XxLarge](#XxLarge) | Den mycket stora absolute-size |
|
|  | [Larger](#Larger) | Större relative-size - teckensnittet blir större relativt föräldraelementets font-size, ungefär enligt förhållandet som används för att separera de ovanstående absolute-size‑nyckelorden. |
|
|  | [Smaller](#Smaller) | Mindre relative-size - teckensnittet blir mindre relativt föräldraelementets font-size, ungefär enligt förhållandet som används för att separera de ovanstående absolute-size‑nyckelorden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indikerar om detta font-size har ett initialt värde (Medium) |
|
|  | [getValue()](#getValue--) | Returnerar ett värde för denna font size som en sträng |
|
|  | [isLengthDefined()](#isLengthDefined--) | Anger om detta font-size är definierat med ett [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) värde |
|
|  | [getLength()](#getLength--) | Ett längdvärde, om detta font-size definierades med det, annars kastas ett undantag |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Anger om detta font-size är definierat med en absolut storlek som ett nyckelord, baserat på användarens standardfontstorlek (som är medium) |
|
|  | [isRelativeSize()](#isRelativeSize--) | Anger om detta font-size är definierat med en relativ storlek som ett nyckelord. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Bestämmer om detta font-size‑instans är lika med den angivna |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om detta font-size‑instans är lika med den angivna okastade |
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod för denna instans |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Kontrollerar om två "FontSize"‑värden är lika |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Kontrollerar om två "FontSize"‑värden inte är lika |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Skapar ett font-size från angiven längd |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Försöker känna igen ett angivet nyckelord som ett korrekt nyckelordsvärde för 'font-size' och returnerar det vid lyckat resultat eller NULL vid misslyckande. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Mediumstorlek. Initialvärde.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


Den mycket lilla absolute-size


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


Den medelmåttigt lilla absolute-size


### Small {#Small}
```
public static final FontSize Small
```


Den normalt lilla absolute-size


### Large {#Large}
```
public static final FontSize Large
```


Den normalt stora absolute-size


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


Den medelmåttigt stora absolute-size


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


Den mycket stora absolute-size


### Larger {#Larger}
```
public static final FontSize Larger
```


Större relative-size - teckensnittet blir större relativt föräldraelementets font-size, ungefär enligt förhållandet som används för att separera de ovanstående absolute-size‑nyckelorden.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Mindre relative-size - teckensnittet blir mindre relativt föräldraelementets font-size, ungefär enligt förhållandet som används för att separera de ovanstående absolute-size‑nyckelorden.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indikerar om detta font-size har ett initialt värde (Medium)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Returnerar ett värde för denna font size som en sträng


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Anger om detta font-size är definierat med ett [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) värde


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


Ett längdvärde, om detta font-size definierades med det, annars kastas ett undantag


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Anger om detta font-size är definierat med en absolut storlek som ett nyckelord, baserat på användarens standardfontstorlek (som är medium)


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Anger om detta font-size är definierat med en relativ storlek som ett nyckelord. Fonten kommer att vara större eller mindre i förhållande till föräldraelementets fontstorlek, ungefär enligt den ratio som används för att separera de absoluta storleksnyckelorden.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Bestämmer om detta font-size‑instans är lika med den angivna


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Annan font-size‑instans |
|

**Returns:**
boolean - true om de är lika, false annars

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om detta font-size‑instans är lika med den angivna okastade


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Annan okastad font-size‑instans, kan vara null |
|

**Returns:**
boolean - true om de är lika, false om de inte är lika, null eller av annan typ

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för denna instans


**Returns:**
int - Hash‑kod som ett signerat heltal

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Kontrollerar om två "FontSize"‑värden är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Första värdet att kontrollera |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Andra värdet att kontrollera |
|

**Returns:**
boolean - true om de är lika, false annars

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Kontrollerar om två "FontSize"‑värden inte är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Första värdet att kontrollera |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Andra värdet att kontrollera |
|

**Returns:**
boolean - false om de är lika, true annars

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Skapar ett font-size från angiven längd


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Ett längdvärde, får inte vara enhetslöst eller negativt |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


Försöker känna igen ett angivet nyckelord som ett korrekt nyckelordsvärde för 'font-size' och returnerar det vid lyckat resultat eller NULL vid misslyckande.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nyckelord | java.lang.String | Ett nyckelord att tolka |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Resultat, om parsning lyckades, annars #Medium.Medium |
|

**Returns:**
boolean - true om parsning lyckades, false annars

