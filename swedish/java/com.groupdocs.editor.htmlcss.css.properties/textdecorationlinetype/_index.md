---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar typer av textdekorationlinjen underline underscore overline och line‑through strikethrough"
type: docs
weight: 13
url: /sv/java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Representerar typer av textdekoration: understrykning (underscore), överstrykning och genomstrykning (strikethrough).

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
|  | [isInitial()](#isInitial--) | Indikerar om den här instansen har ett initialt värde \\u2014 None |
|
|  | [isUnderline()](#isUnderline--) | Indikerar om understrykning (underscore) är aktiverad |
|
|  | [isOverline()](#isOverline--) | Indikerar om överlinje är aktiverad |
|
|  | [isLineThrough()](#isLineThrough--) | Indikerar om genomstrykning (strikethrough) är aktiverad |
|
|  | [getValue()](#getValue--) | Returnerar ett värde för alla flaggor i den här instansen som text |
|
|  | [toString()](#toString--) | Returnerar ett värde för alla flaggor i den här instansen som text |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Indikerar om den här [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)-instansen är lika med den angivna |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Indikerar om den här [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)-instansen är lika med den angivna utan typkonvertering |
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod för den här instansen |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Kontrollerar om två \"TextDecorationLineType\"-värden är lika |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Kontrollerar om två \"TextDecorationLineType\"-värden inte är lika |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Skapar och returnerar en [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)-instans med flaggor, definierade av de angivna parametrarna |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Försöker tolka en angiven sträng och returnera en giltig [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)-instans |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Kombinerar (slår samman) två angivna linjetyper och skapar en ny resulterande linjetyp, där flaggorna slås samman (union) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Subtraherar den andra angivna linjetypen från den första angivna linjetypen och skapar en ny resulterande linjetyp, där endast de flaggor från den första operand som inte finns i den andra operand (skillnad) är närvarande |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Returnerar en skärning mellan första och andra linjetyper, där endast de flaggor som är aktiverade samtidigt i båda operanderna är aktiverade. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Kastar en specifik byte (8-bitars oktett) till motsvarande [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), kastar ett undantag om konverteringen är ogiltig |
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


Indikerar om den här instansen har ett initialt värde \\u2014 None


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Indikerar om understrykning (underscore) är aktiverad


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


Returnerar ett värde för alla flaggor i den här instansen som text


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returnerar ett värde för alla flaggor i den här instansen som text


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Indikerar om den här [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)-instansen är lika med den angivna


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Annan [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)-instans |
|

**Returns:**
boolean -  true  om de är lika,  false  annars

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Indikerar om den här [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)-instansen är lika med den angivna utan typkonvertering


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | java.lang.Object | Annan [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)-instans, kastad till objekt |
|

**Returns:**
boolean -  true  om de är lika,  false  annars

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för den här instansen


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


Skapar och returnerar en [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)-instans med flaggor, definierade av de angivna parametrarna


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | isUnderline | boolean | Bestämmer om en understrykning flagga är aktiverad eller inte |
|
|  | isOverline | boolean | Bestämmer om en överstrykning flagga är aktiverad eller inte |
|
|  | isLineThrough | boolean | Bestämmer om en genomstrykning flagga är aktiverad eller inte |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Försöker tolka en angiven sträng och returnera en giltig [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)-instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | inmatning | java.lang.String | Indata sträng |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Resultat. Om parsning är ogiltig är det ett #None.None-värde |
|

**Returns:**
boolean -  true  om parsning lyckades,  false  vid fel

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Kombinerar (slår samman) två angivna linjetyper och skapar en ny resulterande linjetyp, där flaggorna slås samman (union)


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


Kastar en specifik byte (8-bitars oktett) till motsvarande [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), kastar ett undantag om konverteringen är ogiltig


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | oktet | byte | En 8-bitars oktet (bitfält), där de 5 första bitarna är noll, medan de sista 3 indikerar flaggor |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
