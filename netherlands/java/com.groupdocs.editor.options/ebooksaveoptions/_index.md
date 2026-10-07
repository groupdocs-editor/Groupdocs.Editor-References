---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties op te geven voor het genereren en opslaan van het document in alle ondersteunde e‑Book‑formaten ePub, MOBI en AZW3."
type: docs
weight: 13
url: /nl/java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Staat toe aangepaste opties op te geven voor het genereren en opslaan van het document in alle ondersteunde e‑book‑formaten: ePub, MOBI en AZW3.

<br />

*** ** * ** ***

Ondersteunde e‑book‑formaten:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Elektronische publicatie)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle‑formaat 8t)

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | Deze parameterloze constructor maakt een nieuw exemplaar van EbookSaveOptions aan met ePub-uitvoerformaat (kan vervolgens worden aangepast via |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Maakt een nieuw exemplaar van [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) aan met het opgegeven verplichte e‑Book‑uitvoerformaat, terwijl alle andere parameters standaard zijn. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Specificeert het maximale niveau van koppen waarop het e‑Book‑bestand wordt gesplitst. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Specificeert het maximale niveau van koppen waarop het e‑Book‑bestand wordt gesplitst. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Specificeert of ingebouwde en aangepaste documenteigenschappen moeten worden geëxporteerd in het resulterende bestand. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Specificeert of ingebouwde en aangepaste documenteigenschappen moeten worden geëxporteerd in het resulterende bestand. |
|
|  | [getOutputFormat()](#getOutputFormat--) | Specificeert het formaat van het resulterende e‑Book‑bestand: IDPF ePub, MOBI of AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Specificeert het formaat van het resulterende e‑Book‑bestand: IDPF ePub, MOBI of AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


Deze parameterloze constructor maakt een nieuw exemplaar van EbookSaveOptions aan met ePub-uitvoerformaat (kan vervolgens worden aangepast via
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


Maakt een nieuw exemplaar van [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) aan met het opgegeven verplichte e‑Book‑uitvoerformaat, terwijl alle andere parameters standaard zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | verplicht uitvoerformaat, waarin het e‑Book moet worden opgeslagen |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Specificeert het maximale niveau van koppen waarop het e‑Book‑bestand moet worden gesplitst. Standaardwaarde is
2
.
Instellen op
0
zal splitsen uitschakelen, zodat alle inhoud van het e‑Book wordt opgenomen in één enkel pakket in het resulterende bestand.

<br />

*** ** * ** ***

Wanneer deze eigenschap wordt ingesteld op een waarde van 1 tot 9, wordt het document gesplitst bij alinea's die zijn opgemaakt met

**Heading 1**
,
**Heading 2**
,
**Heading 3**
etc. stijlen tot het opgegeven koppeniveau.

Standaard alleen
**Heading 1**
en
**Heading 2**
alinea's zorgen ervoor dat het document wordt gesplitst.
Het instellen van deze eigenschap op nul (of minder dan nul) zorgt ervoor dat het document helemaal niet wordt gesplitst bij kopalinea's.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Specificeert het maximale niveau van koppen waarop het e‑Book‑bestand moet worden gesplitst. Standaardwaarde is
2
.
Instellen op
0
zal splitsen uitschakelen, zodat alle inhoud van het e‑Book wordt opgenomen in één enkel pakket in het resulterende bestand.

<br />

*** ** * ** ***

Wanneer deze eigenschap wordt ingesteld op een waarde van 1 tot 9, wordt het document gesplitst bij alinea's die zijn opgemaakt met

**Heading 1**
,
**Heading 2**
,
**Heading 3**
etc. stijlen tot het opgegeven koppeniveau.

Standaard alleen
**Heading 1**
en
**Heading 2**
alinea's zorgen ervoor dat het document wordt gesplitst.
Het instellen van deze eigenschap op nul (of minder dan nul) zorgt ervoor dat het document helemaal niet wordt gesplitst bij kopalinea's.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Specificeert of ingebouwde en aangepaste documenteigenschappen moeten worden geëxporteerd in het resulterende bestand.
Standaardwaarde is
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Specificeert of ingebouwde en aangepaste documenteigenschappen moeten worden geëxporteerd in het resulterende bestand.
Standaardwaarde is
false
.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Specificeert het formaat van het resulterende e‑Book‑bestand: IDPF ePub, MOBI of AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Specificeert het formaat van het resulterende e‑Book‑bestand: IDPF ePub, MOBI of AZW3.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

