---
title: "EbookSaveOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Consente di specificare opzioni personalizzate per generare e salvare il documento in tutti i formati e-Book supportati ePub, MOBI e AZW3."
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Consente di specificare opzioni personalizzate per la generazione e il salvataggio del documento in tutti i formati e-Book supportabili: ePub, MOBI e AZW3.

<br />

*** ** * ** ***

Formati e-Book supportati:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Pubblicazione elettronica)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle Format 8t)

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | Questo costruttore senza parametri crea una nuova istanza di EbookSaveOptions con formato di output ePub (può essere modificato successivamente tramite |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) proprietà)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Crea una nuova istanza di [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) con il formato di output e-Book obbligatorio specificato, mentre tutti gli altri parametri sono predefiniti. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Specifica il livello massimo di intestazioni al quale suddividere il file e-Book. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Specifica il livello massimo di intestazioni al quale suddividere il file e-Book. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Specifica se esportare le proprietà del documento integrate e personalizzate nel file risultante. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Specifica se esportare le proprietà del documento integrate e personalizzate nel file risultante. |
|
|  | [getOutputFormat()](#getOutputFormat--) | Specifica il formato del file e-Book risultante: IDPF ePub, MOBI o AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Specifica il formato del file e-Book risultante: IDPF ePub, MOBI o AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


Questo costruttore senza parametri crea una nuova istanza di EbookSaveOptions con formato di output ePub (può essere modificato successivamente tramite
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) proprietà)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


Crea una nuova istanza di [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) con il formato di output e-Book obbligatorio specificato, mentre tutti gli altri parametri sono predefiniti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | formato di output obbligatorio, in cui l'e-Book dovrebbe essere salvato |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Specifica il livello massimo di intestazioni al quale suddividere il file e-Book. Il valore predefinito è
2
.
Impostandolo a
0
disabiliterà la suddivisione, quindi tutto il contenuto dell'e-Book sarà incorporato in un unico pacchetto all'interno del file risultante.

<br />

*** ** * ** ***

Quando questa proprietà è impostata a un valore da 1 a 9, il documento verrà suddiviso nei paragrafi formattati utilizzando

**Heading 1**
,
**Heading 2**
,
**Heading 3**
stili ecc. fino al livello di intestazione specificato.

Per impostazione predefinita, solo
**Heading 1**
e
**Heading 2**
i paragrafi provocano la divisione del documento.
Impostare questa proprietà a zero (o a un valore inferiore a zero) impedirà del tutto la divisione del documento nei paragrafi di intestazione.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Specifica il livello massimo di intestazioni al quale suddividere il file e-Book. Il valore predefinito è
2
.
Impostandolo a
0
disabiliterà la suddivisione, quindi tutto il contenuto dell'e-Book sarà incorporato in un unico pacchetto all'interno del file risultante.

<br />

*** ** * ** ***

Quando questa proprietà è impostata a un valore da 1 a 9, il documento verrà suddiviso nei paragrafi formattati utilizzando

**Heading 1**
,
**Heading 2**
,
**Heading 3**
stili ecc. fino al livello di intestazione specificato.

Per impostazione predefinita, solo
**Heading 1**
e
**Heading 2**
i paragrafi provocano la divisione del documento.
Impostare questa proprietà a zero (o a un valore inferiore a zero) impedirà del tutto la divisione del documento nei paragrafi di intestazione.

<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Specifica se esportare le proprietà del documento integrate e personalizzate nel file risultante.
Il valore predefinito è
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Specifica se esportare le proprietà del documento integrate e personalizzate nel file risultante.
Il valore predefinito è
false
.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Specifica il formato del file e-Book risultante: IDPF ePub, MOBI o AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Specifica il formato del file e-Book risultante: IDPF ePub, MOBI o AZW3.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

