---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti XPS XML Paper Specifications"
type: docs
weight: 54
url: /it/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti XPS (XML Paper Specifications)

<br />

*** ** * ** ***

Un file XPS rappresenta file di layout di pagina basati su XML Paper Specifications creati da Microsoft. È stato sviluppato come sostituto del formato file EMF ed è simile al formato PDF, ma utilizza XML per il layout, l'aspetto e le informazioni di stampa di un documento.

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | Responsabile dell'incorporamento delle risorse di font nel documento XPS risultante, che sono utilizzate nel documento originale. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Responsabile dell'incorporamento delle risorse di font nel documento XPS risultante, che sono utilizzate nel documento originale.
Per impostazione predefinita non incorpora alcun font (NotEmbed).


**Returns:**
byte
### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria.
Impostare questa opzione su true può ridurre significativamente il consumo di memoria durante la generazione di documenti di grandi dimensioni a costo di un tempo di salvataggio più lento.
Il valore predefinito è false (l'ottimizzazione della memoria è disabilitata per garantire migliori prestazioni).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria.
Impostare questa opzione su true può ridurre significativamente il consumo di memoria durante la generazione di documenti di grandi dimensioni a costo di un tempo di salvataggio più lento.
Il valore predefinito è false (l'ottimizzazione della memoria è disabilitata per garantire migliori prestazioni).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

