---
title: "QuoteType"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt aanhalingstekens voor - enkele aanhaling en dubbele aanhaling"
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

Stelt aanhalingstekens voor – enkele aanhaling (') en dubbele aanhaling (\").

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | Enkele aanhaling (U+0027 APOSTROFE teken) |
|
|  | [DoubleQuote](#DoubleQuote) | Dubbele aanhaling (U+0022 AANHALINGSTEKEN teken) |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getCode()](#getCode--) | Codepunt van het huidige teken (U+0027 of U+0022) |
|
|  | [getCharacter()](#getCharacter--) | Teken om te citeren |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | HTML-gecodeerd teken |
|
|  | [toString()](#toString--) | Retourneert een "SingleQuote" of "DoubleQuote" string afhankelijk van de huidige waarde |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Geeft aan of deze instantie van het aanhalingstype gelijk is aan de opgegeven |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Geeft aan of deze instantie van het aanhalingstype gelijk is aan de opgegeven, niet-gecastte |
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode voor dit teken |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Controleert of twee "QuoteType" waarden gelijk zijn |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Controleert of twee "QuoteType"-waarden niet gelijk zijn |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Converteert opgegeven [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) instantie naar het teken |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | Converteert specifiek teken naar de overeenkomstige [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), gooit een uitzondering als de conversie ongeldig is |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


Enkele aanhaling (U+0027 APOSTROFE teken)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


Dubbele aanhaling (U+0022 AANHALINGSTEKEN teken)


### getCode() {#getCode--}
```
public final int getCode()
```


Codepunt van het huidige teken (U+0027 of U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Teken om te citeren


**Returns:**
teken
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


HTML-gecodeerd teken


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Retourneert een "SingleQuote" of "DoubleQuote" string afhankelijk van de huidige waarde


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


Geeft aan of deze instantie van het aanhalingstype gelijk is aan de opgegeven


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Andere instantie van QuoteType om te controleren |
|

**Returns:**
boolean - true als ze gelijk zijn, false als ze ongelijk zijn.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Geeft aan of deze instantie van het aanhalingstype gelijk is aan de opgegeven, niet-gecastte


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Niet-gecast object, verwacht van het type [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |
|

**Returns:**
boolean - true als ze gelijk zijn, false als ze ongelijk zijn.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor dit teken


**Returns:**
int - Hash-code als een ondertekend geheel getal

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


Controleert of twee "QuoteType" waarden gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Eerste waarde om te controleren |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Tweede waarde om te controleren |
|

**Returns:**
boolean - true als ze gelijk zijn, false anders

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


Controleert of twee "QuoteType"-waarden niet gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Eerste waarde om te controleren |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Tweede waarde om te controleren |
|

**Returns:**
boolean - false als ze gelijk zijn, true anders

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Converteert opgegeven [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) instantie naar het teken


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Quote-type instantie om te casten |
|

**Returns:**
teken
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


Converteert specifiek teken naar de overeenkomstige [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), gooit een uitzondering als de conversie ongeldig is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | teken | teken | Een enkel aanhalingsteken (U+0027 APOSTROPHE) of dubbel aanhalingsteken (U+0022 QUOTATION MARK) teken. Er wordt een uitzondering gegooid als een ander teken wordt opgegeven. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
