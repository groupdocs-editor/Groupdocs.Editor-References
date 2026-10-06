---
title: "TextualFormats"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Regroupe tous les formats textuels basés sur du texte, y compris le balisage XML, HTML et d'autres."
type: docs
weight: 16
url: /fr/java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

Encapsule tous les formats textuels (basés sur du texte), y compris le balisage (XML, HTML) et d'autres.
Inclut les formats suivants :
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## Champs

| Champ | Description |
| --- | --- |
|  | [Html](#Html) | Le document HyperText Markup Language (HTML) est l'extension des pages web créées pour être affichées dans les navigateurs. |
|
|  | [Xml](#Xml) | Le document eXtensible Markup Language (XML) est similaire à HTML mais diffère par l'utilisation de balises pour définir des objets. |
|
|  | [Txt](#Txt) | Le document texte brut (TXT) représente un document contenant du texte simple sous forme de lignes. |
|
|  | [Md](#Md) | Markdown est un langage de balisage léger pour créer du texte formaté à l'aide d'un éditeur texte simple. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation) est un format de fichier standard ouvert pour le partage de données qui utilise du texte lisible par l'homme pour stocker et transmettre les données. |
|
|  | [Mhtml](#Mhtml) | L'encapsulation MIME de documents HTML agrégés est un format d'archive de pages web utilisé pour combiner, dans un seul fichier informatique, le code HTML et ses ressources associées. |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help est un format binaire d'aide en ligne propriétaire de Microsoft, composé d'une collection de pages HTML, d'un index et d'autres outils de navigation. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAll()](#getAll--) | Obtient une collection énumérable de tous les [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Récupère une instance du type spécifié [TextualFormats](../../com.groupdocs.editor.formats/textualformats) qui possède l'extension de fichier spécifiée. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convertit une chaîne représentant une extension de fichier en un objet [TextualFormats](../../com.groupdocs.editor.formats/textualformats). |
|
### Html {#Html}
```
public static final TextualFormats Html
```


Le document HyperText Markup Language (HTML) est l'extension des pages web créées pour être affichées dans les navigateurs.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


Le document eXtensible Markup Language (XML) est similaire à HTML mais diffère par l'utilisation de balises pour définir des objets.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


Le document texte brut (TXT) représente un document contenant du texte simple sous forme de lignes.
En savoir plus sur ce format de fichier
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown est un langage de balisage léger pour créer du texte formaté à l'aide d'un éditeur texte simple.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation) est un format de fichier standard ouvert pour le partage de données qui utilise du texte lisible par l'homme pour stocker et transmettre les données.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


L'encapsulation MIME de documents HTML agrégés est un format d'archive de pages web utilisé pour combiner, dans un seul fichier informatique, le code HTML et ses ressources associées.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help est un format binaire d'aide en ligne propriétaire de Microsoft, composé d'une collection de pages HTML, d'un index et d'autres outils de navigation.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


Obtient une collection énumérable de tous les [TextualFormats](../../com.groupdocs.editor.formats/textualformats).
Valeur : un IEnumerable{TextualFormats} contenant toutes les instances de [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Récupère une instance du type spécifié [TextualFormats](../../com.groupdocs.editor.formats/textualformats) qui possède l'extension de fichier spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier du format du document. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


Convertit une chaîne représentant une extension de fichier en un objet [TextualFormats](../../com.groupdocs.editor.formats/textualformats).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

