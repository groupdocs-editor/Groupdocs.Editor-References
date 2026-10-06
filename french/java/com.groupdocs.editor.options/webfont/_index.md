---
title: "WebFont"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente des paramètres de police pour le web."
type: docs
weight: 43
url: /fr/java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

Représente des paramètres de police pour le web.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getColor()](#getColor--) | Couleur de police au format ARGB32 |
|
|  | [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Couleur de police au format ARGB32 |
|
|  | [getWeight()](#getWeight--) | Définit le poids (ou l'épaisseur) de la police |
|
|  | [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Définit le poids (ou l'épaisseur) de la police |
|
|  | [getStyle()](#getStyle--) | Définit si une police doit être stylisée avec un style normal, italique ou oblique à partir de sa famille de polices. |
|
|  | [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Définit si une police doit être stylisée avec un style normal, italique ou oblique à partir de sa famille de polices. |
|
|  | [getLine()](#getLine--) | Définit une ligne ou une combinaison de lignes, appliquée au texte. |
|
|  | [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Définit une ligne ou une combinaison de lignes, appliquée au texte. |
|
|  | [getSize()](#getSize--) | Définit la taille de la police en unités absolues ou relatives. |
|
|  | [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Définit la taille de la police en unités absolues ou relatives. |
|
|  | [getName()](#getName--) | Définit le nom de la police. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Définit le nom de la police. |
|
|  | [deepClone()](#deepClone--) | Crée et renvoie une copie profonde complète de cette instance [WebFont](../../com.groupdocs.editor.options/webfont). |
|
|  | [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | Détermine si cette instance de WebFont est égale à celle spécifiée. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance de WebFont est égale à l'objet non casté spécifié. |
|
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


Couleur de police au format ARGB32


**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


Couleur de police au format ARGB32


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


Définit le poids (ou l'épaisseur) de la police


**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


Définit le poids (ou l'épaisseur) de la police


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


Définit si une police doit être stylisée avec un style normal, italique ou oblique à partir de sa famille de polices.


**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


Définit si une police doit être stylisée avec un style normal, italique ou oblique à partir de sa famille de polices.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


Définit une ligne ou une combinaison de lignes, appliquée au texte.


**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


Définit une ligne ou une combinaison de lignes, appliquée au texte.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


Définit la taille de la police en unités absolues ou relatives.


**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


Définit la taille de la police en unités absolues ou relatives.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


Définit le nom de la police. Si aucun n'est spécifié, la police par défaut sera utilisée.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Définit le nom de la police. Si aucun n'est spécifié, la police par défaut sera utilisée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


Crée et renvoie une copie profonde complète de cette instance [WebFont](../../com.groupdocs.editor.options/webfont).


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one

### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


Détermine si cette instance de WebFont est égale à celle spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [WebFont](../../com.groupdocs.editor.options/webfont) | Un autre WebFont pour vérifier l'égalité, peut être NULL. |
|

**Returns:**
booléen - vrai si égal, faux si différent.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance de WebFont est égale à l'objet non casté spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | Objet, qui doit être une instance [WebFont](../../com.groupdocs.editor.options/webfont). |
|

**Returns:**
booléen - vrai si égal, faux si différent.

