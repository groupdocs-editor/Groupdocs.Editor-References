---
title: "XmlEditOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare opzioni personalizzate per il caricamento di documenti XML eXtensible Markup Language e la loro conversione in HTML"
type: docs
weight: 51
url: /it/nodejs-java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

Consente di specificare opzioni personalizzate per il caricamento di XML (eXtensible Markup Language)
documenti e la loro conversione in HTML

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Codifica dei caratteri del documento di testo, che verrà applicata al suo |
apertura.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Codifica dei caratteri del documento di testo, che verrà applicata al suo |
apertura.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Consente di abilitare o disabilitare il meccanismo per correggere la struttura XML corrotta. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Consente di abilitare o disabilitare il meccanismo per correggere la struttura XML corrotta. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | Consente di abilitare l'algoritmo di riconoscimento URI |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | Consente di abilitare l'algoritmo di riconoscimento URI |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Consente di abilitare l'algoritmo di riconoscimento per gli indirizzi email negli attributi |
valori
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Consente di abilitare l'algoritmo di riconoscimento per gli indirizzi email negli attributi |
valori
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | Consente di abilitare il troncamento degli spazi bianchi finali nel tag interno |
testo.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | Consente di abilitare il troncamento degli spazi bianchi finali nel tag interno |
testo.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Consente di specificare il tipo di virgolette (singole o doppie) per i valori degli attributi. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Consente di specificare il tipo di virgolette (singole o doppie) per i valori degli attributi. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | Consente di regolare l'evidenziazione XML, che verrà applicata alla struttura XML quando viene rappresentata in HTML. |
|
|  | [getFormatOptions()](#getFormatOptions--) | Consente di regolare la formattazione XML, che verrà applicata alla struttura XML quando viene rappresentata in HTML. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Codifica dei caratteri del documento di testo, che verrà applicata al suo
apertura. Per impostazione predefinita è null \\u2014 verrà applicata la codifica interna del documento.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Codifica dei caratteri del documento di testo, che verrà applicata al suo
apertura. Per impostazione predefinita è null \\u2014 verrà applicata la codifica interna del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Consente di abilitare o disabilitare il meccanismo per correggere la struttura XML corrotta.
Per impostazione predefinita è disabilitato (false).

*** ** * ** ***


Per impostazione predefinita solo documenti XML corretti, validi e ben formati sono
accettabili. Quando questa opzione è abilitata, GroupDocs.Editor cercherà di correggere
la struttura XML corrotta, se possibile.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Consente di abilitare o disabilitare il meccanismo per correggere la struttura XML corrotta.
Per impostazione predefinita è disabilitato (false).

*** ** * ** ***


Per impostazione predefinita solo documenti XML corretti, validi e ben formati sono
accettabili. Quando questa opzione è abilitata, GroupDocs.Editor cercherà di correggere
la struttura XML corrotta, se possibile.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


Consente di abilitare l'algoritmo di riconoscimento URI


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


Consente di abilitare l'algoritmo di riconoscimento URI


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Consente di abilitare l'algoritmo di riconoscimento per gli indirizzi email negli attributi
valori


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Consente di abilitare l'algoritmo di riconoscimento per gli indirizzi email negli attributi
valori


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


Consente di abilitare il troncamento degli spazi bianchi finali nel tag interno
testo. Per impostazione predefinita è disabilitato (false) \\u2014 gli spazi finali saranno
preservati.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


Consente di abilitare il troncamento degli spazi bianchi finali nel tag interno
testo. Per impostazione predefinita è disabilitato (false) \\u2014 gli spazi finali saranno
preservati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Consente di specificare il tipo di virgolette (singole o doppie) per i valori degli attributi. Le virgolette doppie sono predefinite.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Consente di specificare il tipo di virgolette (singole o doppie) per i valori degli attributi. Le virgolette doppie sono predefinite.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


Consente di regolare l'evidenziazione XML, che verrà applicata alla struttura XML quando è rappresentata in HTML. Viene utilizzata l'evidenziazione predefinita ed è regolabile. Non può essere null.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


Consente di regolare la formattazione XML, che verrà applicata alla struttura XML quando è rappresentata in HTML. Viene utilizzata la formattazione predefinita ed è regolabile. Non può essere null.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
