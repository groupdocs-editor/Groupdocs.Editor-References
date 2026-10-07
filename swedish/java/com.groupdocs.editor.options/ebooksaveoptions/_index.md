---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara dokumentet i alla stödjade e-bokformat ePub, MOBI och AZW3."
type: docs
weight: 13
url: /sv/java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Tillåter att ange anpassade alternativ för att generera och spara dokumentet i alla stödbara e-bokformat: ePub, MOBI och AZW3.

<br />

*** ** * ** ***

Stödda e-bokformat:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Elektronisk publikation)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle-format 8t)

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | Denna parameterlösa konstruktor skapar en ny instans av EbookSaveOptions med ePub-utdataformat (kan sedan ändras via |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) egenskap)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Skapar en ny instans av [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) med angivet obligatoriskt e-bokutdataformat, medan alla andra parametrar är standard. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Anger den maximala nivån av rubriker där e-bokfilen ska delas. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Anger den maximala nivån av rubriker där e-bokfilen ska delas. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Anger om inbyggda och anpassade dokumentegenskaper ska exporteras i den resulterande filen. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Anger om inbyggda och anpassade dokumentegenskaper ska exporteras i den resulterande filen. |
|
|  | [getOutputFormat()](#getOutputFormat--) | Anger formatet för den resulterande e-bokfilen: IDPF ePub, MOBI eller AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Anger formatet för den resulterande e-bokfilen: IDPF ePub, MOBI eller AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


Denna parameterlösa konstruktor skapar en ny instans av EbookSaveOptions med ePub-utdataformat (kan sedan ändras via
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) egenskap)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


Skapar en ny instans av [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) med angivet obligatoriskt e-bokutdataformat, medan alla andra parametrar är standard.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | Obligatoriskt utdataformat, i vilket e-boken ska sparas |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Anger den maximala rubriknivån där e-bokfilen ska delas. Standardvärdet är
2
.
Att sätta den till
0
kommer att inaktivera delning, så allt innehåll i e-boken kommer att införlivas i ett enda paket i den resulterande filen.

<br />

*** ** * ** ***

När den här egenskapen är inställd på ett värde från 1 till 9, kommer dokumentet att delas vid stycken formaterade med

**Heading 1**
,
**Heading 2**
,
**Heading 3**
etc.-stilar upp till den angivna rubriknivån.

Som standard, endast
**Heading 1**
och
**Heading 2**
stycken får dokumentet att delas.
Att sätta den här egenskapen till noll (eller mindre än noll) kommer att göra att dokumentet inte delas vid rubrikstycken alls.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Anger den maximala rubriknivån där e-bokfilen ska delas. Standardvärdet är
2
.
Att sätta den till
0
kommer att inaktivera delning, så allt innehåll i e-boken kommer att införlivas i ett enda paket i den resulterande filen.

<br />

*** ** * ** ***

När den här egenskapen är inställd på ett värde från 1 till 9, kommer dokumentet att delas vid stycken formaterade med

**Heading 1**
,
**Heading 2**
,
**Heading 3**
etc.-stilar upp till den angivna rubriknivån.

Som standard, endast
**Heading 1**
och
**Heading 2**
stycken får dokumentet att delas.
Att sätta den här egenskapen till noll (eller mindre än noll) kommer att göra att dokumentet inte delas vid rubrikstycken alls.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Anger om inbyggda och anpassade dokumentegenskaper ska exporteras i den resulterande filen.
Standardvärdet är
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Anger om inbyggda och anpassade dokumentegenskaper ska exporteras i den resulterande filen.
Standardvärdet är
false
.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Anger formatet för den resulterande e-bokfilen: IDPF ePub, MOBI eller AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Anger formatet för den resulterande e-bokfilen: IDPF ePub, MOBI eller AZW3.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

