---
title: "FixedLayoutFormats"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Encapsule tous les formats à mise en page fixe, également appelés formats à page fixe, qui incluent PDF et XPS ; cela n’inclut pas les images raster."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.editor.formats/fixedlayoutformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class FixedLayoutFormats extends DocumentFormatBase
```

Encapsule tous les formats à mise en page fixe (également appelés "fixed-page") qui incluent PDF et XPS (cela n'inclut pas les images raster)

<br />

*** ** * ** ***

Diverses applications de visualisation ou de publication de documents permettent aux utilisateurs d’ouvrir (Adobe Acrobat, XPS Viewer) et parfois de modifier (Adobe InDesign) des documents de formats spécifiques. Ces applications produisent généralement des documents au format \\u201cfixed-page\\u201d. Un tel format de document décrit précisément où le contenu d’un document\\u2019s est placé sur chaque page. En interne, le format PDF ou XPS contient une description de chaque page, ainsi que des instructions de dessin, spécifiant la mise en page du contenu sur la page. Cela ressemble aux formats d’image, décrivant où le contenu est affiché soit sous forme raster, soit sous forme vectorielle.

<br />


## Champs

| Champ | Description |
| --- | --- |
|  | [Pdf](#Pdf) | Le format de document portable (PDF) est un type de document créé par Adobe dans les années 1990. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAll()](#getAll--) | Obtient une collection énumérable de tous les [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Récupère une instance du type spécifié [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) qui possède l’extension de fichier spécifiée. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convertit une chaîne représentant une extension de fichier en un objet [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats). |
|
### Pdf {#Pdf}
```
public static final FixedLayoutFormats Pdf
```


Le format de document portable (PDF) est un type de document créé par Adobe dans les années 1990. Le but de ce format de fichier était d’introduire une norme pour la représentation de documents et d’autres supports de référence dans un format indépendant du logiciel applicatif, du matériel ainsi que du système d’exploitation.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/pdf/)
.


### getAll() {#getAll--}
```
public static List<FixedLayoutFormats> getAll()
```


Obtient une collection énumérable de tous les [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).
Valeur : Un IEnumerable{FixedLayoutFormats} contenant toutes les instances de [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.FixedLayoutFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FixedLayoutFormats fromExtension(String extension)
```


Récupère une instance du type spécifié [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) qui possède l’extension de fichier spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier du format de document. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - An instance of the specified type [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static FixedLayoutFormats fromString(String extension)
```


Convertit une chaîne représentant une extension de fichier en un objet [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |
|

**Returns:**
[FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) - A [FixedLayoutFormats](../../com.groupdocs.editor.formats/fixedlayoutformats) object corresponding to the specified file extension.

