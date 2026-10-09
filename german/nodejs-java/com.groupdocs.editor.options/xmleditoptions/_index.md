---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Ermöglicht das Angeben benutzerdefinierter Optionen zum Laden von XML eXtensible Markup Language-Dokumenten und deren Konvertierung in HTML"
type: docs
weight: 51
url: /de/nodejs-java/com.groupdocs.editor.options/xmleditoptions/
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
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Ermöglicht das Aktivieren oder Deaktivieren des Mechanismus zum Reparieren beschädigter XML-Strukturen. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Ermöglicht das Aktivieren oder Deaktivieren des Mechanismus zum Reparieren beschädigter XML-Strukturen. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | Ermöglicht das Aktivieren des URI-Erkennungsalgorithmus |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | Ermöglicht das Aktivieren des URI-Erkennungsalgorithmus |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Ermöglicht das Aktivieren des Erkennungsalgorithmus für E-Mail-Adressen im Attribut |
Werte
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Ermöglicht das Aktivieren des Erkennungsalgorithmus für E-Mail-Adressen im Attribut |
Werte
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | Ermöglicht das Aktivieren des Trunkierens von nachfolgenden Leerzeichen im inneren Tag |
Text.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | Ermöglicht das Aktivieren des Trunkierens von nachfolgenden Leerzeichen im inneren Tag |
Text.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Ermöglicht das Angeben des Anführungszeichentyps (einfaches oder doppeltes Anführungszeichen) für Attributwerte. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Ermöglicht das Angeben des Anführungszeichentyps (einfaches oder doppeltes Anführungszeichen) für Attributwerte. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | Ermöglicht das Anpassen der XML-Hervorhebung, die auf die XML-Struktur angewendet wird, wenn sie in HTML dargestellt wird. |
|
|  | [getFormatOptions()](#getFormatOptions--) | Ermöglicht das Anpassen der XML-Formatierung, die auf die XML-Struktur angewendet wird, wenn sie in HTML dargestellt wird. |
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
Öffnen. Standard ist null \u2014 interne Dokumentkodierung wird angewendet.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Zeichencodierung des Textdokuments, die für dessen
Öffnen. Standard ist null \u2014 interne Dokumentkodierung wird angewendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Ermöglicht das Aktivieren oder Deaktivieren des Mechanismus zum Reparieren beschädigter XML-Strukturen.
Standard ist deaktiviert (false).

*** ** * ** ***


Standard sind nur korrekte, gültige, wohlgeformte XML-Dokumente
akzeptabel. Wenn diese Option aktiviert ist, versucht GroupDocs.Editor, 
beschädigte XML-Strukturen, wenn möglich, zu reparieren.


**Returns:**
boolesch
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Ermöglicht das Aktivieren oder Deaktivieren des Mechanismus zum Reparieren beschädigter XML-Strukturen.
Standard ist deaktiviert (false).

*** ** * ** ***


Standard sind nur korrekte, gültige, wohlgeformte XML-Dokumente
akzeptabel. Wenn diese Option aktiviert ist, versucht GroupDocs.Editor, 
beschädigte XML-Strukturen, wenn möglich, zu reparieren.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


Ermöglicht das Aktivieren des URI-Erkennungsalgorithmus


**Returns:**
boolesch
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


Ermöglicht das Aktivieren des URI-Erkennungsalgorithmus


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Ermöglicht das Aktivieren des Erkennungsalgorithmus für E-Mail-Adressen im Attribut
Werte


**Returns:**
boolesch
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Ermöglicht das Aktivieren des Erkennungsalgorithmus für E-Mail-Adressen im Attribut
Werte


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


Ermöglicht das Aktivieren des Trunkierens von nachfolgenden Leerzeichen im inneren Tag
Text. Standard ist deaktiviert (false) \u2014 nachfolgende Leerzeichen werden
beibehalten.


**Returns:**
boolesch
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


Ermöglicht das Aktivieren des Trunkierens von nachfolgenden Leerzeichen im inneren Tag
Text. Standard ist deaktiviert (false) \u2014 nachfolgende Leerzeichen werden
beibehalten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

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


Ermöglicht die Anpassung der XML‑Hervorhebung, die auf die XML‑Struktur angewendet wird, wenn sie in HTML dargestellt wird. Standard‑Hervorhebung wird verwendet und ist anpassbar. Darf nicht null sein.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


Ermöglicht die Anpassung der XML‑Formatierung, die auf die XML‑Struktur angewendet wird, wenn sie in HTML dargestellt wird. Standard‑Formatierung wird verwendet und ist anpassbar. Darf nicht null sein.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
