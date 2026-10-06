---
title: "TextSaveOptions"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Permet de spécifier des options personnalisées pour la génération et l'enregistrement de documents texte brut TXT"
type: docs
weight: 41
url: /fr/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Permet de spécifier des options personnalisées pour la génération et l'enregistrement de texte brut (TXT)
documents

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Encodage des caractères du document texte, qui sera appliqué à son |
enregistrement
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Encodage des caractères du document texte, qui sera appliqué à son |
enregistrement
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Spécifie s'il faut ajouter des marques bidirectionnelles avant chaque séquence BiDi lors du |
exportation au format texte brut.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Spécifie s'il faut ajouter des marques bidirectionnelles avant chaque séquence BiDi lors du |
exportation au format texte brut
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Spécifie si le programme doit tenter de préserver la mise en page des tableaux |
lors de l'enregistrement au format texte brut.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Spécifie si le programme doit tenter de préserver la mise en page des tableaux |
lors de l'enregistrement au format texte brut.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Encodage des caractères du document texte, qui sera appliqué à son
enregistrement


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Encodage des caractères du document texte, qui sera appliqué à son
enregistrement


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Spécifie s'il faut ajouter des marques bidirectionnelles avant chaque séquence BiDi lors du
exportation au format texte brut. La valeur par défaut est 'false' \\u2014 ne pas ajouter de marques BiDi.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Spécifie s'il faut ajouter des marques bidirectionnelles avant chaque séquence BiDi lors du
exportation au format texte brut


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Spécifie si le programme doit tenter de préserver la mise en page des tableaux
lors de l'enregistrement au format texte brut. La valeur par défaut est false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Spécifie si le programme doit tenter de préserver la mise en page des tableaux
lors de l'enregistrement au format texte brut. La valeur par défaut est false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

