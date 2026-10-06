---
title: "WordProcessingFormats"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Encapsule tous les formats de traitement de texte."
type: docs
weight: 17
url: /fr/java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

Regroupe tous les formats de traitement de texte. Inclut les types de fichiers suivants :
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
En savoir plus sur les formats de traitement de texte [ici](../https://wiki.fileformat.com/word-processing).

Les codes MIME sont récupérés à partir des ressources fournies :
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## Champs

| Champ | Description |
| --- | --- |
|  | [Doc](#Doc) | MS Word 97-2007 Binary File Format (DOC) représente les documents générés par Microsoft Word ou d’autres documents de traitement de texte au format binaire. |
|
|  | [Docx](#Docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) est un format bien connu pour les documents Microsoft Word. |
|
|  | [Dot](#Dot) | MS Word 97-2007 Template (DOT) sont des fichiers modèle créés par Microsoft Word pour disposer de paramètres préformatés en vue de la génération de futurs fichiers DOC ou DOCX. |
|
|  | [Docm](#Docm) | Les fichiers Office Open XML WordProcessingML Macro-Enabled Document (DOCM) sont des documents générés par Microsoft Word 2007 ou version ultérieure avec la capacité d’exécuter des macros. |
|
|  | [Dotx](#Dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) sont des fichiers modèle créés par Microsoft Word pour disposer de paramètres préformatés en vue de la génération de futurs fichiers DOCX. |
|
|  | [Dotm](#Dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) représente des fichiers modèle créés avec Microsoft Word 2007 ou version ultérieure. |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML stocké dans un fichier XML plat au lieu d’un paquet ZIP. |
|
|  | [Rtf](#Rtf) | Rich Text Format (RTF) représente une méthode d’encodage du texte formaté et des graphiques pour une utilisation dans les applications. |
|
|  | [Odt](#Odt) | Les fichiers Open Document Format Text Document (ODT) sont un type de documents créés avec des applications de traitement de texte basées sur le format de fichier texte OpenDocument. |
|
|  | [Ott](#Ott) | Open Document Format Text Document Template (OTT) représente des documents modèle générés par des applications conformes au format standard OpenDocument de l’OASIS. |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML Format — WordProcessingML ou WordML (.XML). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAll()](#getAll--) | Obtient une collection énumérable de tous les [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Récupère une instance du type spécifié [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) qui possède l’extension de fichier spécifiée. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convertit une chaîne représentant une extension de fichier en un objet [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats). |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


MS Word 97-2007 Binary File Format (DOC) représente les documents générés par Microsoft Word ou d’autres documents de traitement de texte au format binaire.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Office Open XML WordProcessingML Macro-Free Document (DOCX) est un format bien connu pour les documents Microsoft Word.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


MS Word 97-2007 Template (DOT) sont des fichiers modèle créés par Microsoft Word pour disposer de paramètres préformatés en vue de la génération de futurs fichiers DOC ou DOCX.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Les fichiers Office Open XML WordProcessingML Macro-Enabled Document (DOCM) sont des documents générés par Microsoft Word 2007 ou version ultérieure avec la capacité d’exécuter des macros.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Office Open XML WordprocessingML Macro-Free Template (DOTX) sont des fichiers modèle créés par Microsoft Word pour disposer de paramètres préformatés en vue de la génération de futurs fichiers DOCX.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Office Open XML WordprocessingML Macro-Enabled Template (DOTM) représente des fichiers modèle créés avec Microsoft Word 2007 ou version ultérieure.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML stocké dans un fichier XML plat au lieu d’un paquet ZIP.


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


Rich Text Format (RTF) représente une méthode d’encodage du texte formaté et des graphiques pour une utilisation dans les applications.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Les fichiers Open Document Format Text Document (ODT) sont un type de documents créés avec des applications de traitement de texte basées sur le format de fichier texte OpenDocument.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Open Document Format Text Document Template (OTT) représente des documents modèle générés par des applications conformes au format standard OpenDocument de l’OASIS.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML Format — WordProcessingML ou WordML (.XML).

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


Obtient une collection énumérable de tous les [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).
Valeur : un IEnumerable{WordProcessingFormats} contenant toutes les instances de [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


Récupère une instance du type spécifié [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) qui possède l’extension de fichier spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier du format du document. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


Convertit une chaîne représentant une extension de fichier en un objet [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.

