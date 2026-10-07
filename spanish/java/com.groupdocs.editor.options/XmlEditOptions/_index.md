---
title: "XmlEditOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para cargar documentos XML eXtensible Markup Language y convertirlos a HTML"
type: docs
weight: 51
url: /es/java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

Permite especificar opciones personalizadas para cargar XML (eXtensible Markup Language)
documentos y convertirlos a HTML

## Constructores

| Constructor | Descripción |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Codificación de caracteres del documento de texto, que se aplicará a su |
apertura.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Codificación de caracteres del documento de texto, que se aplicará a su |
apertura.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Permite habilitar o deshabilitar el mecanismo para corregir estructuras XML corruptas. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Permite habilitar o deshabilitar el mecanismo para corregir estructuras XML corruptas. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | Permite habilitar el algoritmo de reconocimiento de URI |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | Permite habilitar el algoritmo de reconocimiento de URI |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Permite habilitar el algoritmo de reconocimiento de direcciones de correo electrónico en atributos |
valores
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Permite habilitar el algoritmo de reconocimiento de direcciones de correo electrónico en atributos |
valores
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | Permite habilitar el truncamiento de espacios en blanco finales en la etiqueta interna |
texto.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | Permite habilitar el truncamiento de espacios en blanco finales en la etiqueta interna |
texto.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Permite especificar el tipo de comilla (simple o doble) para los valores de atributo. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Permite especificar el tipo de comilla (simple o doble) para los valores de atributo. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | Permite ajustar el resaltado XML, que se aplicará a la estructura XML cuando se represente en HTML. |
|
|  | [getFormatOptions()](#getFormatOptions--) | Permite ajustar el formato XML, que se aplicará a la estructura XML cuando se represente en HTML. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Codificación de caracteres del documento de texto, que se aplicará a su
apertura. Por defecto es nulo \u2014 se aplicará la codificación interna del documento.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Codificación de caracteres del documento de texto, que se aplicará a su
apertura. Por defecto es nulo \u2014 se aplicará la codificación interna del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Permite habilitar o deshabilitar el mecanismo para corregir estructuras XML corruptas.
Por defecto está deshabilitado (false).

*** ** * ** ***


Por defecto solo los documentos XML válidos y bien formados son
aceptables. Cuando esta opción está habilitada, GroupDocs.Editor intentará corregir
estructuras XML corruptas si es posible.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Permite habilitar o deshabilitar el mecanismo para corregir estructuras XML corruptas.
Por defecto está deshabilitado (false).

*** ** * ** ***


Por defecto solo los documentos XML válidos y bien formados son
aceptables. Cuando esta opción está habilitada, GroupDocs.Editor intentará corregir
estructuras XML corruptas si es posible.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


Permite habilitar el algoritmo de reconocimiento de URI


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


Permite habilitar el algoritmo de reconocimiento de URI


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Permite habilitar el algoritmo de reconocimiento de direcciones de correo electrónico en atributos
valores


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Permite habilitar el algoritmo de reconocimiento de direcciones de correo electrónico en atributos
valores


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


Permite habilitar el truncamiento de espacios en blanco finales en la etiqueta interna
texto. Por defecto está deshabilitado (false) \u2014 los espacios en blanco finales serán
preservados.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


Permite habilitar el truncamiento de espacios en blanco finales en la etiqueta interna
texto. Por defecto está deshabilitado (false) \u2014 los espacios en blanco finales serán
preservados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Permite especificar el tipo de comilla (simple o doble) para los valores de atributo. Las comillas dobles son predeterminadas.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Permite especificar el tipo de comilla (simple o doble) para los valores de atributo. Las comillas dobles son predeterminadas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


Permite ajustar el resaltado XML, que se aplicará a la estructura XML cuando se represente en HTML. Se utiliza el resaltado predeterminado y es ajustable. No puede ser nulo.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


Permite ajustar el formato XML, que se aplicará a la estructura XML cuando se represente en HTML. Se utiliza el formato predeterminado y es ajustable. No puede ser nulo.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
