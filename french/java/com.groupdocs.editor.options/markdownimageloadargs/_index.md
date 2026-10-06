---
title: "MarkdownImageLoadArgs"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Fournit les données pour l’événement MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs."
type: docs
weight: 22
url: /fr/java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Fournit les données pour le

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

événement.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Obtient ou définit le nom de fichier (tel qu’il apparaît dans le document Markdown) qui sera |
traité.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Obtient ou définit le nom de fichier (tel qu’il apparaît dans le document Markdown) qui sera |
traité.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Obtient une valeur indiquant si cette image possède un lien URI absolu. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Obtient une valeur indiquant si cette image possède un lien URI absolu. |
|
|  | [setData(byte[] data)](#setData-byte---) | Définit les données fournies par l’utilisateur pour la ressource qui sont utilisées si |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


Obtient ou définit le nom de fichier (tel qu’il apparaît dans le document Markdown) qui sera
traité.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Obtient ou définit le nom de fichier (tel qu’il apparaît dans le document Markdown) qui sera
traité.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Obtient une valeur indiquant si cette image possède un lien URI absolu.
Valeur : true si cette image possède un lien URI absolu ; sinon, false.


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Obtient une valeur indiquant si cette image possède un lien URI absolu.
Valeur : true si cette image possède un lien URI absolu ; sinon, false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Définit les données fournies par l’utilisateur pour la ressource qui sont utilisées si

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] |  |

