---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Contiene opzioni per la generazione e il salvataggio di documenti di foglio di calcolo basati su testo, CSV, basati su tabulazione, ecc., che utilizzano un delimitatore separatore"
type: docs
weight: 11
url: /it/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Contiene opzioni per generare e salvare documenti Spreadsheet basati su testo
(CSV, basati su tabulazione ecc.), che utilizzano un separatore (delimitatore)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | Questo costruttore senza parametri crea una nuova istanza di DelimitedTextSaveOptions con un separatore predefinito punto e virgola (;) (può essere modificato successivamente tramite |
Separatore
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) proprietà)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Crea un'istanza della classe di opzioni per testo delimitato con obbligatorio |
separatore (delimitatore)
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Consente di specificare un separatore di stringa (delimitatore) per basati su testo |
documenti Spreadsheet
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Consente di specificare un separatore di stringa (delimitatore) per basati su testo |
documenti Spreadsheet
|
|  | [getEncoding()](#getEncoding--) | Consente di impostare una codifica per il documento Spreadsheet basato su testo. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Consente di impostare una codifica per il documento Spreadsheet basato su testo. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Indica se le righe e le colonne vuote iniziali devono essere eliminate come |
come fa MS Excel
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Indica se le righe e le colonne vuote iniziali devono essere eliminate come |
come fa MS Excel
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Indica se i separatori devono essere emessi per le righe vuote. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Indica se i separatori devono essere emessi per le righe vuote. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


Questo costruttore senza parametri crea una nuova istanza di DelimitedTextSaveOptions con un separatore predefinito punto e virgola (;) (può essere modificato successivamente tramite
Separatore
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) proprietà)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Crea un'istanza della classe di opzioni per testo delimitato con obbligatorio
separatore (delimitatore)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | separatore | java.lang.String | Separatore stringa (delimitatore) per documenti Spreadsheet basati su testo |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Consente di specificare un separatore di stringa (delimitatore) per basati su testo
documenti Spreadsheet


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Consente di specificare un separatore di stringa (delimitatore) per basati su testo
documenti Spreadsheet


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Consente di impostare una codifica per il documento Spreadsheet basato su testo. Per
impostazione predefinita (e se non specificato) è UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Consente di impostare una codifica per il documento Spreadsheet basato su testo. Per
impostazione predefinita (e se non specificato) è UTF8.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Indica se le righe e le colonne vuote iniziali devono essere eliminate come
come fa MS Excel


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Indica se le righe e le colonne vuote iniziali devono essere eliminate come
come fa MS Excel


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Indica se i separatori devono essere emessi per le righe vuote. Predefinito
il valore è false, il che significa che il contenuto per la riga vuota sarà vuoto.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Indica se i separatori devono essere emessi per le righe vuote. Predefinito
il valore è false, il che significa che il contenuto per la riga vuota sarà vuoto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

