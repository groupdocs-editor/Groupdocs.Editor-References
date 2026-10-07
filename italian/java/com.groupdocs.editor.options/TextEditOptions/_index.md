---
title: "TextEditOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Consente di specificare opzioni personalizzate per il caricamento di documenti di testo semplice TXT"
type: docs
weight: 39
url: /it/java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Consente di specificare opzioni personalizzate per il caricamento di documenti plain text (TXT)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Codifica dei caratteri del documento di testo, che verrà applicata al suo |
apertura
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Codifica dei caratteri del documento di testo, che verrà applicata al suo |
apertura
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Consente di specificare come gli elementi di elenco numerato vengono riconosciuti quando il documento è |
importato dal formato di testo semplice.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Consente di specificare come gli elementi di elenco numerato vengono riconosciuti quando il documento è |
importato dal formato di testo semplice.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | Ottiene o imposta l'opzione preferita per la gestione degli spazi iniziali. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Ottiene o imposta l'opzione preferita per la gestione degli spazi iniziali. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | Ottiene o imposta l'opzione preferita per la gestione degli spazi finali. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Ottiene o imposta l'opzione preferita per la gestione degli spazi finali. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. |
|
|  | [getDirection()](#getDirection--) | Consente di specificare la direzione del flusso di testo nel testo semplice di input |
documento.
|
|  | [setDirection(int value)](#setDirection-int-) | Consente di specificare la direzione del flusso di testo nel testo semplice di input |
documento.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Codifica dei caratteri del documento di testo, che verrà applicata al suo
apertura


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Codifica dei caratteri del documento di testo, che verrà applicata al suo
apertura


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Consente di specificare come gli elementi di elenco numerato vengono riconosciuti quando il documento è
importato dal formato di testo semplice. Il valore predefinito è true.


*** ** * ** ***

Se questa opzione è impostata su false, l'algoritmo di riconoscimento degli elenchi rileva i paragrafi di elenco quando i numeri degli elenchi terminano con un punto, una parentesi chiusa o simboli di elenco puntato (come \"\\u2022\", \"\\*\", \"-\" o \"o\"). Se questa opzione è impostata su true, gli spazi bianchi sono anche usati come delimitatori dei numeri di elenco: l'algoritmo di riconoscimento degli elenchi per la numerazione in stile arabo (1., 1.1.2.) utilizza sia gli spazi bianchi sia il punto (\".\") come simboli.

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Consente di specificare come gli elementi di elenco numerato vengono riconosciuti quando il documento è
importato dal formato di testo semplice. Il valore predefinito è true.


*** ** * ** ***

Se questa opzione è impostata su false, l'algoritmo di riconoscimento degli elenchi rileva i paragrafi di elenco quando i numeri degli elenchi terminano con un punto, una parentesi chiusa o simboli di elenco puntato (come \"\\u2022\", \"\\*\", \"-\" o \"o\"). Se questa opzione è impostata su true, gli spazi bianchi sono anche usati come delimitatori dei numeri di elenco: l'algoritmo di riconoscimento degli elenchi per la numerazione in stile arabo (1., 1.1.2.) utilizza sia gli spazi bianchi sia il punto (\".\") come simboli.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Ottiene o imposta l'opzione preferita per la gestione degli spazi iniziali. Per impostazione predefinita
converte gli spazi iniziali in rientro a sinistra.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Ottiene o imposta l'opzione preferita per la gestione degli spazi iniziali. Per impostazione predefinita
converte gli spazi iniziali in rientro a sinistra.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Ottiene o imposta l'opzione preferita per la gestione degli spazi finali. Per impostazione predefinita
tronca tutti gli spazi finali.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Ottiene o imposta l'opzione preferita per la gestione degli spazi finali. Per impostazione predefinita
tronca tutti gli spazi finali.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. By
Il valore predefinito è disabilitato (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Consente di abilitare o disabilitare l'impaginazione nel documento HTML risultante. By
Il valore predefinito è disabilitato (false).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Consente di specificare la direzione del flusso di testo nel testo semplice di input
documento. Per impostazione predefinita è da sinistra a destra.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Consente di specificare la direzione del flusso di testo nel testo semplice di input
documento. Per impostazione predefinita è da sinistra a destra.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

