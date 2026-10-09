---
title: "XmlFormatOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Contient des options permettant d’ajuster le formatage du document XML lorsqu’il est représenté en HTML"
type: docs
weight: 52
url: /fr/nodejs-java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

Contient des options qui permettent d’ajuster le formatage du document XML lorsqu’il est représenté en HTML.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | Lorsqu’activée, chaque paire attribut‑valeur dans chaque élément XML sera placée sur une nouvelle ligne. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | Lorsqu’activée, chaque paire attribut‑valeur dans chaque élément XML sera placée sur une nouvelle ligne. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | Lorsqu’activée, les nœuds texte feuilles (contenu textuel à l’intérieur des éléments XML, qui n’ont pas d’enfants) seront rendus sur une nouvelle ligne avec un retrait gauche plus important. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | Lorsqu’activée, les nœuds texte feuilles (contenu textuel à l’intérieur des éléments XML, qui n’ont pas d’enfants) seront rendus sur une nouvelle ligne avec un retrait gauche plus important. |
|
|  | [getLeftIndent()](#getLeftIndent--) | Permet de spécifier un décalage pour le retrait gauche de chaque nouvelle ligne. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Permet de spécifier un décalage pour le retrait gauche de chaque nouvelle ligne. |
|
|  | [isDefault()](#isDefault--) | Indique si cette instance d'options de formatage XML possède une valeur par défaut |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


Lorsqu’activée, chaque paire attribut‑valeur dans chaque élément XML sera placée sur une nouvelle ligne.
Par défaut, la valeur est false (désactivé) \\u2014 toutes les paires attribut-valeur sont placées sur une seule ligne.


**Returns:**
booléen
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


Lorsqu’activée, chaque paire attribut‑valeur dans chaque élément XML sera placée sur une nouvelle ligne.
Par défaut, la valeur est false (désactivé) \\u2014 toutes les paires attribut-valeur sont placées sur une seule ligne.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


Lorsqu’activée, les nœuds texte feuilles (contenu textuel à l’intérieur des éléments XML, qui n’ont pas d’enfants) seront rendus sur une nouvelle ligne avec un retrait gauche plus important.
Par défaut, la valeur est false (désactivé) \\u2014 les nœuds texte feuilles sont placés sur la même ligne que leurs parents, sans nouvelle indentation.


**Returns:**
booléen
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


Lorsqu’activée, les nœuds texte feuilles (contenu textuel à l’intérieur des éléments XML, qui n’ont pas d’enfants) seront rendus sur une nouvelle ligne avec un retrait gauche plus important.
Par défaut, la valeur est false (désactivé) \\u2014 les nœuds texte feuilles sont placés sur la même ligne que leurs parents, sans nouvelle indentation.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


Permet de spécifier un décalage pour l'indentation gauche de chaque nouvelle ligne. Ne peut pas être une valeur non nulle sans unité. Par défaut, la valeur est 10pt


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


Permet de spécifier un décalage pour l'indentation gauche de chaque nouvelle ligne. Ne peut pas être une valeur non nulle sans unité. Par défaut, la valeur est 10pt


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indique si cette instance d'options de formatage XML possède une valeur par défaut


**Returns:**
booléen
