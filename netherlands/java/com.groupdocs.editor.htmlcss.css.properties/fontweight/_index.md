---
title: "FontWeight"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "De Font-weight eigenschap stelt het gewicht of de vetheid van het lettertype in."
type: docs
weight: 12
url: /nl/java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

De Font-weight eigenschap stelt het gewicht (of de vetheid) van het lettertype in. De beschikbare gewichten hangen af van de font-family die momenteel is ingesteld.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Lighter](#Lighter) | Een relatieve font-weight lichter dan het bovenliggende element |
|
|  | [Bolder](#Bolder) | Een relatieve font-weight zwaarder dan het bovenliggende element |
|
|  | [Normal](#Normal) | Normaal font-weight. |
|
|  | [Bold](#Bold) | Vet font-weight. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isInitial()](#isInitial--) | Geeft aan of deze font-size een initiële waarde heeft (Medium) |
|
|  | [getNumber()](#getNumber--) | Retourneert een getal - een gehele waarde tussen 1 en 1000, inclusief, die de dikte van het lettertype beschrijft, of gooit een uitzondering als de huidige dikte niet absoluut, maar relatief is. |
|
|  | [isAbsolute()](#isAbsolute--) | Geeft aan of deze font-weight instantie een absolute waarde van het gewicht (dikte) van het lettertype opslaat, als een geheel getal. |
|
|  | [isRelative()](#isRelative--) | Geeft aan of deze font-weight instantie een relatieve waarde van het gewicht (dikte) van het lettertype opslaat - vergeleken met de dikte van het bovenliggende element. |
|
|  | [getValue()](#getValue--) | Retourneert een waarde van deze font-weight als een string. |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Bepaalt of opgegeven FontWeight instanties gelijk zijn. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze FontWeight instantie gelijk is aan de opgegeven niet-gecastte. |
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode voor deze instantie. |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Controleert of twee "FontWeight" waarden gelijk zijn. |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Controleert of twee "FontWeight" waarden niet gelijk zijn. |
|
|  | [fromNumber(int number)](#fromNumber-int-) | Maakt een font-weight aan vanuit een opgegeven getal. |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Probeert een opgegeven string te parseren en retourneert bij succes een geldige FontWeight instantie. |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


Een relatieve font-weight lichter dan het bovenliggende element


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


Een relatieve font-weight zwaarder dan het bovenliggende element


### Normal {#Normal}
```
public static final FontWeight Normal
```


Normaal font weight. Hetzelfde als 400.


### Bold {#Bold}
```
public static final FontWeight Bold
```


Vet font weight. Hetzelfde als 700.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Geeft aan of deze font-size een initiële waarde heeft (Medium)


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Retourneert een getal - een gehele waarde tussen 1 en 1000, inclusief, die de dikte van het lettertype beschrijft, of gooit een uitzondering als de huidige dikte niet absoluut, maar relatief is.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Geeft aan of deze font-weight instantie een absolute waarde van het gewicht (dikte) van het lettertype opslaat, als een geheel getal.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Geeft aan of deze font-weight instantie een relatieve waarde van het gewicht (dikte) van het lettertype opslaat - vergeleken met de dikte van het bovenliggende element.


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Retourneert een waarde van deze font-weight als een string.


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Bepaalt of opgegeven FontWeight instanties gelijk zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Andere FontWeight instantie om de gelijkheid te controleren. |
|

**Returns:**
boolean - true als ze gelijk zijn, false als ze ongelijk zijn.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze FontWeight instantie gelijk is aan de opgegeven niet-gecastte.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere niet-gecastte FontWeight instantie, kan null zijn. |
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

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


Controleert of twee "FontWeight" waarden gelijk zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Eerste waarde om te controleren |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Tweede waarde om te controleren |
|

**Returns:**
boolean - true als ze gelijk zijn, false anders

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


Controleert of twee "FontWeight" waarden niet gelijk zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Eerste waarde om te controleren |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Tweede waarde om te controleren |
|

**Returns:**
boolean - false als ze gelijk zijn, true anders

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Maakt een font-weight aan vanuit een opgegeven getal.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | number | int | Unsigned integer, moet binnen het bereik [1..1000] liggen. |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Probeert een opgegeven string te parseren en retourneert bij succes een geldige FontWeight instantie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | invoer | java.lang.String | Invoerstring om te parseren. |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Geldige FontWeight waarde bij succes of #Normal.Normal bij falen. |
|

**Returns:**
boolean - Succes (true) of falen (false) van het parseren.

