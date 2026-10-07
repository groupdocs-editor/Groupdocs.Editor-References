---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti di testo semplice TXT"
type: docs
weight: 41
url: /it/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Consente di specificare opzioni personalizzate per la generazione e il salvataggio di testo semplice (TXT)
documenti

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Codifica dei caratteri del documento di testo, che verrà applicata al suo |
salvataggio
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Codifica dei caratteri del documento di testo, che verrà applicata al suo |
salvataggio
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Specifica se aggiungere segni bidirezionali prima di ogni sequenza BiDi quando |
esportare in formato di testo semplice.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Specifica se aggiungere segni bidirezionali prima di ogni sequenza BiDi quando |
esportazione in formato di testo semplice
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Specifica se il programma dovrebbe tentare di preservare la disposizione delle tabelle |
quando si salva nel formato di testo semplice.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Specifica se il programma dovrebbe tentare di preservare la disposizione delle tabelle |
quando si salva nel formato di testo semplice.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Codifica dei caratteri del documento di testo, che verrà applicata al suo
salvataggio


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Codifica dei caratteri del documento di testo, che verrà applicata al suo
salvataggio


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Specifica se aggiungere segni bidirezionali prima di ogni sequenza BiDi quando
esportare in formato di testo semplice. Il valore predefinito è 'false' \\u2014 non aggiungere segni BiDi.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Specifica se aggiungere segni bidirezionali prima di ogni sequenza BiDi quando
esportazione in formato di testo semplice


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Specifica se il programma dovrebbe tentare di preservare la disposizione delle tabelle
quando si salva nel formato di testo semplice. Il valore predefinito è false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Specifica se il programma dovrebbe tentare di preservare la disposizione delle tabelle
quando si salva nel formato di testo semplice. Il valore predefinito è false.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

