---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för att läsa in XML eXtensible Markup Language‑dokument och konvertera dem till HTML"
type: docs
weight: 51
url: /sv/java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

Tillåter att ange anpassade alternativ för att läsa in XML (eXtensible Markup Language)
dokument och konvertera dem till HTML

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Teckenkodning för textdokumentet, som kommer att tillämpas för dess |
öppning.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Teckenkodning för textdokumentet, som kommer att tillämpas för dess |
öppning.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Tillåter att aktivera eller inaktivera mekanism för att reparera korrupt XML‑struktur. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Tillåter att aktivera eller inaktivera mekanism för att reparera korrupt XML‑struktur. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | Tillåter att aktivera URI‑igenkänningsalgoritm |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | Tillåter att aktivera URI‑igenkänningsalgoritm |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Tillåter att aktivera igenkänningsalgoritm för e‑postadresser i attribut |
värden
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Tillåter att aktivera igenkänningsalgoritm för e‑postadresser i attribut |
värden
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | Tillåter att aktivera borttagning av avslutande blanksteg i inner‑taggen |
text.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | Tillåter att aktivera borttagning av avslutande blanksteg i inner‑taggen |
text.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Tillåter att ange citatteckenstyp (enkla eller dubbla citattecken) för attributvärden. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Tillåter att ange citatteckenstyp (enkla eller dubbla citattecken) för attributvärden. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | Tillåter att justera XML‑markering som kommer att tillämpas på XML‑strukturen när den visas i HTML. |
|
|  | [getFormatOptions()](#getFormatOptions--) | Tillåter att justera XML‑formatering som kommer att tillämpas på XML‑strukturen när den visas i HTML. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Teckenkodning för textdokumentet, som kommer att tillämpas för dess
öppning. Standard är null \\u2014 intern dokumentkodning kommer att tillämpas.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Teckenkodning för textdokumentet, som kommer att tillämpas för dess
öppning. Standard är null \\u2014 intern dokumentkodning kommer att tillämpas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Tillåter att aktivera eller inaktivera mekanism för att reparera korrupt XML‑struktur.
Standard är inaktiverad (false).

*** ** * ** ***


Standard är att endast korrekta, giltiga, välformade XML‑dokument är
godtagbara. När detta alternativ är aktiverat kommer GroupDocs.Editor att försöka reparera
korrupt XML‑struktur om möjligt.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Tillåter att aktivera eller inaktivera mekanism för att reparera korrupt XML‑struktur.
Standard är inaktiverad (false).

*** ** * ** ***


Standard är att endast korrekta, giltiga, välformade XML‑dokument är
godtagbara. När detta alternativ är aktiverat kommer GroupDocs.Editor att försöka reparera
korrupt XML‑struktur om möjligt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


Tillåter att aktivera URI‑igenkänningsalgoritm


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


Tillåter att aktivera URI‑igenkänningsalgoritm


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Tillåter att aktivera igenkänningsalgoritm för e‑postadresser i attribut
värden


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Tillåter att aktivera igenkänningsalgoritm för e‑postadresser i attribut
värden


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


Tillåter att aktivera borttagning av avslutande blanksteg i inner‑taggen
text. Standard är inaktiverad (false) \\u2014 avslutande blanksteg kommer att
bevaras.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


Tillåter att aktivera borttagning av avslutande blanksteg i inner‑taggen
text. Standard är inaktiverad (false) \\u2014 avslutande blanksteg kommer att
bevaras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Tillåter att ange citatteckenstyp (enkla eller dubbla citattecken) för attributvärden. Dubbla citattecken är standard.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Tillåter att ange citatteckenstyp (enkla eller dubbla citattecken) för attributvärden. Dubbla citattecken är standard.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


Tillåter att justera XML‑markeringen som kommer att tillämpas på XML‑strukturen när den visas i HTML. Standardmarkering används och kan justeras. Får inte vara null.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


Tillåter att justera XML‑formateringen som kommer att tillämpas på XML‑strukturen när den visas i HTML. Standardformatering används och kan justeras. Får inte vara null.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
