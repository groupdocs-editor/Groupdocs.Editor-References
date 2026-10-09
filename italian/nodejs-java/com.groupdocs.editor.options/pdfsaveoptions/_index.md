---
title: "PdfSaveOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti PDF Portable Document Format"
type: docs
weight: 31
url: /it/nodejs-java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

Consente di specificare opzioni personalizzate per la generazione e il salvataggio di PDF (Portable
Document Format) documenti

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPassword()](#getPassword--) | Password, che verrà applicata al documento PDF generato come password utente, richiesta per l'apertura. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Password, che verrà applicata al documento PDF generato come password utente, richiesta per l'apertura. |
|
|  | [getCompliance()](#getCompliance--) | Specifica il livello di conformità agli standard PDF per i documenti di output. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | Specifica il livello di conformità agli standard PDF per i documenti di output. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Responsabile dell'incorporamento delle risorse di carattere nel documento PDF risultante, che sono utilizzate nel documento originale. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Responsabile dell'incorporamento delle risorse di carattere nel documento PDF risultante, che sono utilizzate nel documento originale. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Password, che verrà applicata al documento PDF generato come password utente, richiesta per l'apertura.
Se NULL o vuoto, nessuna password verrà applicata al documento. Altrimenti, il documento sarà crittografato con RC4 (lunghezza chiave di 128 bit).
Per impostazione predefinita è NULL \\u2014 la password non viene applicata.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Password, che verrà applicata al documento PDF generato come password utente, richiesta per l'apertura.
Se NULL o vuoto, nessuna password verrà applicata al documento. Altrimenti, il documento sarà crittografato con RC4 (lunghezza chiave di 128 bit).
Per impostazione predefinita è NULL \\u2014 la password non viene applicata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Specifica il livello di conformità agli standard PDF per i documenti di output. Il valore predefinito è PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Specifica il livello di conformità agli standard PDF per i documenti di output. Il valore predefinito è PdfCompliance.Pdf17.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Responsabile dell'incorporamento delle risorse di carattere nel documento PDF risultante, che sono utilizzate nel documento originale. Per impostazione predefinita non incorpora alcun carattere (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Responsabile dell'incorporamento delle risorse di carattere nel documento PDF risultante, che sono utilizzate nel documento originale. Per impostazione predefinita non incorpora alcun carattere (NotEmbed).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria.
Impostare questa opzione su true può ridurre significativamente il consumo di memoria durante la generazione di documenti di grandi dimensioni, a costo di tempi di salvataggio più lunghi.
Il valore predefinito è false (l'ottimizzazione della memoria è disabilitata per ottenere migliori prestazioni).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria.
Impostare questa opzione su true può ridurre significativamente il consumo di memoria durante la generazione di documenti di grandi dimensioni, a costo di tempi di salvataggio più lunghi.
Il valore predefinito è false (l'ottimizzazione della memoria è disabilitata per ottenere migliori prestazioni).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

