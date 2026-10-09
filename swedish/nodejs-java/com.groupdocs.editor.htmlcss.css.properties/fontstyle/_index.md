---
title: "FontStyle"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Definierar hur teckensnittet ska stiliseras med ett normalt, kursivt eller snett teckensnitt från dess teckensnittsfamilj."
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

Definierar hur teckensnittet ska stylas med: en normal, kursiv eller snedställd stil från dess font-family.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Normal](#Normal) | Väljer ett teckensnitt som klassificeras som normalt inom en teckensnittsfamilj. |
|
|  | [Italic](#Italic) | Väljer ett teckensnitt som klassificeras som kursivt. |
|
|  | [Oblique](#Oblique) | Väljer ett teckensnitt som klassificeras som snett. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indikerar om detta font-style har ett initialt värde (Normal) |
|
|  | [getValue()](#getValue--) | Returnerar ett värde för denna teckensnittsstil som en sträng. |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Bestämmer om detta font-style‑instans är lika med den angivna. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om detta font-style‑instans är lika med den angivna okastade. |
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod för denna instans. |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Kontrollerar om två "FontStyle"-värden är lika. |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Kontrollerar om två "FontStyle"-värden inte är lika. |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | Försöker känna igen ett angivet nyckelord som ett korrekt nyckelordsvärde för 'font-style' och returnera det vid framgång eller NULL vid misslyckande. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


Väljer ett teckensnitt som klassificeras som normalt inom en teckensnittsfamilj. Initialt värde.


### Italic {#Italic}
```
public static final FontStyle Italic
```


Väljer ett teckensnitt som klassificeras som kursivt. Om ingen kursiv version av teckensnittet är tillgänglig, används en som klassificeras som snett istället. Om ingen av dem är tillgänglig, simuleras stilen artificiellt.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


Väljer ett teckensnitt som klassificeras som snett. Om ingen sned version av teckensnittet är tillgänglig, används en som klassificeras som kursivt istället. Om ingen av dem är tillgänglig, simuleras stilen artificiellt.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indikerar om detta font-style har ett initialt värde (Normal)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Returnerar ett värde för denna teckensnittsstil som en sträng.


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


Bestämmer om detta font-style‑instans är lika med den angivna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Annan font-style-instans |
|

**Returns:**
boolean - true om de är lika, false annars

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om detta font-style‑instans är lika med den angivna okastade.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Annan ocastad font-style-instans, kan vara null |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


Kontrollerar om två "FontStyle"-värden är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Första värdet att kontrollera |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Andra värdet att kontrollera |
|

**Returns:**
boolean - true om de är lika, false annars

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


Kontrollerar om två "FontStyle"-värden inte är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Första värdet att kontrollera |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Andra värdet att kontrollera |
|

**Returns:**
boolean - false om de är lika, true annars

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


Försöker känna igen ett angivet nyckelord som ett korrekt nyckelordsvärde för 'font-style' och returnera det vid framgång eller NULL vid misslyckande.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nyckelord | java.lang.String | Ett nyckelord att tolka |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Resultat, om tolkning lyckades, annars #Normal.Normal |
|

**Returns:**
boolean - true om tolkning lyckades, false annars

