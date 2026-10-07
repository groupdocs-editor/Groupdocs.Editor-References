---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt de typen van de tekstdecoratielijn onderstreping, underscore, overline en doorhaling (line-through) voor."
type: docs
weight: 13
url: /nl/java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Stelt typen van de tekstdecoratielijn voor: onderstrepen (underscore), overstrepen en doorhalen (strikethrough)

<br />

*** ** * ** ***

Immutable struct. Vergelijkbaar met de https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [None](#None) | Produceert geen tekstdecoratie. |
|
|  | [Underline](#Underline) | Elke regel tekst is onderstreept. |
|
|  | [Overline](#Overline) | Elke regel tekst heeft een lijn erboven. |
|
|  | [LineThrough](#LineThrough) | Elke regel tekst heeft een lijn door het midden. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isInitial()](#isInitial--) | Geeft aan of deze instantie een beginwaarde heeft \\u2014 Geen |
|
|  | [isUnderline()](#isUnderline--) | Geeft aan of onderstrepen (underscore) is ingeschakeld |
|
|  | [isOverline()](#isOverline--) | Geeft aan of overstrepen is ingeschakeld |
|
|  | [isLineThrough()](#isLineThrough--) | Geeft aan of doorhalen (strikethrough) is ingeschakeld |
|
|  | [getValue()](#getValue--) | Retourneert een waarde van alle vlaggen in deze instantie als tekst |
|
|  | [toString()](#toString--) | Retourneert een waarde van alle vlaggen in deze instantie als tekst |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Geeft aan of deze [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instantie gelijk is aan de opgegeven |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Geeft aan of deze [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instantie gelijk is aan de opgegeven niet-gecastte |
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode van deze instantie |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Controleert of twee "TextDecorationLineType" waarden gelijk zijn |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Controleert of twee "TextDecorationLineType" waarden niet gelijk zijn |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Maakt en retourneert een [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instantie met vlaggen, gedefinieerd door de opgegeven parameters |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Probeert een opgegeven tekenreeks te parseren en retourneert een geldige [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instantie |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Combineert (voegt samen) twee opgegeven lijntypen en produceert een nieuw resulterend lijntype, waarbij vlaggen worden samengevoegd (unite) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Trek het tweede opgegeven lijntype af van het eerste opgegeven lijntype en produceer een nieuw resulterend lijntype, waarbij alleen die vlaggen van de eerste operand aanwezig zijn die niet in de tweede operand worden gevonden (verschil) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Retourneert een intersectie tussen het eerste en tweede lijntype, waarbij alleen die vlaggen zijn ingeschakeld die simultaan in beide operand(en) zijn ingeschakeld. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Zet een specifiek byte (8-bit octet) om naar het overeenkomstige [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), gooit een uitzondering als de conversie ongeldig is |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


Produceert geen tekstdecoratie. Beginwaarde.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


Elke regel tekst is onderstreept.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


Elke regel tekst heeft een lijn erboven.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


Elke regel tekst heeft een lijn door het midden.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Geeft aan of deze instantie een beginwaarde heeft \\u2014 Geen


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Geeft aan of onderstrepen (underscore) is ingeschakeld


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Geeft aan of overstrepen is ingeschakeld


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Geeft aan of doorhalen (strikethrough) is ingeschakeld


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Retourneert een waarde van alle vlaggen in deze instantie als tekst


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Retourneert een waarde van alle vlaggen in deze instantie als tekst


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Geeft aan of deze [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instantie gelijk is aan de opgegeven


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Andere [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instantie |
|

**Returns:**
boolean -  true  als ze gelijk zijn,  false  anders

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Geeft aan of deze [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instantie gelijk is aan de opgegeven niet-gecastte


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | java.lang.Object | Andere [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instantie, gecast naar object |
|

**Returns:**
boolean -  true  als ze gelijk zijn,  false  anders

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode van deze instantie


**Returns:**
int - Ondertekende integer hashcode

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


Controleert of twee "TextDecorationLineType" waarden gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Eerste operand om te controleren |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Tweede operand om te controleren |
|

**Returns:**
boolean -  true  als ze gelijk zijn,  false  anders

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Controleert of twee "TextDecorationLineType" waarden niet gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Eerste operand om te controleren |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Tweede operand om te controleren |
|

**Returns:**
boolean -  true  als ze ongelijk zijn,  false  anders

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Maakt en retourneert een [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instantie met vlaggen, gedefinieerd door de opgegeven parameters


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | isUnderline | boolean | Bepaalt of een onderstreept vlag is ingeschakeld of niet |
|
|  | isOverline | boolean | Bepaalt of een overlijn vlag is ingeschakeld of niet |
|
|  | isLineThrough | boolean | Bepaalt of een doorstreping vlag is ingeschakeld of niet |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Probeert een opgegeven tekenreeks te parseren en retourneert een geldige [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | invoer | java.lang.String | Invoertekenreeks |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Resultaat. Als parseren ongeldig is, is het een #None.None waarde |
|

**Returns:**
boolean -  true  als parseren succesvol was,  false  bij falen

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Combineert (voegt samen) twee opgegeven lijntypen en produceert een nieuw resulterend lijntype, waarbij vlaggen worden samengevoegd (unite)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Eerste regeltype operand |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Tweede regeltype operand |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


Trek het tweede opgegeven lijntype af van het eerste opgegeven lijntype en produceer een nieuw resulterend lijntype, waarbij alleen die vlaggen van de eerste operand aanwezig zijn die niet in de tweede operand worden gevonden (verschil)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Eerste regeltype operand |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Tweede regeltype operand |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


Retourneert een intersectie tussen de eerste en tweede regeltypen, waarbij alleen die vlaggen zijn ingeschakeld die gelijktijdig in beide operand(en) zijn ingeschakeld. Heeft de hoogste prioriteit van alle operatoren (hoger dan unie en verschil)


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Eerste regeltype operand |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Tweede regeltype operand |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


Zet een specifiek byte (8-bit octet) om naar het overeenkomstige [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), gooit een uitzondering als de conversie ongeldig is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | octet | byte | Een 8-bit octet (bitveld), waarbij de eerste 5 bits nul zijn, terwijl de laatste 3 vlaggen aangeven |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
