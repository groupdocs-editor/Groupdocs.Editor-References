---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar typer av textdekorationer: underline, underscore, overline och line-through (strikethrough)."
type: docs
weight: 13
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Representerar typer av textdekoration: underline (understrykning), overline och line-through (genomstrykning)

<br />

*** ** * ** ***

Oföränderlig struct. Liknande https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [None](#None) | Producerar ingen textdekoration. |
|
|  | [Underline](#Underline) | Varje textrad är understruken. |
|
|  | [Overline](#Overline) | Varje textrad har en linje ovanför den. |
|
|  | [LineThrough](#LineThrough) | Varje textrad har en linje genom mitten. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indikerar om detta objekt har ett initialt värde — Ingen |
|
|  | [isUnderline()](#isUnderline--) | Indikerar om understrykning (understreck) är aktiverad |
|
|  | [isOverline()](#isOverline--) | Indikerar om överlinje är aktiverad |
|
|  | [isLineThrough()](#isLineThrough--) | Indikerar om genomstrykning (strikethrough) är aktiverad |
|
|  | [getValue()](#getValue--) | Returnerar ett värde för alla flaggor i detta objekt som text |
|
|  | [toString()](#toString--) | Returnerar ett värde för alla flaggor i detta objekt som text |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Indikerar om detta [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) objekt är lika med det angivna |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Indikerar om detta [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) objekt är lika med det angivna utan typkonvertering |
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Kontrollerar om två \"TextDecorationLineType\"-värden är lika |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Kontrollerar om två \"TextDecorationLineType\"-värden inte är lika |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Skapar och returnerar ett [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) objekt med flaggor, definierade av de angivna parametrarna |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Försöker tolka en angiven sträng och returnera ett giltigt [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) objekt |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Kombinerar (slår ihop) två angivna linjetyper och skapar en ny resulterande linjetyp, där flaggorna slås ihop (union) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Subtraherar den andra angivna linjetypen från den första angivna linjetypen och skapar en ny resulterande linjetyp, där endast de flaggor från den första operand som inte finns i den andra operand (skillnad) är närvarande |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Returnerar en intersektion mellan första och andra linjetyper, där endast de flaggor som är aktiverade i båda operanderna samtidigt är aktiverade. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Omvandlar en specifik byte (8-bitars oktett) till motsvarande [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), kastar ett undantag om omvandlingen är ogiltig |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


Producerar ingen textdekoration. Initialt värde.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


Varje textrad är understruken.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


Varje textrad har en linje ovanför den.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


Varje textrad har en linje genom mitten.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indikerar om detta objekt har ett initialt värde — Ingen


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Indikerar om understrykning (understreck) är aktiverad


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Indikerar om överlinje är aktiverad


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Indikerar om genomstrykning (strikethrough) är aktiverad


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Returnerar ett värde för alla flaggor i detta objekt som text


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returnerar ett värde för alla flaggor i detta objekt som text


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Indikerar om detta [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) objekt är lika med det angivna


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Annat [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) objekt |
|

**Returns:**
boolean -  true  om de är lika,  false  annars

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Indikerar om detta [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) objekt är lika med det angivna utan typkonvertering


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | java.lang.Object | Annat [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) objekt, kastat till objekt |
|

**Returns:**
boolean -  true  om de är lika,  false  annars

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt


**Returns:**
int - Signerad heltals hashkod

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


Kontrollerar om två \"TextDecorationLineType\"-värden är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Första operand att kontrollera |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Andra operand att kontrollera |
|

**Returns:**
boolean -  true  om de är lika,  false  annars

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Kontrollerar om två \"TextDecorationLineType\"-värden inte är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Första operand att kontrollera |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Andra operand att kontrollera |
|

**Returns:**
boolean -  true  om de är olika,  false  annars

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Skapar och returnerar ett [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) objekt med flaggor, definierade av de angivna parametrarna


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | isUnderline | boolean | Bestämmer om ett understrykningflagg är aktiverat eller inte |
|
|  | isOverline | boolean | Bestämmer om ett överstrykningflagg är aktiverat eller inte |
|
|  | isLineThrough | boolean | Bestämmer om ett genomstrykningflagg är aktiverat eller inte |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Försöker tolka en angiven sträng och returnera ett giltigt [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) objekt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | input | java.lang.String | Indatasträng |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Resultat. Om parsning är ogiltig, är det ett #None.None‑värde |
|

**Returns:**
boolean -  true  om parsning lyckades,  false  vid fel

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Kombinerar (slår ihop) två angivna linjetyper och skapar en ny resulterande linjetyp, där flaggorna slås ihop (union)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Första radtyp operand |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Andra radtyp operand |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


Subtraherar den andra angivna linjetypen från den första angivna linjetypen och skapar en ny resulterande linjetyp, där endast de flaggor från den första operand som inte finns i den andra operand (skillnad) är närvarande


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Första radtyp operand |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Andra radtyp operand |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


Returnerar en skärning mellan första och andra radtyper, där endast de flaggor som är aktiverade samtidigt i båda operanderna är påslagna. Har högsta prioritet bland alla operatorer (högre än union och differens)


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Första radtyp operand |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Andra radtyp operand |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


Omvandlar en specifik byte (8-bitars oktett) till motsvarande [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), kastar ett undantag om omvandlingen är ogiltig


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | oktet | byte | Ett 8‑bitars oktet (bitfält), där de 5 första bitarna är noll, medan de sista 3 indikerar flaggor |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
