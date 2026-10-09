---
title: "EBookFormats"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Encapsule tous les formats eBook."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

Encapsule tous les formats eBook. Inclut les types de fichiers suivants :
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
En savoir plus sur le format Mobi [ici](../https://docs.fileformat.com/ebook/mobi/), et sur le format ePub [ici](../https://docs.fileformat.com/ebook/epub/).

## Champs

| Champ | Description |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI est le nom donné au format développé pour le lecteur MobiPocket. |
|
|  | [Epub](#Epub) | Le format Electronic Publication (IDPF ePub) est un format de fichier e-book qui fournit un format de publication numérique standard pour les éditeurs et les consommateurs. |
|
|  | [Azw3](#Azw3) | AZW3, également connu sous le nom de Kindle Format 8 (KF8), est la version modifiée du format de fichier numérique e-book AZW développé pour les appareils Amazon Kindle. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAll()](#getAll--) | Obtient une collection énumérable de tous les [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Récupère une instance du type spécifié [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) qui possède l'extension de fichier spécifiée. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Convertit une chaîne représentant une extension de fichier en un objet [EBookFormats](../../com.groupdocs.editor.formats/ebookformats). |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI est le nom donné au format développé pour le lecteur MobiPocket. Aussi appelé PRC, AZW.
Il est actuellement utilisé par Amazon avec un schéma DRM légèrement différent et appelé AZW.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Le format Electronic Publication (IDPF ePub) est un format de fichier e-book qui fournit un format de publication numérique standard pour les éditeurs et les consommateurs.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, également connu sous le nom de Kindle Format 8 (KF8), est la version modifiée du format de fichier numérique e-book AZW développé pour les appareils Amazon Kindle.
Le format est une amélioration des anciens fichiers AZW.
En savoir plus sur ce format de fichier
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


Obtient une collection énumérable de tous les [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).
Valeur : Un IEnumerable{EBookFormats} contenant toutes les instances de [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Récupère une instance du type spécifié [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) qui possède l'extension de fichier spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier du format de document. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


Convertit une chaîne représentant une extension de fichier en un objet [EBookFormats](../../com.groupdocs.editor.formats/ebookformats).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | extension | java.lang.String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

