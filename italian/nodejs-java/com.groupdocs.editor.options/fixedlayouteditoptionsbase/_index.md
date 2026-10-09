---
title: "FixedLayoutEditOptionsBase"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Classe astratta di base per le opzioni di tutti i documenti con formati a layout fisso come PDF e XPS"
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

Classe astratta di base per le opzioni di tutti i documenti con formati a layout fisso come PDF e XPS

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | Ottiene o imposta il flag che indica se le immagini devono essere ignorate durante la conversione del documento a layout fisso di input in HTML risultante. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | Ottiene o imposta il flag che indica se le immagini devono essere ignorate durante la conversione del documento a layout fisso di input in HTML risultante. |
|
|  | [getPages()](#getPages--) | Consente di impostare un intervallo di pagine da elaborare. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | Consente di impostare un intervallo di pagine da elaborare. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Consente di abilitare (true) o disabilitare (false) l'impaginazione nel documento HTML risultante. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Consente di abilitare (true) o disabilitare (false) l'impaginazione nel documento HTML risultante. |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


Ottiene o imposta il flag che indica se le immagini devono essere ignorate durante la conversione del documento a layout fisso di input in HTML risultante. Il valore predefinito è false - le immagini vengono conservate.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


Ottiene o imposta il flag che indica se le immagini devono essere ignorate durante la conversione del documento a layout fisso di input in HTML risultante. Il valore predefinito è false - le immagini vengono conservate.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


Consente di impostare un intervallo di pagine da elaborare. Per impostazione predefinita tutte le pagine di un documento a layout fisso vengono elaborate.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


Consente di impostare un intervallo di pagine da elaborare. Per impostazione predefinita tutte le pagine di un documento a layout fisso vengono elaborate.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Consente di abilitare (true) o disabilitare (false) l'impaginazione nel documento HTML risultante. Per impostazione predefinita è disabilitata (false).

<br />

*** ** * ** ***

I documenti in formato a layout fisso (PDF e XPS in particolare) sono essenzialmente paginati in modo rigoroso, il loro contenuto ha un layout fisso e è diviso in pagine. Tuttavia l'HTML modificabile risultante può essere rappresentato sia in visualizzazione senza pagine sia in visualizzazione paginata.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Consente di abilitare (true) o disabilitare (false) l'impaginazione nel documento HTML risultante. Per impostazione predefinita è disabilitata (false).

<br />

*** ** * ** ***

I documenti in formato a layout fisso (PDF e XPS in particolare) sono essenzialmente paginati in modo rigoroso, il loro contenuto ha un layout fisso e è diviso in pagine. Tuttavia l'HTML modificabile risultante può essere rappresentato sia in visualizzazione senza pagine sia in visualizzazione paginata.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

