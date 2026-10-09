---
title: "EbookSaveOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour générer et enregistrer le document dans tous les formats de livre électronique pris en charge : ePub, MOBI et AZW3."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Permet de spécifier des options personnalisées pour générer et enregistrer le document dans tous les formats de livre numérique pris en charge : ePub, MOBI et AZW3.

<br />

*** ** * ** ***

Formats de livre électronique pris en charge :

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Publication électronique)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Format Kindle 8t)

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | Ce constructeur sans paramètres crée une nouvelle instance de EbookSaveOptions avec le format de sortie ePub (peut ensuite être modifié via |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) propriété)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Crée une nouvelle instance de [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) avec le format de sortie de livre électronique obligatoire spécifié, tandis que tous les autres paramètres sont par défaut. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Spécifie le niveau maximal de titres auquel diviser le fichier du livre électronique. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Spécifie le niveau maximal de titres auquel diviser le fichier du livre électronique. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées dans le fichier résultant. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées dans le fichier résultant. |
|
|  | [getOutputFormat()](#getOutputFormat--) | Spécifie le format du fichier de livre électronique résultant : IDPF ePub, MOBI ou AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Spécifie le format du fichier de livre électronique résultant : IDPF ePub, MOBI ou AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


Ce constructeur sans paramètres crée une nouvelle instance de EbookSaveOptions avec le format de sortie ePub (peut ensuite être modifié via
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) propriété)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


Crée une nouvelle instance de [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) avec le format de sortie de livre électronique obligatoire spécifié, tandis que tous les autres paramètres sont par défaut.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | format de sortie obligatoire, dans lequel le livre électronique doit être enregistré |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Spécifie le niveau maximal de titres auquel diviser le fichier du livre électronique. La valeur par défaut est
2
.
Le définir à
0
désactivera la division, de sorte que tout le contenu du livre électronique sera incorporé dans un seul paquet à l'intérieur du fichier résultant.

<br />

*** ** * ** ***

Lorsque cette propriété est définie sur une valeur de 1 à 9, le document sera divisé aux paragraphes formatés avec

**Heading 1**
,
**Heading 2**
,
**Heading 3**
etc. styles jusqu'au niveau de titre spécifié.

Par défaut, uniquement
**Heading 1**
et
**Heading 2**
les paragraphes provoquent la division du document.
Définir cette propriété à zéro (ou à une valeur inférieure à zéro) empêchera complètement le document d'être divisé aux paragraphes d'en-tête.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Spécifie le niveau maximal de titres auquel diviser le fichier du livre électronique. La valeur par défaut est
2
.
Le définir à
0
désactivera la division, de sorte que tout le contenu du livre électronique sera incorporé dans un seul paquet à l'intérieur du fichier résultant.

<br />

*** ** * ** ***

Lorsque cette propriété est définie sur une valeur de 1 à 9, le document sera divisé aux paragraphes formatés avec

**Heading 1**
,
**Heading 2**
,
**Heading 3**
etc. styles jusqu'au niveau de titre spécifié.

Par défaut, uniquement
**Heading 1**
et
**Heading 2**
les paragraphes provoquent la division du document.
Définir cette propriété à zéro (ou à une valeur inférieure à zéro) empêchera complètement le document d'être divisé aux paragraphes d'en-tête.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées dans le fichier résultant.
La valeur par défaut est
false
.


**Returns:**
booléen
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées dans le fichier résultant.
La valeur par défaut est
false
.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Spécifie le format du fichier de livre électronique résultant : IDPF ePub, MOBI ou AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Spécifie le format du fichier de livre électronique résultant : IDPF ePub, MOBI ou AZW3.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

