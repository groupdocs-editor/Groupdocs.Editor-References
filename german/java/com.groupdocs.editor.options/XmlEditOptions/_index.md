---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Laden von XML (eXtensible Markup Language)-Dokumenten und deren Konvertierung in HTML"
type: docs
weight: 51
url: /de/java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

Ermöglicht das Angeben benutzerdefinierter Optionen zum Laden von XML (eXtensible Markup Language)
Dokumente und deren Konvertierung in HTML

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Zeichencodierung des Textdokuments, die für dessen |
Öffnen.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Zeichencodierung des Textdokuments, die für dessen |
Öffnen.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Ermöglicht das Aktivieren oder Deaktivieren des Mechanismus zur Korrektur beschädigter XML‑Strukturen. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Ermöglicht das Aktivieren oder Deaktivieren des Mechanismus zur Korrektur beschädigter XML‑Strukturen. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | Ermöglicht das Aktivieren des URI‑Erkennungsalgorithmus |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | Ermöglicht das Aktivieren des URI‑Erkennungsalgorithmus |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Ermöglicht das Aktivieren des Erkennungsalgorithmus für E‑Mail‑Adressen in Attribut |
Werten
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Ermöglicht das Aktivieren des Erkennungsalgorithmus für E‑Mail‑Adressen in Attribut |
Werten
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | Ermöglicht das Abschneiden von nachfolgenden Leerzeichen im Inner‑Tag |
Text.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | Ermöglicht das Abschneiden von nachfolgenden Leerzeichen im Inner‑Tag |
Text.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Ermöglicht das Angeben des Anführungszeichentyps (einfach oder doppelt) für Attributwerte. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Ermöglicht das Angeben des Anführungszeichentyps (einfach oder doppelt) für Attributwerte. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | Ermöglicht die Anpassung der XML‑Hervorhebung, die auf die XML‑Struktur angewendet wird, wenn sie in HTML dargestellt wird. |
|
|  | [getFormatOptions()](#getFormatOptions--) | Ermöglicht die Anpassung der XML‑Formatierung, die auf die XML‑Struktur angewendet wird, wenn sie in HTML dargestellt wird. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Zeichencodierung des Textdokuments, die für dessen
Öffnen. Standardmäßig ist null \\u2014 die interne Dokumentkodierung wird angewendet.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Zeichencodierung des Textdokuments, die für dessen
Öffnen. Standardmäßig ist null \\u2014 die interne Dokumentkodierung wird angewendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Ermöglicht das Aktivieren oder Deaktivieren des Mechanismus zur Korrektur beschädigter XML‑Strukturen.
Standardmäßig ist deaktiviert (false).

*** ** * ** ***


Standardmäßig sind nur ordnungsgemäße, gültige, wohlgeformte XML‑Dokumente
akzeptabel. Wenn diese Option aktiviert ist, versucht GroupDocs.Editor,
beschädigte XML‑Strukturen nach Möglichkeit zu reparieren.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Ermöglicht das Aktivieren oder Deaktivieren des Mechanismus zur Korrektur beschädigter XML‑Strukturen.
Standardmäßig ist deaktiviert (false).

*** ** * ** ***


Standardmäßig sind nur ordnungsgemäße, gültige, wohlgeformte XML‑Dokumente
akzeptabel. Wenn diese Option aktiviert ist, versucht GroupDocs.Editor,
beschädigte XML‑Strukturen nach Möglichkeit zu reparieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


Ermöglicht das Aktivieren des URI‑Erkennungsalgorithmus


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


Ermöglicht das Aktivieren des URI‑Erkennungsalgorithmus


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Ermöglicht das Aktivieren des Erkennungsalgorithmus für E‑Mail‑Adressen in Attribut
Werten


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Ermöglicht das Aktivieren des Erkennungsalgorithmus für E‑Mail‑Adressen in Attribut
Werten


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


Ermöglicht das Abschneiden von nachfolgenden Leerzeichen im Inner‑Tag
Text. Standardmäßig ist deaktiviert (false) \\u2014 nachfolgende Leerzeichen werden
beibehalten.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


Ermöglicht das Abschneiden von nachfolgenden Leerzeichen im Inner‑Tag
Text. Standardmäßig ist deaktiviert (false) \\u2014 nachfolgende Leerzeichen werden
beibehalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Ermöglicht die Angabe des Anführungszeichentyps (einfach oder doppelt) für Attributwerte. Doppelte Anführungszeichen sind Standard.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Ermöglicht die Angabe des Anführungszeichentyps (einfach oder doppelt) für Attributwerte. Doppelte Anführungszeichen sind Standard.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


Ermöglicht die Anpassung der XML-Hervorhebung, die auf die XML-Struktur angewendet wird, wenn sie in HTML dargestellt wird. Standardhervorhebung wird verwendet und ist anpassbar. Darf nicht null sein.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


Ermöglicht die Anpassung der XML-Formatierung, die auf die XML-Struktur angewendet wird, wenn sie in HTML dargestellt wird. Standardformatierung wird verwendet und ist anpassbar. Darf nicht null sein.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
