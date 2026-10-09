---
title: "QuoteType"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar citattecken – enkelfnutt och dubbelfnutt"
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

Representerar citattecken – enkelfnutt (') och dubbelfnutt (\")

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | Enkelfnutt (U+0027 APOSTROF‑tecken) |
|
|  | [DoubleQuote](#DoubleQuote) | Dubbelcitat (U+0022 QUOTATION MARK-tecken) |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCode()](#getCode--) | Kodpunkt för det aktuella tecknet (U+0027 eller U+0022) |
|
|  | [getCharacter()](#getCharacter--) | Tecken att citera |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | HTML-kodat tecken |
|
|  | [toString()](#toString--) | Returnerar en "SingleQuote" eller "DoubleQuote"-sträng beroende på det aktuella värdet |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Indikerar om detta objekt av citattypen är lika med den angivna |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Indikerar om detta objekt av citattypen är lika med den angivna okastade |
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod för detta tecken |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Kontrollerar om två "QuoteType"-värden är lika |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Kontrollerar om två "QuoteType"-värden inte är lika |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Kastar angivet [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)-objekt till char |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | Kastar specifikt char till motsvarande [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), kastar undantag om kastning är ogiltig |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


Enkelfnutt (U+0027 APOSTROF‑tecken)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


Dubbelcitat (U+0022 QUOTATION MARK-tecken)


### getCode() {#getCode--}
```
public final int getCode()
```


Kodpunkt för det aktuella tecknet (U+0027 eller U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Tecken att citera


**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


HTML-kodat tecken


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returnerar en "SingleQuote" eller "DoubleQuote"-sträng beroende på det aktuella värdet


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


Indikerar om detta objekt av citattypen är lika med den angivna


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Annat objekt av QuoteType att kontrollera |
|

**Returns:**
boolean - true om de är lika, false om de är olika.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Indikerar om detta objekt av citattypen är lika med den angivna okastade


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Okastat objekt, förväntas vara av typen [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |
|

**Returns:**
boolean - true om de är lika, false om de är olika.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta tecken


**Returns:**
int - Hash-kod som ett signerat heltal

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


Kontrollerar om två "QuoteType"-värden är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Första värdet att kontrollera |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Andra värdet att kontrollera |
|

**Returns:**
boolean - true om de är lika, false annars

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


Kontrollerar om två "QuoteType"-värden inte är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Första värdet att kontrollera |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Andra värdet att kontrollera |
|

**Returns:**
boolean - false om de är lika, true annars

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Kastar angivet [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)-objekt till char


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Quote type-instans att kasta |
|

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


Kastar specifikt char till motsvarande [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype), kastar undantag om kastning är ogiltig


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | tecken | char | Ett enkelt citattecken (U+0027 APOSTROPHE) eller dubbelcitat (U+0022 QUOTATION MARK)-tecken. Undantag kastas om något annat tecken anges. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
