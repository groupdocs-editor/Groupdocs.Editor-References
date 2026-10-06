---
title: "EbookSaveOptions"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Permet de spécifier des options personnalisées pour générer et enregistrer le document dans tous les formats de livre numérique pris en charge ePub, MOBI et AZW3."
type: docs
weight: 13
url: /fr/java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Permet de spécifier des options personnalisées pour générer et enregistrer le document dans tous les formats e-Book pris en charge : ePub, MOBI et AZW3.

<br />

*** ** * ** ***

Formats de livre numérique pris en charge :

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
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Crée une nouvelle instance de [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) avec le format de sortie e-Book obligatoire spécifié, tandis que tous les autres paramètres sont par défaut |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | Spécifie le niveau maximal de titres auquel diviser le fichier e-Book. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | Spécifie le niveau maximal de titres auquel diviser le fichier e-Book. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées dans le fichier résultant. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Spécifie s'il faut exporter les propriétés de document intégrées et personnalisées dans le fichier résultant. |
|
|  | [getOutputFormat()](#getOutputFormat--) | Spécifie le format du fichier e-Book résultant : IDPF ePub, MOBI ou AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Spécifie le format du fichier e-Book résultant : IDPF ePub, MOBI ou AZW3. |
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


Crée une nouvelle instance de [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) avec le format de sortie e-Book obligatoire spécifié, tandis que tous les autres paramètres sont par défaut


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | format de sortie obligatoire, dans lequel le e-Book doit être enregistré |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


Spécifie le niveau maximal de titres auquel diviser le fichier e-Book. La valeur par défaut est
2
.
Définir à
0
désactivera le fractionnement, de sorte que tout le contenu de l'e‑Book sera incorporé dans un seul paquet dans le fichier résultant.

<br />

*** ** * ** ***

Lorsque cette propriété est définie sur une valeur de 1 à 9, le document sera découpé aux paragraphes formatés à l'aide de

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
les paragraphes provoquent le découpage du document.
Définir cette propriété à zéro (ou à une valeur inférieure à zéro) empêchera le document d'être découpé aux paragraphes de titre.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


Spécifie le niveau maximal de titres auquel diviser le fichier e-Book. La valeur par défaut est
2
.
Définir à
0
désactivera le fractionnement, de sorte que tout le contenu de l'e‑Book sera incorporé dans un seul paquet dans le fichier résultant.

<br />

*** ** * ** ***

Lorsque cette propriété est définie sur une valeur de 1 à 9, le document sera découpé aux paragraphes formatés à l'aide de

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
les paragraphes provoquent le découpage du document.
Définir cette propriété à zéro (ou à une valeur inférieure à zéro) empêchera le document d'être découpé aux paragraphes de titre.

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
boolean
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
| valeur | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Spécifie le format du fichier e-Book résultant : IDPF ePub, MOBI ou AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Spécifie le format du fichier e-Book résultant : IDPF ePub, MOBI ou AZW3.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

