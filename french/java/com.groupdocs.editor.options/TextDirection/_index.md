---
title: "TextDirection"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente 3 variantes possibles de la façon de traiter la direction du texte dans les documents texte brut"
type: docs
weight: 38
url: /fr/java/com.groupdocs.editor.options/textdirection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextDirection extends System.Enum
```

Représente 3 variantes possibles de la façon de traiter la direction du texte dans le texte brut
documents

## Champs

| Champ | Description |
| --- | --- |
|  | [LeftToRight](#LeftToRight) | Direction de gauche à droite, texte habituel, valeur par défaut. |
|
|  | [RightToLeft](#RightToLeft) | Direction de droite à gauche |
|
|  | [Auto](#Auto) | Détection automatique de la direction. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTextDirection()](#getTextDirection--) |  |
### LeftToRight {#LeftToRight}
```
public static final int LeftToRight
```


Direction de gauche à droite, texte habituel, valeur par défaut.


### RightToLeft {#RightToLeft}
```
public static final int RightToLeft
```


Direction de droite à gauche


### Auto {#Auto}
```
public static final int Auto
```


Détection automatique de la direction. Lorsque cette option est sélectionnée et que le texte contient
des caractères appartenant à des scripts RTL, la direction du document sera définie
automatiquement en RTL.


### getTextDirection() {#getTextDirection--}
```
public static int[] getTextDirection()
```




**Returns:**
int[]
