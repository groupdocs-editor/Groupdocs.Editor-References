---
title: "QuoteType"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt Anführungszeichen dar – einfaches Anführungszeichen und doppeltes Anführungszeichen"
type: docs
weight: 10
url: /de/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

Stellt Anführungszeichen dar – einfaches Anführungszeichen (') und doppeltes Anführungszeichen (\")

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | Einfaches Anführungszeichen (U+0027 APOSTROPHE-Zeichen) |
|
|  | [DoubleQuote](#DoubleQuote) | Doppeltes Anführungszeichen (U+0022 QUOTATION MARK-Zeichen) |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getCode()](#getCode--) | Codepunkt des aktuellen Zeichens (U+0027 oder U+0022) |
|
|  | [getCharacter()](#getCharacter--) | Zeichen zum Einrahmen |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | HTML-codiertes Zeichen |
|
|  | [toString()](#toString--) | Gibt einen \"SingleQuote\"- oder \"DoubleQuote\"-String zurück, abhängig vom aktuellen Wert |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Gibt an, ob diese Instanz des Anführungszeichentyps gleich dem angegebenen ist |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Gibt an, ob diese Instanz des Anführungszeichentyps gleich dem angegebenen ungecasteten ist |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hashcode für dieses Zeichen zurück |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Überprüft, ob zwei \"QuoteType\"-Werte gleich sind |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Überprüft, ob zwei \"QuoteType\"-Werte ungleich sind |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Wandelt die angegebene [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)-Instanz in ein Zeichen um |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | Wandelt ein bestimmtes Zeichen in den entsprechenden [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) um, wirft eine Ausnahme, wenn das Casting ungültig ist |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


Einfaches Anführungszeichen (U+0027 APOSTROPHE-Zeichen)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


Doppeltes Anführungszeichen (U+0022 QUOTATION MARK-Zeichen)


### getCode() {#getCode--}
```
public final int getCode()
```


Codepunkt des aktuellen Zeichens (U+0027 oder U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Zeichen zum Einrahmen


**Returns:**
Zeichen
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


HTML-codiertes Zeichen


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Gibt einen \"SingleQuote\"- oder \"DoubleQuote\"-String zurück, abhängig vom aktuellen Wert


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


Gibt an, ob diese Instanz des Anführungszeichentyps gleich dem angegebenen ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Andere Instanz von QuoteType zum Prüfen |
|

**Returns:**
boolean – true, wenn gleich, false, wenn ungleich

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt an, ob diese Instanz des Anführungszeichentyps gleich dem angegebenen ungecasteten ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Nicht gecastetes Objekt, erwartet vom Typ [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |
|

**Returns:**
boolean – true, wenn gleich, false, wenn ungleich

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für dieses Zeichen zurück


**Returns:**
int - Hash-Code als vorzeichenbehaftete Ganzzahl

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


Überprüft, ob zwei \"QuoteType\"-Werte gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Erster zu prüfender Wert |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Zweiter zu prüfender Wert |
|

**Returns:**
boolean - true, wenn gleich, sonst false

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


Überprüft, ob zwei \"QuoteType\"-Werte ungleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Erster zu prüfender Wert |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | Zweiter zu prüfender Wert |
|

**Returns:**
boolean - false, wenn gleich, sonst true

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


Wandelt die angegebene [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)-Instanz in ein Zeichen um


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | QuoteType-Instanz zum Casten |
|

**Returns:**
Zeichen
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


Wandelt ein bestimmtes Zeichen in den entsprechenden [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) um, wirft eine Ausnahme, wenn das Casting ungültig ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Zeichen | Zeichen | Ein einzelnes Anführungszeichen (U+0027 APOSTROPHE) oder ein doppeltes Anführungszeichen (U+0022 QUOTATION MARK). Es wird eine Ausnahme ausgelöst, wenn ein anderes Zeichen angegeben wird. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
