---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties op te geven voor het laden van XML eXtensible Markup Language‑documenten en deze om te zetten naar HTML"
type: docs
weight: 51
url: /nl/java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

Staat toe aangepaste opties op te geven voor het laden van XML (eXtensible Markup Language)
documenten en ze converteren naar de HTML

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Tekencodering van het tekstdocument, die zal worden toegepast op zijn |
openen.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Tekencodering van het tekstdocument, die zal worden toegepast op zijn |
openen.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Staat toe om het mechanisme voor het repareren van corrupte XML-structuren in te schakelen of uit te schakelen. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Staat toe om het mechanisme voor het repareren van corrupte XML-structuren in te schakelen of uit te schakelen. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | Staat toe om het URI-herkenningsalgoritme in te schakelen |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | Staat toe om het URI-herkenningsalgoritme in te schakelen |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Staat toe om het herkenningsalgoritme voor e-mailadressen in attributen in te schakelen |
waarden
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Staat toe om het herkenningsalgoritme voor e-mailadressen in attributen in te schakelen |
waarden
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | Staat toe om het afkappen van achterliggende spaties in de inner-tag in te schakelen |
tekst.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | Staat toe om het afkappen van achterliggende spaties in de inner-tag in te schakelen |
tekst.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Staat toe om het type aanhalingsteken (enkele of dubbele aanhalingstekens) voor attribuutwaarden op te geven. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Staat toe om het type aanhalingsteken (enkele of dubbele aanhalingstekens) voor attribuutwaarden op te geven. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | Staat toe om de XML-markering aan te passen, die wordt toegepast op de XML-structuur wanneer deze wordt weergegeven in HTML. |
|
|  | [getFormatOptions()](#getFormatOptions--) | Staat toe om de XML-opmaak aan te passen, die wordt toegepast op de XML-structuur wanneer deze wordt weergegeven in HTML. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Tekencodering van het tekstdocument, die zal worden toegepast op zijn
openen. Standaard is null \\u2014 interne documentcodering wordt toegepast.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Tekencodering van het tekstdocument, die zal worden toegepast op zijn
openen. Standaard is null \\u2014 interne documentcodering wordt toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Staat toe om het mechanisme voor het repareren van corrupte XML-structuren in te schakelen of uit te schakelen.
Standaard is uitgeschakeld (false).

*** ** * ** ***


Standaard zijn alleen correcte, geldige, goed gevormde XML-documenten
aanvaardbaar. Wanneer deze optie is ingeschakeld, zal GroupDocs.Editor proberen te repareren
corrupte XML-structuur indien mogelijk.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Staat toe om het mechanisme voor het repareren van corrupte XML-structuren in te schakelen of uit te schakelen.
Standaard is uitgeschakeld (false).

*** ** * ** ***


Standaard zijn alleen correcte, geldige, goed gevormde XML-documenten
aanvaardbaar. Wanneer deze optie is ingeschakeld, zal GroupDocs.Editor proberen te repareren
corrupte XML-structuur indien mogelijk.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


Staat toe om het URI-herkenningsalgoritme in te schakelen


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


Staat toe om het URI-herkenningsalgoritme in te schakelen


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Staat toe om het herkenningsalgoritme voor e-mailadressen in attributen in te schakelen
waarden


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Staat toe om het herkenningsalgoritme voor e-mailadressen in attributen in te schakelen
waarden


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


Staat toe om het afkappen van achterliggende spaties in de inner-tag in te schakelen
tekst. Standaard is uitgeschakeld (false) \\u2014 achterliggende spaties zullen
behouden.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


Staat toe om het afkappen van achterliggende spaties in de inner-tag in te schakelen
tekst. Standaard is uitgeschakeld (false) \\u2014 achterliggende spaties zullen
behouden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Staat toe om het type aanhalingsteken (enkele of dubbele aanhalingstekens) voor attribuutwaarden op te geven. Dubbele aanhalingstekens zijn standaard.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Staat toe om het type aanhalingsteken (enkele of dubbele aanhalingstekens) voor attribuutwaarden op te geven. Dubbele aanhalingstekens zijn standaard.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


Staat toe om de XML-markering aan te passen, die wordt toegepast op de XML-structuur wanneer deze wordt weergegeven in HTML. Standaardmarkering wordt gebruikt en is aanpasbaar. Mag niet null zijn.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


Staat toe om de XML-opmaak aan te passen, die wordt toegepast op de XML-structuur wanneer deze wordt weergegeven in HTML. Standaardopmaak wordt gebruikt en is aanpasbaar. Mag niet null zijn.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
