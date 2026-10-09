---
title: "MarkdownSaveOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti Markdown"
type: docs
weight: 24
url: /it/nodejs-java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Consente di specificare opzioni personalizzate per la generazione e il salvataggio di documenti Markdown

<br />

*** ** * ** ***

La classe MarkdownSaveOptions deve essere applicata dall'utente quando esiste un'istanza della classe EditableDocument, che contiene il contenuto di un documento modificato, ed è necessario salvare questo contenuto nel nuovo documento in formato Markdown.

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow specifica come allineare i contenuti nelle tabelle durante l'esportazione nel formato Markdown. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow specifica come allineare i contenuti nelle tabelle durante l'esportazione nel formato Markdown. |
|
|  | [getImagesFolder()](#getImagesFolder--) | Specifica la cartella fisica in cui le immagini vengono salvate durante l'esportazione di un documento in |
il formato Markdown.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | Specifica la cartella fisica in cui le immagini vengono salvate durante l'esportazione di un documento in |
il formato Markdown.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | Specifica se le immagini vengono salvate in formato Base64 nel file di output. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | Specifica se le immagini vengono salvate in formato Base64 nel file di output. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria.
Impostare questa opzione su
true
può ridurre significativamente il consumo di memoria durante la generazione di documenti di grandi dimensioni a scapito di un tempo di salvataggio più lento.
Il valore predefinito è
false
(l'ottimizzazione della memoria è disabilitata per garantire migliori prestazioni).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Abilita meccanismi di ottimizzazione della memoria durante la generazione del documento da HTML, il che degrada le prestazioni come costo della riduzione dell'uso della memoria.
Impostare questa opzione su
true
può ridurre significativamente il consumo di memoria durante la generazione di documenti di grandi dimensioni a scapito di un tempo di salvataggio più lento.
Il valore predefinito è
false
(l'ottimizzazione della memoria è disabilitata per garantire migliori prestazioni).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow specifica come allineare i contenuti nelle tabelle durante l'esportazione nel formato Markdown.
Il valore predefinito è [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Valore: l'allineamento del contenuto della tabella


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow specifica come allineare i contenuti nelle tabelle durante l'esportazione nel formato Markdown.
Il valore predefinito è [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Valore: l'allineamento del contenuto della tabella


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Specifica la cartella fisica in cui le immagini vengono salvate durante l'esportazione di un documento in
il formato Markdown. Il valore predefinito è null.

<br />

*** ** * ** ***

Se né l'ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) né l'ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) sono specificati dall'utente, allora GroupDocs.Editor cercherà di determinare autonomamente l'ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) e lo applicherà in caso di successo.

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Specifica la cartella fisica in cui le immagini vengono salvate durante l'esportazione di un documento in
il formato Markdown. Il valore predefinito è null.

<br />

*** ** * ** ***

Se né l'ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) né l'ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) sono specificati dall'utente, allora GroupDocs.Editor cercherà di determinare autonomamente l'ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) e lo applicherà in caso di successo.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


Specifica se le immagini vengono salvate in formato Base64 nel file di output. Il valore predefinito è
false
.

<br />

*** ** * ** ***

Quando questa proprietà è impostata su true, i dati delle immagini vengono esportati direttamente negli elementi immagine ![](../) e non vengono creati file separati. Questa proprietà, se impostata su true, ha priorità più alta rispetto alla proprietà MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


Specifica se le immagini vengono salvate in formato Base64 nel file di output. Il valore predefinito è
false
.

<br />

*** ** * ** ***

Quando questa proprietà è impostata su true, i dati delle immagini vengono esportati direttamente negli elementi immagine ![](../) e non vengono creati file separati. Questa proprietà, se impostata su true, ha priorità più alta rispetto alla proprietà MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

