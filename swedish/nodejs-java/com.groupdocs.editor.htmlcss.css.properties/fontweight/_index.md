---
title: "FontWeight"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Font-weight‑egenskapen anger vikten eller fetstil för teckensnittet."
type: docs
weight: 12
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

Font-weight‑egenskapen anger vikten (eller fetstil) för teckensnittet. Tillgängliga vikter beror på den font-family som för närvarande är inställd.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Lighter](#Lighter) | En relativ font-weight som är lättare än föräldraelementet |
|
|  | [Bolder](#Bolder) | En relativ font-weight som är tyngre än föräldraelementet |
|
|  | [Normal](#Normal) | Normal font-weight. |
|
|  | [Bold](#Bold) | Fet font-weight. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isInitial()](#isInitial--) | Anger om detta font-size har ett initialvärde (Medium) |
|
|  | [getNumber()](#getNumber--) | Returnerar ett tal - heltalsvärde mellan 1 och 1000, inklusive, som beskriver fetheten i teckensnittet, eller kastar ett undantag om den aktuella fetheten inte är absolut utan relativ. |
|
|  | [isAbsolute()](#isAbsolute--) | Indikerar om detta font-weight‑instans lagrar ett absolut värde för vikten (fetheten) av teckensnittet, som ett heltal. |
|
|  | [isRelative()](#isRelative--) | Indikerar om detta font-weight‑instans lagrar ett relativt värde för vikten (fetheten) av teckensnittet – jämfört med fetheten i förälderelementet. |
|
|  | [getValue()](#getValue--) | Returnerar ett värde för detta font-weight som en sträng. |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Bestämmer om angivna FontWeight‑instanser är lika. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om detta FontWeight‑instans är lika med den angivna okastade. |
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod för denna instans. |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Kontrollerar om två \"FontWeight\"‑värden är lika. |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Kontrollerar om två \"FontWeight\"‑värden inte är lika. |
|
|  | [fromNumber(int number)](#fromNumber-int-) | Skapar ett font-weight från angivet tal. |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Försöker tolka en angiven sträng och returnera en giltig FontWeight‑instans vid lyckat resultat. |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


En relativ font-weight som är lättare än föräldraelementet


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


En relativ font-weight som är tyngre än föräldraelementet


### Normal {#Normal}
```
public static final FontWeight Normal
```


Normal font-weight. Samma som 400.


### Bold {#Bold}
```
public static final FontWeight Bold
```


Fet font-weight. Samma som 700.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Anger om detta font-size har ett initialvärde (Medium)


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Returnerar ett tal - heltalsvärde mellan 1 och 1000, inklusive, som beskriver fetheten i teckensnittet, eller kastar ett undantag om den aktuella fetheten inte är absolut utan relativ.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Indikerar om detta font-weight‑instans lagrar ett absolut värde för vikten (fetheten) av teckensnittet, som ett heltal.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Indikerar om detta font-weight‑instans lagrar ett relativt värde för vikten (fetheten) av teckensnittet – jämfört med fetheten i förälderelementet.


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Returnerar ett värde för detta font-weight som en sträng.


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Bestämmer om angivna FontWeight‑instanser är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Annan FontWeight‑instans för att kontrollera likhet. |
|

**Returns:**
boolean - true om de är lika, false om de är olika.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om detta FontWeight‑instans är lika med den angivna okastade.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Annan okastad FontWeight‑instans, kan vara null. |
|

**Returns:**
boolean - true om de är lika, false om de inte är lika, null eller av annan typ

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för denna instans.


**Returns:**
int - Hash-kod som ett signerat heltal

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


Kontrollerar om två \"FontWeight\"‑värden är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Första värdet att kontrollera |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Andra värdet att kontrollera |
|

**Returns:**
boolean - true om de är lika, false annars

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


Kontrollerar om två \"FontWeight\"‑värden inte är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Första värdet att kontrollera |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Andra värdet att kontrollera |
|

**Returns:**
boolean - false om de är lika, true annars

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Skapar ett font-weight från angivet tal.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | number | int | Unsigned integer, måste ligga inom intervallet [1..1000]. |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Försöker tolka en angiven sträng och returnera en giltig FontWeight‑instans vid lyckat resultat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | input | java.lang.String | Indata‑sträng att tolka. |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Giltigt FontWeight‑värde vid lyckat resultat eller #Normal.Normal vid misslyckande. |
|

**Returns:**
boolean - Lyckat (true) eller misslyckat (false) för tolkningen.

